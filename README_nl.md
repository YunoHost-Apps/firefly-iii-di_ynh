<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Firefly III Importer voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/firefly-iii-di)](https://ci-apps.yunohost.org/ci/apps/firefly-iii-di/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/firefly-iii-di)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/firefly-iii-di)

[![Firefly III Importer met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii-di)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Firefly III Importer snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Firefly III Data Importer is the nr. 1 tool to import data into [Firefly III](https://www.firefly-iii.org/). This tools helps you import transactions from files or bank APIs into your
Firefly-III server. Please follow the documentation at https://docs.firefly-iii.org/data-importer/.

If your Firefly-III server is installed as a YunoHost app, please note:

- It should be accessible to all visitors (using its internal user management instead of YunoHosts') for the Data Importer to communicate with it.

- When configuring the Data Importer, use the public Firefly-III domain and path, not *localhost*, even if both services are on the same machine.


**Geleverde versie:** 1.6.1~ynh1

## Schermafdrukken

![Schermafdrukken van Firefly III Importer](./doc/screenshots/firefly-iii-di-start-screen.png)

## Documentatie en bronnen

- Officiele website van de app: <https://docs.firefly-iii.org/data-importer/>
- Officiele beheerdersdocumentatie: <https://docs.firefly-iii.org/data-importer/how-to-use/>
- Upstream app codedepot: <https://github.com/firefly-iii/data-importer>
- YunoHost-store: <https://apps.yunohost.org/app/firefly-iii-di>
- Meld een bug: <https://github.com/YunoHost-Apps/firefly-iii-di_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
of
sudo yunohost app upgrade firefly-iii-di -u https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
