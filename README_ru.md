<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Firefly III Importer для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/firefly-iii-di.svg)](https://ci-apps.yunohost.org/ci/apps/firefly-iii-di/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/firefly-iii-di.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/firefly-iii-di.maintain.svg)

[![Установите Firefly III Importer с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii-di)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Firefly III Importer быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Firefly III Data Importer is the nr. 1 tool to import data into [Firefly III](https://www.firefly-iii.org/). This tools helps you import transactions from files or bank APIs into your
Firefly-III server. Please follow the documentation at https://docs.firefly-iii.org/data-importer/.

If your Firefly-III server is installed as a YunoHost app, please note:

- It should be accessible to all visitors (using its internal user management instead of YunoHosts') for the Data Importer to communicate with it.

- When configuring the Data Importer, use the public Firefly-III domain and path, not *localhost*, even if both services are on the same machine.


**Поставляемая версия:** 1.5.7~ynh1

## Снимки экрана

![Снимок экрана Firefly III Importer](./doc/screenshots/firefly-iii-di-start-screen.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://docs.firefly-iii.org/data-importer/>
- Официальная документация администратора: <https://docs.firefly-iii.org/data-importer/how-to-use/>
- Репозиторий кода главной ветки приложения: <https://github.com/firefly-iii/data-importer>
- Магазин YunoHost: <https://apps.yunohost.org/app/firefly-iii-di>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/firefly-iii-di_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
или
sudo yunohost app upgrade firefly-iii-di -u https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
