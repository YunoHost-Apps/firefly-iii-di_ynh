<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Firefly III Importer dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/firefly-iii-di)](https://ci-apps.yunohost.org/ci/apps/firefly-iii-di/)
![Status działania](https://apps.yunohost.org/badge/state/firefly-iii-di)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/firefly-iii-di)

[![Zainstaluj Firefly III Importer z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii-di)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Firefly III Importer na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Firefly III Data Importer is the nr. 1 tool to import data into [Firefly III](https://www.firefly-iii.org/). This tools helps you import transactions from files or bank APIs into your
Firefly-III server. Please follow the documentation at https://docs.firefly-iii.org/data-importer/.

If your Firefly-III server is installed as a YunoHost app, please note:

- It should be accessible to all visitors (using its internal user management instead of YunoHosts') for the Data Importer to communicate with it.

- When configuring the Data Importer, use the public Firefly-III domain and path, not *localhost*, even if both services are on the same machine.


**Dostarczona wersja:** 1.6.0~ynh1

## Zrzuty ekranu

![Zrzut ekranu z Firefly III Importer](./doc/screenshots/firefly-iii-di-start-screen.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://docs.firefly-iii.org/data-importer/>
- Oficjalna dokumentacja dla administratora: <https://docs.firefly-iii.org/data-importer/how-to-use/>
- Repozytorium z kodem źródłowym: <https://github.com/firefly-iii/data-importer>
- Sklep YunoHost: <https://apps.yunohost.org/app/firefly-iii-di>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/firefly-iii-di_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
lub
sudo yunohost app upgrade firefly-iii-di -u https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
