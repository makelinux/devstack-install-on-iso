# devstack-install-on-iso
Automatic installation of DevStack/OpenStack on virtual Ubuntu-Server-14.04.3

Usage:

- Run script devstack-install-on-iso.
- Wait a lot
- Login to created VM with your name and password same as the name.
- Run devstack-start in VM.

Features:

Script devstack-install-on-iso
 - Downloads ISO of Ubuntu-Server-14.04.3
 - Creates kickstart configuration 
 - Runs qemu and installs automatically Ubuntu-Server with kickstart
 - 
Script devstack-start
 - creates local.conf with default configuration 
 - and runs devstack installation.
