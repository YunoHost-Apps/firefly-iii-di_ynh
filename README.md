<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Firefly III Importer for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/firefly-iii-di)](https://ci-apps.yunohost.org/ci/apps/firefly-iii-di/)
![Working status](https://apps.yunohost.org/badge/state/firefly-iii-di)
![Maintenance status](https://apps.yunohost.org/badge/maintained/firefly-iii-di)

[![Install Firefly III Importer with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii-di)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Firefly III Importer quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Firefly III Data Importer is the nr. 1 tool to import data into [Firefly III](https://www.firefly-iii.org/). This tools helps you import transactions from files or bank APIs into your
Firefly-III server. Please follow the documentation at https://docs.firefly-iii.org/data-importer/.

If your Firefly-III server is installed as a YunoHost app, please note:

- It should be accessible to all visitors (using its internal user management instead of YunoHosts') for the Data Importer to communicate with it.

- When configuring the Data Importer, use the public Firefly-III domain and path, not *localhost*, even if both services are on the same machine.


**Shipped version:** 1.6.1~ynh1

## Screenshots

![Screenshot of Firefly III Importer](./doc/screenshots/firefly-iii-di-start-screen.png)

## Documentation and resources

- Official app website: <https://docs.firefly-iii.org/data-importer/>
- Official admin documentation: <https://docs.firefly-iii.org/data-importer/how-to-use/>
- Upstream app code repository: <https://github.com/firefly-iii/data-importer>
- YunoHost Store: <https://apps.yunohost.org/app/firefly-iii-di>
- Report a bug: <https://github.com/YunoHost-Apps/firefly-iii-di_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
or
sudo yunohost app upgrade firefly-iii-di -u https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
