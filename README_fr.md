<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Firefly III Importer pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/firefly-iii-di)](https://ci-apps.yunohost.org/ci/apps/firefly-iii-di/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/firefly-iii-di)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/firefly-iii-di)

[![Installer Firefly III Importer avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii-di)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Firefly III Importer rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Firefly III Data Importer est l'outil n°1 pour importer des données dans [Firefly III](https://www.firefly-iii.org/). Cet outil vous aide à importer des transactions à partir de fichiers ou d'API bancaires dans votre
serveur Firefly-III. Veuillez suivre la documentation sur https://docs.firefly-iii.org/data-importer/.

Si votre serveur Firefly-III est installé en tant qu'application YunoHost, veuillez noter :

- Il doit être accessible à tous les visiteurs (en utilisant sa gestion interne des utilisateurs au lieu de celle de YunoHost) pour que l'importateur de données puisse communiquer avec lui.

- Lors de la configuration de l'importateur de données, utilisez le domaine et le chemin publics de Firefly-III, et non *localhost*, même si les deux services se trouvent sur la même machine.

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
