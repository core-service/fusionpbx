DIYPBX Changes
--------------------------------------
The configrtaion remains the same as the Fusionpbx Git except for some changes to match our tutorials

Made sure NFTables is Uninstalled and IPTables is installed
Pointed the fusionpbx clone location to the DIYPBX git server
Added our own filewall script

What is [FusionPBX](https://www.fusionpbx.com/)?
--------------------------------------

[FusionPBX](https://www.fusionpbx.com/) can be used as a single or domain based multi-tenant PBX, carrier grade switch, call center server, fax server, VoIP server, voicemail server, conference server, voice application server, multi-tenant appliance framework and more. [FreeSWITCH™](https://freeswitch.com) is a highly scalable, multi-threaded, multi-platform communication platform. 

It provides the functionality your business needs and brings carrier grade switching, and corporate-level phone system features to small, medium, and large businesses. Read more at [FusionPBX](https://www.fusionpbx.com/). [Please visit our youtube channel](https://www.youtube.com/FusionPBX)

In addition to providing all of the usual PBX functionality, FusionPBX allows you to configure:

- Multi-Tenant
- Unlimited Extensions
- Voicemail-to-Email
- Device Provisioning
- Music on Hold
- Call Parking
- Automatic Call Distribution
- Interactive Voice Response
- Ring Groups
- Find Me / Follow Me
- Hot desking
- High Availability and Redundancy
- Dialplan Programming that allow nearly endless possibilities
- [Many other Features](https://docs.fusionpbx.com/en/latest/features/features.html)

Software Requirements
--------------------------------------

- FusionPBX will run on Debian, Ubuntu LTS, FreeBSD, CentOS, and more.
- [FusionPBX Installer](https://www.fusionpbx.com/download.php)

How to Install FusionPBX
----------------------------
* As root do the following:

Debian Install
```
wget -O - https://raw.githubusercontent.com/diypbx/fusionpbx-install.sh/master/debian/pre-install.sh | sh;
cd /usr/src/fusionpbx-install.sh/debian && ./install.sh
```

