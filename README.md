HTPC Guides Media Server Installer for Ubuntu and Debian
========================

This is an automated installer for Home Media Server setups from [HTPC Guides](http://www.htpcguides.com) for Debian and Ubuntu. It will be maintained as part of a school project so please **small pull requests welcome** if you want to fork the framework use [Igor's repository](https://github.com/igorpecovnik/Debian-micro-home-server).

It currently supports ARM, x86 and x64 devices

![SOHO server](http://www.htpcguides.com/wp-content/uploads/2015/05/HTPC-Guides-installer-Main-screen-600x331.png)

This projecti's framework is based on Igor's [Micro Home Server](http://www.igorpecovnik.com/2013/12/10/micro-home-server/)

If you only need Igor's services, use his fork which has these programs

Samba, TV headend, BitTorrent Sync, SoftEther VPN server, CUPS, scanner + buttons + OCR, Temper, Rpimonitor + 3 additional sensors, Transmission, ISPConfig  (Apache2 or NginX, PHP, Mysql with phpMyAdmin, Postfix, Dovecot)

The HTPC Guides fork includes these programs
NZBGet, Sabnzbd, Sonarr, SickRage, CouchPotato, HTPC Manager, CherryMusic, Kodi and more will be added.


HTPC Guides Media Server Installation
------------------

```shell
sudo apt-get -y install git
cd ~
git clone https://github.com/blindpet/MediaServerInstaller ~/HTPCGuides
cd ~/HTPCGuides
sudo bash install.sh
```

**If you want to include this installer in any distro images please ask**

Donate to Igor's project
------------------

[![Paypal donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CUYH2KR36YB7W)

![Igor's bitcoin address](http://www.igorpecovnik.com/wp-content/uploads/2014/10/bitcoinigor.png)

17vT6hV83EQ6rizbWeasfy1tWEzFpzYqEE
