.. _install:


Install
=======

**Tested on Fedora 24 and AWS Linux version 7.0**

Fedora OS:

local build::

	make rpm
	sudo dnf reinstall rpmbuild/RPMS/x86_64/cd2cloud-0.0.1-1.x86_64.rpm

copr repo::

 	sudo dnf install copr....

AWS Linux OS:

copr repo::

 	sudo yum install copr....

