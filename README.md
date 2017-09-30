# AWX-on-CentOS-7
AWX is the upstream project from which the Red Hat Ansible Tower offering is ultimately derived. This project uses Vagrant, Virtualbox &amp; Ansible to fire up a working AWX virtual machine.

Based on blog post published on http://khmel.org/?p=1245

Requirements
=============

 	Ansible 2.3.2
 	Virtualbox 5.1.28
 	Vagrant 1.9.7

Getting started
================

1. From a shell

	ansible-galaxy install  geerlingguy.repo-epel
	git clone https://github.com/rhysmeister/AWX-on-CentOS-7
	cd AWX-on-CentOS-7
	vagrant up

2. Access url http://http://192.168.4.111/

3.  Login with;

	u: admin
	p: password
