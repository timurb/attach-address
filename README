A tool to auto-attach ElasticIP address on instance startup
===========================================================

The idea is simple: run this script on instance startup and it will
attach it to ElasticIP given as a param.


Setup
-----

* Place somewhere in the path the aws tool by Timothy Kay 
(https://github.com/timkay/aws)
* Place user credentials into $HOME/.awssecret with 0600 mode set
* Run this script on instance startup:   attach-address 1.2.3.4

Notes
-----

The AWS user used to attach address should have the only permission 
of ec2:AssociateAddress or otherwise nasty things could be done if
the credentials leak out.
