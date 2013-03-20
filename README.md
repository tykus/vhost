vhost
=====

A shell script for creating virtual hosts

About
-----
vhost is a shell script which takes a single argument, the name of a Virtual Host. 
1. Writes a site-available file, and enables it. 
1. Creates a /etc/hosts entry for the virtual host, restarts apache2 service. 
1. Creates a webroot directory in a pre-existing ~/webdev directory
1. Writes a phpinfo file in webroot for test purposes


Requirements
------------
Apache2
Current user is sudoer


Execution
---------
~/bin/vhost www.name.dev 
or, if your bin is in your PATH
vhost www.name.dev

