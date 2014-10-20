openstack-cloudinit-templates
=============================

That repository contains some usefull cloud-init scripts we are using at Cloudwatt.

List of scripts:
* OpenContrail
 * **deploy_OpenContrail_OpenStack.yaml**: Start an OpenStack and an OpenContrail development environment onto a virtual machine.
* OpenStack
 * devstack
   * **deploy_devstack_all-in-one.yaml**: Start a DevStack onto a virtual machine
* various
 * **final_message_to_grep.yaml**: Write a message a the end of the execution of cloud-init scripts
 * **set_resolvers.yaml**: This is an example file to automatically configure resolv.conf when the instance boots for the first time.
 * **set_ubuntu_password.yaml**: Set the password of the 'ubuntu' user to 'ubuntu' and authorize to use the password authentication with SSH.
