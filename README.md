TFTP-PXE-Boot-Server
====================

# dnsmasq component
1. use as DHCP&TFTP server
1.1 the tested config in dnsmasq/

# httpd component
1. use as HTTP repo
1.1 ```mount /dev/cdrom /var/www/html/centos```

# ks
It currently has support for network (PXE) installing:

* Centos 7.9.2009 { Manual,Auto }

# Future Work
* EFI boot to support
