**zrepo - An other third party repository**
==============

*Description*
--------------

RPM Package for legacy driver problems and other software updated by me.
Suittable for Fedora

*Supported Distribution*
--------------
At the moment packages are only for arch x86_64. In alternative there are the source packages. 

- Fedora 18

*How to use*
--------------
- Download the python script "zrepo".
- Move this script to /usr/local/bin
- Run as root: zrepo init
- Update yum: yum update
- See the available packages: yum --disablerepo="*" --enablerepo="zrepo" list available

enjoy

*Support*
--------------

For problems with these packages please contact me via the github Issue tracker or directly at gmrandazzo@gmail.com.

*Credit*
--------------
These packages are based on the official vanilla source and official Fedora source.

