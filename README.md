<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Guacamole for YunoHost

[![Integration level](https://dash.yunohost.org/integration/guacamole.svg)](https://dash.yunohost.org/appci/app/guacamole) ![Working status](https://ci-apps.yunohost.org/ci/badges/guacamole.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/guacamole.maintain.svg)  
[![Install Guacamole with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=guacamole)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Guacamole quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Clientless remote desktop gateway. It supports standard protocols like VNC, RDP, and SSH.

**Shipped version:** 1.4.0~ynh1

## Screenshots

![Screenshot of Guacamole](./doc/screenshots/screenshot1.jpg)

## Disclaimers / important information

## Configuration

The user that is configured as admin during install will have access to admin settings in the settings menu of the app (under the user menu). Configuration files are in `/opt/yunohost/guacamole/etc/guacamole` (for the first install).

## Documentation and resources

* Official app website: <https://guacamole.apache.org/>
* Official admin documentation: <https://guacamole.apache.org/doc/gug/>
* Upstream app code repository: <https://github.com/search?utf8=%E2%9C%93&q=repo%3Aapache%2Fguacamole-server+repo%3Aapache%2Fguacamole-client+repo%3Aapache%2Fguacamole-website&type=Repositories&ref=searchresults>
* YunoHost documentation for this app: <https://yunohost.org/app_guacamole>
* Report a bug: <https://github.com/YunoHost-Apps/guacamole_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/guacamole_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/guacamole_ynh/tree/testing --debug
or
sudo yunohost app upgrade guacamole -u https://github.com/YunoHost-Apps/guacamole_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
