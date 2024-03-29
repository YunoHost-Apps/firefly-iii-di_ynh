<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Firefly III Importer per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/firefly-iii-di.svg)](https://dash.yunohost.org/appci/app/firefly-iii-di) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/firefly-iii-di.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/firefly-iii-di.maintain.svg)

[![Installa Firefly III Importer con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii-di)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Firefly III Importer su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Firefly III Data Importer is the nr. 1 tool to import data into [Firefly III](https://www.firefly-iii.org/). This tools helps you import transactions from files or bank APIs into your
Firefly-III server. Please follow the documentation at https://docs.firefly-iii.org/data-importer/.

If your Firefly-III server is installed as a YunoHost app, please note:

- It should be accessible to all visitors (using its internal user management instead of YunoHosts') for the Data Importer to communicate with it.

- When configuring the Data Importer, use the public Firefly-III domain and path, not *localhost*, even if both services are on the same machine.


**Versione pubblicata:** 1.2.2~ynh1

## Screenshot

![Screenshot di Firefly III Importer](./doc/screenshots/firefly-iii-di-start-screen.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://docs.firefly-iii.org/data-importer/>
- Documentazione ufficiale per gli amministratori: <https://docs.firefly-iii.org/data-importer/how-to-use/>
- Repository upstream del codice dell’app: <https://github.com/firefly-iii/data-importer>
- Store di YunoHost: <https://apps.yunohost.org/app/firefly-iii-di>
- Segnala un problema: <https://github.com/YunoHost-Apps/firefly-iii-di_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
o
sudo yunohost app upgrade firefly-iii-di -u https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
