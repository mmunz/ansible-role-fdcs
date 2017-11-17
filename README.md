c1.froxlor-fdcs
===============

This role can be used to setup [fdcs](https://github.com/mmunz/fdcs), the Froxlor Docker Customer Shell on Debian hosts.

Requirements
------------

The role itself has no requirements but expects that froxlor is installed and setup.

The role does not add a newer kernel from backports or set grub parameters fpr memory cgroup support.
See the README of fdcs for details on how to enable these features.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: froxlor-servers
      roles:
         - c1.froxlor-fdcs


