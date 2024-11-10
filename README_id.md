<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Firefly III Importer untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/firefly-iii-di.svg)](https://ci-apps.yunohost.org/ci/apps/firefly-iii-di/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/firefly-iii-di.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/firefly-iii-di.maintain.svg)

[![Pasang Firefly III Importer dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii-di)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Firefly III Importer secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Firefly III Data Importer is the nr. 1 tool to import data into [Firefly III](https://www.firefly-iii.org/). This tools helps you import transactions from files or bank APIs into your
Firefly-III server. Please follow the documentation at https://docs.firefly-iii.org/data-importer/.

If your Firefly-III server is installed as a YunoHost app, please note:

- It should be accessible to all visitors (using its internal user management instead of YunoHosts') for the Data Importer to communicate with it.

- When configuring the Data Importer, use the public Firefly-III domain and path, not *localhost*, even if both services are on the same machine.


**Versi terkirim:** 1.5.7~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Firefly III Importer](./doc/screenshots/firefly-iii-di-start-screen.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://docs.firefly-iii.org/data-importer/>
- Dokumentasi admin resmi: <https://docs.firefly-iii.org/data-importer/how-to-use/>
- Depot kode aplikasi hulu: <https://github.com/firefly-iii/data-importer>
- Gudang YunoHost: <https://apps.yunohost.org/app/firefly-iii-di>
- Laporkan bug: <https://github.com/YunoHost-Apps/firefly-iii-di_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
atau
sudo yunohost app upgrade firefly-iii-di -u https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
