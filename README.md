Ansible Workstation
===================

This project is the [ansible](http://docs.ansible.com/index.html) scripts to install my developpement workstation

Requirements
------------

### Machine

 * Work station :
   - Ubuntu 64 bit
   - Python 2.7
   - SSH enabled (sudo apt-get install ssh)
   - Port 22 accessible (configure iptables)
 * Runner (machine that will run ansible)
  - POSIX terminal (not windows)
  - Python 2.7
  - Ansible

It's possible to only use one Machine

### Galaxy

 * [Java](https://galaxy.ansible.com/list#/roles/1209)
 * [Maven](https://galaxy.ansible.com/list#/roles/458)

Components
----------

 * Git
 * Vim
 * Atom
 * Java
 * Maven


Utilisation
-----------
Get external dependencies : `ansible-galaxy install smola.java`

Run `ansible-playbook site.yml  --extra-vars '@example.json' -K -U tge` and replace example.json with yours settings.



Todo
----
 * Add a script to run everything from one computer with only requirement : linux
