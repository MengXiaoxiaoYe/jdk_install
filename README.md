# jdk_install

This Ansible role installs Java JDK from a downloaded tar.gz compressed file with the installer.
These installers could be downloaded from the below URL or another repository you prefer:
http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html

1) Place the tar.gz compressed files on the files folder under the role directory.

2) There is a playbook example to run this role on tests folder:
   test.yml

3) This role doesn't require root access and it doesn't use any package manager, so it will probably run on any distro
   with tar package installed.
