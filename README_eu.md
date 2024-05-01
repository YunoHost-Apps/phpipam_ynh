<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# phpIPAM YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/phpipam.svg)](https://dash.yunohost.org/appci/app/phpipam) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/phpipam.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/phpipam.maintain.svg)

[![Instalatu phpIPAM YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpipam)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek phpIPAM YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

phpIPAM is an open-source web IP address management application. Its goal is to provide light and simple IP address management application. It is ajax-based using jQuery libraries, it uses php scripts and javascript and some HTML5/CSS3 features, so some modern browser is preferred to be able to display javascript quickly and correctly.

**Paketatutako bertsioa:** 1.19.8~ynh2

**Demoa:** <http://demo.phpipam.net>

## Pantaila-argazkiak

![phpIPAM(r)en pantaila-argazkia](./doc/screenshots/dashboard.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://phpipam.net>
- Administratzaileen dokumentazio ofiziala: <https://phpipam.net/documents/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/phpipam/phpipam>
- YunoHost Denda: <https://apps.yunohost.org/app/phpipam>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/phpipam_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
edo
sudo yunohost app upgrade phpipam -u https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
