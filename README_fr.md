<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Bloat pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/bloat.svg)](https://ci-apps.yunohost.org/ci/apps/bloat/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/bloat.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/bloat.maintain.svg)

[![Installer Bloat avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bloat)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Bloat rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

bloat - Un client web pour le réseau Mastadon[1]

Caractéristiques :

- Ne nécessite pas de JavaScript pour afficher du texte, des images, du son et des vidéos.

[1] https://pleroma.social


**Version incluse :** 1.0~ynh1

## Captures d’écran

![Capture d’écran de Bloat](./doc/screenshots/example.png)

## Documentations et ressources

- Documentation officielle de l’admin : <https://git.freesoftwareextremist.com/bloat/tree/README>
- Dépôt de code officiel de l’app : <https://git.freesoftwareextremist.com/bloat/>
- YunoHost Store : <https://apps.yunohost.org/app/bloat>
- Signaler un bug : <https://github.com/YunoHost-Apps/bloat_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/bloat_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/bloat_ynh/tree/testing --debug
ou
sudo yunohost app upgrade bloat -u https://github.com/YunoHost-Apps/bloat_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
