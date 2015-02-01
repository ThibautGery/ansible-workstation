Ansible Workstation
===================

This project is the [ansible](http://docs.ansible.com/index.html) scripts to install my developpement workstation

Requirements
------------

 * Work station :
   - Ubuntu
   - Python 2.7
   - SSH enabled (sudo apt-get install ssh)
   - Port 22 accessible (configure iptables)
 * Runner (machine that will run ansible)
  - POSIX terminal (not windows)
  - Python 2.7
  - Ansible

It's possible to only use one Machine

Component
---------

 * Git
 * Vim
 * Java


Utilisation
-----------

All you have to do is `ansible-playbook site.yml  --extra-vars '@example.json' -K` and replace example.json with yours settings.



Todo
----
 * Add a script to run everything from one computer with only requirement : linux
