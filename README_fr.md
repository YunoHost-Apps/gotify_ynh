# Gotify pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/gotify.svg)](https://dash.yunohost.org/appci/app/gotify)
[![Install Gotify with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=gotify)


*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Gotify rapidement et simplement sur un serveur Yunohost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble
Gotify est un simple serveur permettant d'envoyer et de recevoir des messages via websocket.

**Version incluse:** 2.0.10

## Captures d'écran

[![Screenshot](https://raw.githubusercontent.com/gotify/server/master/ui.png)](https://github.com/gotify/server)

## Configuration

Pour configurer Gotify :
> Edit config.yml file via SSH.

## Documentation

 * Documentation officielle: [ici](https://gotify.net/docs/index)

#### Support multi-utilisateurs

Pas de support de LDAP

## Limitations

 * necessite un domaine dédié par exemple gotify.domain.tld.

 * Pas de support de LDAP (non implémenté upstream)

## Links

## Links

 * Signaler un bug: https://github.com/YunoHost-Apps/gotify_ynh/issues
 * Site de l'application: https://gotify.net/
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/gotify_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/gotify_ynh/tree/testing --debug
ou
sudo yunohost app upgrade gotify -u https://github.com/YunoHost-Apps/gotify_ynh/tree/testing --debug
```
