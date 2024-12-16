<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Firefly III Importer pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/firefly-iii-di.svg)](https://ci-apps.yunohost.org/ci/apps/firefly-iii-di/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/firefly-iii-di.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/firefly-iii-di.maintain.svg)

[![Installer Firefly III Importer avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii-di)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Firefly III Importer rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Firefly III Data Importer is the nr. 1 tool to import data into [Firefly III](https://www.firefly-iii.org/). This tools helps you import transactions from files or bank APIs into your
Firefly-III server. Please follow the documentation at https://docs.firefly-iii.org/data-importer/.

If your Firefly-III server is installed as a YunoHost app, please note:

- It should be accessible to all visitors (using its internal user management instead of YunoHosts') for the Data Importer to communicate with it.

- When configuring the Data Importer, use the public Firefly-III domain and path, not *localhost*, even if both services are on the same machine.


**Version incluse :** 1.5.7~ynh1

## Captures d’écran

![Capture d’écran de Firefly III Importer](./doc/screenshots/firefly-iii-di-start-screen.png)

## Documentations et ressources

- Site officiel de l’app : <https://docs.firefly-iii.org/data-importer/>
- Documentation officielle de l’admin : <https://docs.firefly-iii.org/data-importer/how-to-use/>
- Dépôt de code officiel de l’app : <https://github.com/firefly-iii/data-importer>
- YunoHost Store : <https://apps.yunohost.org/app/firefly-iii-di>
- Signaler un bug : <https://github.com/YunoHost-Apps/firefly-iii-di_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
ou
sudo yunohost app upgrade firefly-iii-di -u https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
