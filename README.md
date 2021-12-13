[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a64ba1f5c7564d8492f91701c273976c)](https://www.codacy.com/app/Link1986/projet5?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Link1986/projet5&amp;utm_campaign=Badge_Grade)

OC - Projet 5
Création d'un gestionnaire de liste de tâches avec Symfony

Installation
1. Récupérer le code

Vous avez deux solutions pour le faire :

Via Git, en clonant ce dépôt ;

Via le téléchargement du code source en une archive ZIP

2. Télécharger les vendors

Pour cela on utilise composer:

1/php composer.phar install

2/Composer update

3. Créez la base de données

Si la base de données n'existe pas déjà, créez-la :

php bin/console doctrine:database:create

Puis créez les tables correspondantes au schéma Doctrine :

php bin/console doctrine:schema:update --dump-sql

php bin/console doctrine:schema:update --force

4. Publiez les assets

Publiez les assets dans le répertoire web :

php bin/console assets:install web![gesty](https://user-images.githubusercontent.com/27373255/145893788-f84cb1cf-492d-40cc-a805-b43bd404b909.png)
