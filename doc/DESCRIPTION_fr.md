Firefly III Data Importer est l'outil n°1 pour importer des données dans [Firefly III](https://www.firefly-iii.org/). Cet outil vous aide à importer des transactions à partir de fichiers ou d'API bancaires dans votre
serveur Firefly-III. Veuillez suivre la documentation sur https://docs.firefly-iii.org/data-importer/.

Si votre serveur Firefly-III est installé en tant qu'application YunoHost, veuillez noter :

- Il doit être accessible à tous les visiteurs (en utilisant sa gestion interne des utilisateurs au lieu de celle de YunoHost) pour que l'importateur de données puisse communiquer avec lui.

- Lors de la configuration de l'importateur de données, utilisez le domaine et le chemin publics de Firefly-III, et non *localhost*, même si les deux services se trouvent sur la même machine.