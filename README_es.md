<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Firefly III Importer para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/firefly-iii-di)](https://ci-apps.yunohost.org/ci/apps/firefly-iii-di/)
![Estado funcional](https://apps.yunohost.org/badge/state/firefly-iii-di)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/firefly-iii-di)

[![Instalar Firefly III Importer con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii-di)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarFirefly III Importer rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Firefly III Data Importer is the nr. 1 tool to import data into [Firefly III](https://www.firefly-iii.org/). This tools helps you import transactions from files or bank APIs into your
Firefly-III server. Please follow the documentation at https://docs.firefly-iii.org/data-importer/.

If your Firefly-III server is installed as a YunoHost app, please note:

- It should be accessible to all visitors (using its internal user management instead of YunoHosts') for the Data Importer to communicate with it.

- When configuring the Data Importer, use the public Firefly-III domain and path, not *localhost*, even if both services are on the same machine.


**Versión actual:** 1.5.7~ynh1

## Capturas

![Captura de Firefly III Importer](./doc/screenshots/firefly-iii-di-start-screen.png)

## Documentaciones y recursos

- Sitio web oficial: <https://docs.firefly-iii.org/data-importer/>
- Documentación administrador oficial: <https://docs.firefly-iii.org/data-importer/how-to-use/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/firefly-iii/data-importer>
- Catálogo YunoHost: <https://apps.yunohost.org/app/firefly-iii-di>
- Reportar un error: <https://github.com/YunoHost-Apps/firefly-iii-di_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
o
sudo yunohost app upgrade firefly-iii-di -u https://github.com/YunoHost-Apps/firefly-iii-di_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
