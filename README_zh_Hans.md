<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Bloat

[![集成程度](https://dash.yunohost.org/integration/bloat.svg)](https://ci-apps.yunohost.org/ci/apps/bloat/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/bloat.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/bloat.maintain.svg)

[![使用 YunoHost 安装 Bloat](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bloat)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Bloat。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

bloat - A web client for Mastadon Network[1]

Features:

- Does not require JavaScript to display text, images, audio and videos.

[1] https://pleroma.social


**分发版本：** 1.0~ynh1

## 截图

![Bloat 的截图](./doc/screenshots/example.png)

## 文档与资源

- 官方管理文档： <https://git.freesoftwareextremist.com/bloat/tree/README>
- 上游应用代码库： <https://git.freesoftwareextremist.com/bloat/>
- YunoHost 商店： <https://apps.yunohost.org/app/bloat>
- 报告 bug： <https://github.com/YunoHost-Apps/bloat_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/bloat_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/bloat_ynh/tree/testing --debug
或
sudo yunohost app upgrade bloat -u https://github.com/YunoHost-Apps/bloat_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
