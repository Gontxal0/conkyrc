Conky configuration file
========================

This is Side_thin configuration:

![Conky](https://raw.github.com/Gontxal0/conkyrc/master/previews/Side_thin.jpeg)

This is Smooth_blue configuration:

![Conky](https://raw.github.com/Gontxal0/conkyrc/master/previews/Smooth_blue.png)

This is Smooth_DArk_blue configuration:

![Conky](https://raw.github.com/Gontxal0/conkyrc/master/previews/Smooth_Dark_blue.png)

This is Smooth_Neon configuration:

![Conky](https://raw.github.com/Gontxal0/conkyrc/master/previews/Smooth_Neon.png)

This is Steel configuration:

![Conky](https://raw.github.com/Gontxal0/conkyrc/master/previews/Steel.png)

This is Zenzire configuration:

![Conky](https://raw.github.com/Gontxal0/conkyrc/master/previews/Zenzire.png)



Installation
------------

Fetch the configuration files from GitHub repository:

``
$ git clone git://github.com/Gontxal0/conkyrc.git ~/.conky
``

Create link:

``
ln -s ~/.conky/conkyrc_ApropiateName ~/.conkyrc
``

Enjoy!

Features
--------

* weather with forecast
* CPU graph
* memory graph
* network graph
* processes

Origen
------------
http://speedracker.deviantart.com/art/Side-thin-conky-Made-for-Conky-Manager-513212857
http://sarai-the-geek.deviantart.com/art/Steel-Conky-496210321
https://github.com/zenzire/conkyrc

Tutos
------
http://conky.sourceforge.net/config_settings.html
http://conky.sourceforge.net/faq.html
https://wiki.archlinux.org/index.php/Conky
http://www.ochobitshacenunbyte.com/2015/04/16/utilizar-conky-debian-jessie/
https://wiki.gentoo.org/wiki/Conky/Guide
http://www.tecmint.com/install-conky-in-ubuntu-debian-fedora/
http://custom-linux.deviantart.com/gallery/39357745/Conky-Themes
https://wiki.archlinux.org/index.php/Conky
https://forum.manjaro.org/index.php?topic=7982.0
http://custom-linux.deviantart.com/gallery/39357745/Conky-Themes
http://custom-linux.deviantart.com/gallery/39357745/Conky-Themes?set=39357745&offset=0


Notes
------
Place the Aller folder in ~/.fonts or /usr/share/fonts and run

``
fc-cache -fv
``

to update the font cache.

In order for the weather to display properly you need to find the ICAO
code for your nearest airport and insert it in the two places in the script
where it says *ICAO*. Remove the asterisks.
