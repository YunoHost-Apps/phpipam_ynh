<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# phpIPAM для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/phpipam.svg)](https://ci-apps.yunohost.org/ci/apps/phpipam/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/phpipam.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/phpipam.maintain.svg)

[![Установите phpIPAM с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpipam)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить phpIPAM быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

phpIPAM is an open-source web IP address management application. Its goal is to provide light and simple IP address management application. It is ajax-based using jQuery libraries, it uses php scripts and javascript and some HTML5/CSS3 features, so some modern browser is preferred to be able to display javascript quickly and correctly.

**Поставляемая версия:** 1.7.0~ynh1

**Демо-версия:** <http://demo.phpipam.net>

## Снимки экрана

![Снимок экрана phpIPAM](./doc/screenshots/dashboard.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://phpipam.net>
- Официальная документация администратора: <https://phpipam.net/documents/>
- Репозиторий кода главной ветки приложения: <https://github.com/phpipam/phpipam>
- Магазин YunoHost: <https://apps.yunohost.org/app/phpipam>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/phpipam_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
или
sudo yunohost app upgrade phpipam -u https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
