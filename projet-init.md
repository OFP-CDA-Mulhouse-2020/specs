# Préparation du projet

*19 novembre 2020* : Finalisation de Docker, Découverte de symfony et des outils mis a disposition.
  
  - Terminer installation des différents conteneurs Docker et tout faire fonctionner.
  - Mettre en place le projet Symfony et **ses** base de données
  - Créer une entité "bidon" dans Symfony 
  - Coder quelques tests unitaires sur celle-ci 
  - Découvrir les environnements symfony : DEV / TEST / PROD
      - avoir une base de developpement local : environnement DEV
      - avoir une base de test local : environnement TEST
      - avoir une base de test distante pour les tests sous github : environnement TEST
  - Pré-remplir une base de test (separée de votre base de dev) a l'aide de fixtures 
  - Mettre en place une github action qui lance les tests unitaires

*17 novembre 2020*

- Dockeriser l'application avec les conteneurs suivants:
  - traefik
  - php7.4-apache avec XDebug
  - mysql
  - composer
  - phpmyadmin
  - mailhog

*16 novembre 2020*

- Installer l'executable symfony
- Installer le framework dans le projet
- Installer les outils de qualité : phpCS / phpstan / phpunit / phpunit-watcher dans le projet (pour phpunit vous referer a la documentation symfony)
- Faire l'import du projet de base dans github

