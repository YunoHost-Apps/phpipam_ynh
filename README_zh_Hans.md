<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 phpIPAM

[![集成程度](https://dash.yunohost.org/integration/phpipam.svg)](https://ci-apps.yunohost.org/ci/apps/phpipam/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/phpipam.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/phpipam.maintain.svg)

[![使用 YunoHost 安装 phpIPAM](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpipam)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 phpIPAM。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

phpIPAM is an open-source web IP address management application. Its goal is to provide light and simple IP address management application. It is ajax-based using jQuery libraries, it uses php scripts and javascript and some HTML5/CSS3 features, so some modern browser is preferred to be able to display javascript quickly and correctly.

**分发版本：** 1.19.008~ynh1

**演示：** <http://demo.phpipam.net>

## 截图

![phpIPAM 的截图](./doc/screenshots/dashboard.png)

## 文档与资源

- 官方应用网站： <https://phpipam.net>
- 官方管理文档： <https://phpipam.net/documents/>
- 上游应用代码库： <https://github.com/phpipam/phpipam>
- YunoHost 商店： <https://apps.yunohost.org/app/phpipam>
- 报告 bug： <https://github.com/YunoHost-Apps/phpipam_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
或
sudo yunohost app upgrade phpipam -u https://github.com/YunoHost-Apps/phpipam_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
