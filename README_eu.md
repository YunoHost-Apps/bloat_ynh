<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Bloat YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/bloat.svg)](https://ci-apps.yunohost.org/ci/apps/bloat/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/bloat.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/bloat.maintain.svg)

[![Instalatu Bloat YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bloat)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Bloat YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

bloat - A web client for Mastadon Network[1]

Features:

- Does not require JavaScript to display text, images, audio and videos.

[1] https://pleroma.social


**Paketatutako bertsioa:** 1.0~ynh1

## Pantaila-argazkiak

![Bloat(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://git.freesoftwareextremist.com/bloat/tree/README>
- Jatorrizko aplikazioaren kode-gordailua: <https://git.freesoftwareextremist.com/bloat/>
- YunoHost Denda: <https://apps.yunohost.org/app/bloat>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/bloat_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/bloat_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/bloat_ynh/tree/testing --debug
edo
sudo yunohost app upgrade bloat -u https://github.com/YunoHost-Apps/bloat_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
