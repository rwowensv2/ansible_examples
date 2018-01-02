Postfix
=======

postfix.yml

Summary
=======

Postfix install, copy main.cf start.

Requirements
============

 *relay_server* 

	relay_server = mail.myhost.com

default *relay_server=ourmailserver.ourdomain.com* can be defined by group, or var in play to include
var.


Note(s)
=======

This is an example, consider adding to common role.

https://github.com/rwowensv2
