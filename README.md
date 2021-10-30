
# Blog Symfony

## Comment utiliser le projet

Vérifier que vous possédez les pré-requis

Pour Symfony : https://symfony.com/download 

Composer : https://getcomposer.org/download/

Pour le serveur un wamp/mamp/lamp suffira (mamp pour macos : https://www.mamp.info/en/downloads/ par exemple )

Faire un git clone de ce projet, prendre le terminal pour se rendre dans le dossier du projet télécharger et entrer la commande `composer install` puis `composer require --dev symfony/dotenv` pour générer le fichier .env (que vous réglerez ensuite avec votre nom d'utilisateur et mot de passe pour la base de données)

## Description :
Ce projet sert à appréhender Symfony, pour le moment il possède des routes, des fixtures (fausses données à envoyer directement dans la base de données afin d'avoir un visuel sur la page article), un ajout et edition d'article et une vue pour afficher les différents articles selons leur ID

A faire : 

Système d'enregistrement de compte
Système de vérification de compte via e-mail
Système de login/logout
Système de rôle (administrateur, modérateur, utilisateur)