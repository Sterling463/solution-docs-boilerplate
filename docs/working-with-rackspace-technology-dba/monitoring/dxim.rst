.. _scom:

=============================================
Deploy Unified Infrastructure Manager (DXIM)
=============================================

You are responsible for helping to meet the
following conditions in order to deploy UIM
within your environment:

- Provide a virtual machine to act as the DXIM hub.
This virtual machine requires resources and
proper configuration. You are also responsible
for any additional costs associated with this virtual machine.
- Restarting and patching the virtual machine as necessary
- Configure your network to allow for the necessary flow of
data and alerts in and out of the UIM Hub

If Rackspace Technology is managing your environment,
the DBA team will provide the following assistance.

- Work with the corresponding Rackspace team for restarting or
patching the virtual machine.
- Deploy a DXIM agent onto each database server and configure with
the appropriate access roles.

The diagram below outlines the network architecture for
deploying the UIM solution.

      .. image:: /_static/img/dxim.png
         :alt: **UIM solution diagram**

The following table summarizes the technical requirements for granting DBA
services access to your environment using a bastion host or a VPN.

      .. image:: /_static/img/tech_table.png
         :alt: **Technical requirements diagram**