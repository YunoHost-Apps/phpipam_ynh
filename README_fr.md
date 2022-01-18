# phpIPAM pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/phpipam.svg)](https://dash.yunohost.org/appci/app/phpipam) ![](https://ci-apps.yunohost.org/ci/badges/phpipam.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/phpipam.maintain.svg)  
[![Installer phpIPAM avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpipam)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer phpIPAM rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Application web de gestion d'adresses IP

**Version incluse :** 1.4.5~ynh1

**Démo :** http://demo.phpipam.net

## Captures d'écran

![](./doc/screenshots/.DS_Store)
![](./doc/screenshots/dashboard.png)

## Documentations et ressources

* Site officiel de l'app : https://phpipam.net
* Documentation officielle de l'admin : https://phpipam.net/documents/
* Dépôt de code officiel de l'app : https://github.com/phpipam/phpipam
* Documentation YunoHost pour cette app : https://yunohost.org/app_phpipam
* Signaler un bug : https://github.com/YunoHost-Apps/phpipam_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
ou
sudo yunohost app upgrade phpipam -u https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps