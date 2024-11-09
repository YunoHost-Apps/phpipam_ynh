<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# phpIPAM untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/phpipam.svg)](https://ci-apps.yunohost.org/ci/apps/phpipam/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/phpipam.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/phpipam.maintain.svg)

[![Pasang phpIPAM dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpipam)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang phpIPAM secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

phpIPAM is an open-source web IP address management application. Its goal is to provide light and simple IP address management application. It is ajax-based using jQuery libraries, it uses php scripts and javascript and some HTML5/CSS3 features, so some modern browser is preferred to be able to display javascript quickly and correctly.

**Versi terkirim:** 1.19.008~ynh1

**Demo:** <http://demo.phpipam.net>

## Tangkapan Layar

![Tangkapan Layar pada phpIPAM](./doc/screenshots/dashboard.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://phpipam.net>
- Dokumentasi admin resmi: <https://phpipam.net/documents/>
- Depot kode aplikasi hulu: <https://github.com/phpipam/phpipam>
- Gudang YunoHost: <https://apps.yunohost.org/app/phpipam>
- Laporkan bug: <https://github.com/YunoHost-Apps/phpipam_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
atau
sudo yunohost app upgrade phpipam -u https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
