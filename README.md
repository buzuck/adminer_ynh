# Adminer for Yunohost

[![Integration level](https://dash.yunohost.org/integration/adminer.svg)](https://dash.yunohost.org/appci/app/adminer) ![](https://ci-apps.yunohost.org/ci/badges/adminer.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/adminer.maintain.svg)  
[![Install adminer with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=adminer)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install adminer quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Replace phpMyAdmin with Adminer and you will get a tidier user interface, better support for MySQL features, higher performance and more security. See detailed comparison https://www.adminer.org/en/phpmyadmin/.
Adminer development priorities are: 1. Security, 2. User experience, 3. Performance, 4. Feature set, 5. Size.

Adminer (formerly phpMinAdmin better alternate to phpmyadmin) is a full-featured database management tool written in PHP.

You need to know the root password from here /etc/yunohost/mysql or the app username and password from setting.yml under /etc/yunohost/apps/appname to login.
For themes download the adminer.css from the main website and put the file in the app folder.
If you have problems with drivers see here: https://www.adminer.org/en/drivers.



**Shipped version:** 4.7.6

## Screenshots

![](https://www.adminer.org/static/screenshots/db.png)

## Demo

* [Official demo](https://demo.adminer.org/adminer.php?username=)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported?
 * Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/adminer_%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/adminer/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/adminer_%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/adminer/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/adminer_ynh/issues
 * App website: https://www.adminer.org/
 * Upstream app repository: https://github.com/vrana/adminer/
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
or
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```
