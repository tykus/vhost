vhost
=====

A shell script for creating virtual hosts

About
-----
vhost is a shell script which takes a single argument, the name of a Virtual Host. 
* Writes a site-available file, and enables it. 
* Creates a /etc/hosts entry for the virtual host, restarts apache2 service. 
* Creates a webroot directory in a pre-existing ~/webdev directory
* Writes a phpinfo file in webroot for test purposes


Requirements
------------
* Apache2
* Current user is sudoer


Execution
---------
<pre>~/bin/vhost www.name.dev </pre>
or, if your bin is in your PATH
<pre>vhost www.name.dev<pre>

