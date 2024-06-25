<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Firefly III Importer

[![集成程度](https://dash.yunohost.org/integration/firefly-iii-di.svg)](https://dash.yunohost.org/appci/app/firefly-iii-di) ![工作状态](https://ci-apps.yunohost.org/ci/badges/firefly-iii-di.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/firefly-iii-di.maintain.svg)

[![使用 YunoHost 安装 Firefly III Importer](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii-di)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Firefly III Importer。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Firefly III Data Importer is the nr. 1 tool to import data into [Firefly III](https://www.firefly-iii.org/). This tools helps you import transactions from files or bank APIs into your
Firefly-III server. Please follow the documentation at https://docs.firefly-iii.org/data-importer/.

If your Firefly-III server is installed as a YunoHost app, please note:

- It should be accessible to all visitors (using its internal user management instead of YunoHosts') for the Data Importer to communicate with it.

- When configuring the Data Importer, use the public Firefly-III domain and path, not *localhost*, even if both services are on the same machine.


**分发版本：** 1.5.2~ynh1

## 截图

![Firefly III Importer 的截图](./doc/screenshots/firefly-iii-di-start-screen.png)

## 文档与资源

- 官方应用网站： <https://docs.firefly-iii.org/data-importer/>
- 官方管理文档： <https://docs.firefly-iii.org/data-importer/how-to-use/>
- 上游应用代码库： <https://github.com/firefly-iii/data-importer>
- YunoHost 商店： <https://apps.yunohost.org/app/firefly-iii-di>
- 报告 bug： <https://github.com/YunoHost-Apps/firefly-iii-di_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
或
sudo yunohost app upgrade firefly-iii-di -u https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
