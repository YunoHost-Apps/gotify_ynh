<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Gotify YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/gotify.svg)](https://ci-apps.yunohost.org/ci/apps/gotify/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/gotify.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/gotify.maintain.svg)

[![Instalatu Gotify YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gotify)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Gotify YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Gotify is a simple server for sending and receiving messages in real-time per web socket.


**Paketatutako bertsioa:** 2.6.0~ynh1

## Pantaila-argazkiak

![Gotify(r)en pantaila-argazkia](./doc/screenshots/ui.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <http://gotify.net>
- Administratzaileen dokumentazio ofiziala: <https://gotify.net/docs/index>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/gotify/server>
- YunoHost Denda: <https://apps.yunohost.org/app/gotify>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/gotify_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/gotify_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gotify_ynh/tree/testing --debug
edo
sudo yunohost app upgrade gotify -u https://github.com/YunoHost-Apps/gotify_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
