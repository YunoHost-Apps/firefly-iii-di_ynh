<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Firefly III Importer YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/firefly-iii-di)](https://ci-apps.yunohost.org/ci/apps/firefly-iii-di/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/firefly-iii-di)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/firefly-iii-di)

[![Instalatu Firefly III Importer YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii-di)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Firefly III Importer YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Firefly III Data Importer is the nr. 1 tool to import data into [Firefly III](https://www.firefly-iii.org/). This tools helps you import transactions from files or bank APIs into your
Firefly-III server. Please follow the documentation at https://docs.firefly-iii.org/data-importer/.

If your Firefly-III server is installed as a YunoHost app, please note:

- It should be accessible to all visitors (using its internal user management instead of YunoHosts') for the Data Importer to communicate with it.

- When configuring the Data Importer, use the public Firefly-III domain and path, not *localhost*, even if both services are on the same machine.


**Paketatutako bertsioa:** 1.6.1~ynh1

## Pantaila-argazkiak

![Firefly III Importer(r)en pantaila-argazkia](./doc/screenshots/firefly-iii-di-start-screen.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://docs.firefly-iii.org/data-importer/>
- Administratzaileen dokumentazio ofiziala: <https://docs.firefly-iii.org/data-importer/how-to-use/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/firefly-iii/data-importer>
- YunoHost Denda: <https://apps.yunohost.org/app/firefly-iii-di>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/firefly-iii-di_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
edo
sudo yunohost app upgrade firefly-iii-di -u https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
