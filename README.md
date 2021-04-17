# Gotify for YunoHost

[![Integration level](https://dash.yunohost.org/integration/gotify.svg)](https://dash.yunohost.org/appci/app/gotify) ![](https://ci-apps.yunohost.org/ci/badges/gotify.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/gotify.maintain.svg)  
[![Install Gotify with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=gotify)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Gotify quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Gotify is a simple server for sending and receiving messages in real-time per web socket. (Includes a sleek web-ui)

**Shipped version:** 2.0.22

## Screenshots

[![Screenshot](https://raw.githubusercontent.com/gotify/server/master/ui.png)](https://github.com/gotify/server)

## Configuration

How to configure this app:
> Edit `config.yml` file via SSH.

## Documentation

 * Official documentation: https://gotify.net/docs/index
 * YunoHost documentation: https://yunohost.org/#/app_gotify

#### Multi-users support

LDAP is not supported (blocked until Gotify core upstream implements it).

## Links

 * Report a bug: https://github.com/YunoHost-Apps/gotify_ynh/issues
 * App website: https://gotify.net/
 * Upstream app repository: https://github.com/gotify/server
 * YunoHost website: https://yunohost.org/

---

## Developers info

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/gotify_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/gotify_ynh/tree/testing --debug
or
sudo yunohost app upgrade gotify -u https://github.com/YunoHost-Apps/gotify_ynh/tree/testing --debug
```
