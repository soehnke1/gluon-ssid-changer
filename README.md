ssid-changer
============

Script to change the SSID when there is no suffic sufficient connection to the selected Gateway.

It is quite basic, it just checks the Quality of the Connection and decides if a change of the SSID is necessary.



GLUON_SITE_FEEDS="ssidchanger"<br>
PACKAGES_SSIDCHANGER_REPO=https://github.com/soehnke1/gluon-ssid-changer/<br>
PACKAGES_SSIDCHANGER_COMMIT=06bdf6fc6149af9cbb4564aac82cadd56a98a8b2<br>

With this done you can add the package gluon-ssid-changer to your site.mk

This skript is tested with Gluon 2015.2.1
