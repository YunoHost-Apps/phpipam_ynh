<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# phpIPAM pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/phpipam.svg)](https://dash.yunohost.org/appci/app/phpipam) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/phpipam.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/phpipam.maintain.svg)

[![Installer phpIPAM avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpipam)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer phpIPAM rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

phpIPAM est une application open source de gestion d'adresses IP Web. Son objectif est de fournir une application de gestion d'adresses IP légère et simple. Il est basé sur ajax utilisant les bibliothèques jQuery, il utilise des scripts php et javascript ainsi que certaines fonctionnalités HTML5/CSS3, il est donc préférable d'utiliser certains navigateurs modernes pour pouvoir afficher javascript rapidement et correctement.


**Version incluse :** 1.19.8~ynh2

**Démo :** <http://demo.phpipam.net>

## Captures d’écran

![Capture d’écran de phpIPAM](./doc/screenshots/dashboard.png)

## Documentations et ressources

- Site officiel de l’app : <https://phpipam.net>
- Documentation officielle de l’admin : <https://phpipam.net/documents/>
- Dépôt de code officiel de l’app : <https://github.com/phpipam/phpipam>
- YunoHost Store : <https://apps.yunohost.org/app/phpipam>
- Signaler un bug : <https://github.com/YunoHost-Apps/phpipam_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
ou
sudo yunohost app upgrade phpipam -u https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
