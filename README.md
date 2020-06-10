# Framaforms for YunoHost

[![Integration level](https://dash.yunohost.org/integration/framaforms.svg)](https://dash.yunohost.org/appci/app/framaforms) ![](https://ci-apps.yunohost.org/ci/badges/framaforms.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/framaforms.maintain.svg)    
[![Install FramaForms with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=framaforms)

> *This package allow you to install Framaforms quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Framaforms helps you create online webforms and surveys.
See https://framablog.org/2016/10/05/framaforms-noffrez-plus-les-reponses-que-vous-collectez-a-google/ (in French) and https://framablog.org/2016/10/05/en-savoir-un-peu-plus-sur-le-projet-framaforms/ (in French) for further informations.

**Shipped version:** 1.0.0+190618

## Screenshots

![Animation that present how to build a form with Framaforms](https://framaforms.org/sites/default/files/imgforms/anim_creation.gif)

## Demo

* [Official demo](https://framaforms.org/)

## Configuration

You can change some configuration by using the Framaforms administration panel. You can log in with the administrator user and the password you gave during the installation.

## Documentation

 * Official documentation: https://docs.framasoft.org/fr/framaforms/

## YunoHost specific features

#### Multi-users support

* Are LDAP and HTTP auth supported? **No**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/framaforms%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/framaforms/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/framaforms%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/framaforms/)

## Limitations

* Any known limitations.

## Additional information

* Other information you would add about this application

## Links

 * Report a bug: https://github.com/YunoHost-Apps/framaforms_ynh/issues
 * App website: https://framaforms.org/
 * Upstream app repository: https://framagit.org/framasoft/framaforms
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/framaforms_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/framaforms_ynh/tree/testing --debug
or
sudo yunohost app upgrade framaforms -u https://github.com/YunoHost-Apps/framaforms_ynh/tree/testing --debug
```
