# Gotify pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/gotify.svg)](https://dash.yunohost.org/appci/app/gotify) ![](https://ci-apps.yunohost.org/ci/badges/gotify.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/gotify.maintain.svg)  
[![Install Gotify with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=gotify)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Gotify rapidement et simplement sur un serveur Yunohost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble
Gotify est un serveur simple permettant d'envoyer et de recevoir des messages via websocket.

**Version incluse :** 2.1.4

## Captures d'écran

[![Screenshot](https://raw.githubusercontent.com/gotify/server/master/ui.png)](https://github.com/gotify/server)

## Configuration

Pour configurer Gotify :
> Éditer le fichier `config.yml` avec SSH.

## Documentation

 * Documentation officielle : https://gotify.net/docs/index
 * Documentation YunoHost : https://yunohost.org/#/app_gotify_fr

#### Support multi-utilisateurs

Pas de support de LDAP (non implémenté upstream)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/gotify_ynh/issues
 * Site de l'application : https://gotify.net/
 * Dépôt de l'application principale : https://github.com/gotify/server
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/gotify_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/gotify_ynh/tree/testing --debug
ou
sudo yunohost app upgrade gotify -u https://github.com/YunoHost-Apps/gotify_ynh/tree/testing --debug
```
