HTPC Guides Media Server for ARM Devices
========================

This is an automated installer for Home Media Server programs for [HTPC Guides](http://www.htpcguides.com)

![SOHO server](http://www.htpcguides.com/wp-content/uploads/2015/05/HTPC-Guides-installer-Main-screen-600x331.png)

This projecti's framework is based on Igor's [Micro Home Server](http://www.igorpecovnik.com/2013/12/10/micro-home-server/)

If you only need igor's services, use his fork which has these programs

Samba, TV headend, BitTorrent Sync, SoftEther VPN server, CUPS, scanner + buttons + OCR, Temper, Rpimonitor + 3 additional sensors, Transmission, ISPConfig  (Apache2 or NginX, PHP, Mysql with phpMyAdmin, Postfix, Dovecot)

The HTPC Guides fork includes these programs
NZBGet, Sabnzbd, Sonarr, SickRage, CouchPotato, HTPC Manager, CherryMusic and more will be added.

Tips:
- mail server install (ISPConfig) will work **only with Debian Wheezy**
- set fixed ip address
- for those who use ramlog. You can enable ramlog back when installation is finished
- installation is based on [http://www.howtoforge.com/perfect-server-debian-wheezy-nginx-bind-dovecot-ispconfig-3](http://www.howtoforge.com/perfect-server-debian-wheezy-nginx-bind-dovecot-ispconfig-3)

HTPC Guides Media Server Installation
------------------

```shell
sudo apt-get -y install git
cd ~
git clone https://github.com/blindpet/MediaServerInstaller ~/HTPCGuides
cd ~/HTPCGuides
sudo bash install.sh
```

Donate to Igor's project
------------------

[![Paypal donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CUYH2KR36YB7W)

![My bitcoin address](http://www.igorpecovnik.com/wp-content/uploads/2014/10/bitcoinigor.png)

17vT6hV83EQ6rizbWeasfy1tWEzFpzYqEE
