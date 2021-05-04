.. _acess_to_database:

=======================
Access to the database
=======================

There are three options to grant Rackspace
Technology secure access to your database,
these options are based on where your database
is hosted.

- A Bastion Host: The preferred method for
Rackspace hosted servers or Rackspace managed
cloud servers.
- Remote management and monitoring (RMM): A
dedicated VPN option for remote environments
- A dedicated circuit: A third party option
available to large organizations with unique
security requirements.

A Bastion host
---------------

A Bastion host is a proxy server that provides
secure access to your network. It serves as a
jump server to regulate access to the rest of
the network. Your Bastion hosts provide a safe
way for the Rackspace Technology DBA team to
access your environment. If your database is
already hosted by Rackspace Technology, then
bastion hosts are available to access your
environment. If your database is not hosted
by Rackspace Technology, you may still choose
to install a bastion host on your server to
allow Rackspace DBAs to securely access your
environment. If you decide to install a
bastion host in your remote environment then
you are responsible for all costs, management,
and maintenance of this host.

Remote Management and Monitoring (RMM)
---------------------------------------
If your database is hosted remotely, then
Rackspace Technology can use the RMM dedicated
VPN to access your environment.  To establish
this connection, the Rackspace Technology
team meets with the person in charge of managing
your network to gather details about your
environment, including:

- IP addresses
- VPN device make/model
- VPN Device version
- DNS details

Once this information is collected, Rackspace
works with the network contact to develop a
dedicated VPN.

Dedicated circuits
--------------------
If you require a dedicated circuit, then you
can work with an internet service provider to
set one up. Rackspace Technology allows the
dedicated circuit to connect to the server
where your database is hosted but is not
responsible for managing or maintaining this
option.
