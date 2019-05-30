# Gotify for YunoHost

[![Integration level](https://dash.yunohost.org/integration/gotify.svg)](https://dash.yunohost.org/appci/app/gotify)
[![Install Gotify with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=gotify)

*[Lire ce readme en français.](./README_fr.md)*
> *This package allow you to install Gotify quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Gotify is a simple server for sending and receiving messages in real-time per web socket. (Includes a sleek web-ui)

**Shipped version:** 2.0.5

## Screenshots

[![Screenshot](https://raw.githubusercontent.com/gotify/server/master/ui.png)](https://github.com/gotify/server)


## Configuration

How to configure this app:
> Edit config.yml file via SSH.

## Documentation

 * Official documentation: [here](https://gotify.net/docs/index)

#### Multi-users support

LDAP not supported.

## Limitations

 * Require dedicated domain like gotify.domain.tld.

 * No LDAP support (blocked until Gotify core upstream implements it)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/gotify_ynh/issues
 * App website: https://gotify.net/
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/gotify_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/gotify_ynh/tree/testing --debug
or
sudo yunohost app upgrade gotify -u https://github.com/YunoHost-Apps/gotify_ynh/tree/testing --debug
```
