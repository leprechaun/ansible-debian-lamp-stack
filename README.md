Debian based ansible controlled LAMP stack
==========================================

These are 2 simple playbooks to setup and deploy code on debian based machines.

* infrastructure
  Install base packages, apache and php, mysql and creates and enables virtual hosts

* deploy-web-applications
  Deploy web applications through git

You will be unable to use this playbook as there is a dependency on a personal ansible module.
The module in question is available at https://github.com/leprechaun/ansible/blob/debian-apache2-module/library/web_infrastructure/debian_apache2

It is most easily replacable by a few shell calls, but will require systematic reloading of apache instead of doing so only when required.
