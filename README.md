OpenClovis6.1-Installation-for-Solaris11.
=========================================

OpenClovis6.1 Installation for Solaris11 : The Pre-requisites and dependencies are stored in this location.

Pre-installations:
1. Solaris Studio 12.3
2. Java 7

Setting SDK pre-requisites: 
Create a tarball 3rdparty-base-6.1-sun.tar  which comprises the following entities:
	eclipse-SDK-4.2.2-solaris-gtk-x86.zip
	emf-sdo-xsd-SDK-2.2.2.zip
	gcc-3.2.3.tar.gz
	gdbm-1.8.0.tar.gz
	GEF-SDK-3.2.2.zip
	glib-2.28.5.tar.gz
	glibc-2.3.5.tar.gz
	glibc-linuxthreads-2.3.5.tar.gz
	net-snmp-5.4.2.tar.gz
	openhpi-3.0.0.oc.tar.gz
	openhpi-subagent-2.3.4.tar.gz

Installing SDK Dependencies:
1. Create a openclovis-safplus-sdk-6.1-private folder which contains the solaris installation file.(Look into the help.openclovis for detailed information on how to do this.)
2. cd to the  <path/to /the/ openclovis-safplus-sdk-6.1-private>
3. Run the installer file - install-solaris.sh


