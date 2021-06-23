# TP Cybersécurité 

Ce projet a été réalisé dans le cadre de notre troisième année de formation en développement et conception d'applications.

**Les consignes du projet sont les suivantes :**

Création d'une application web avec authentification

* Création de la partie front 
    * Reproduire du mieux possible une interface de connexion exsitante (comme du phishing)
    * Langage de programmation libre

* Utilisation API (google, facebook, twitter ...)
    * Intégration du bouton de login avec (si possible) récupération des données utilisateurs

* OU Création de la partie back
    * Pouvoir se connecter à l'application à l'aide d'un login et d'un mot de passe
    * Création d'un token de session correspondant à la personne authentifiée
    * Génération du token de session grâce au protocole Oauth2
    * Langage de programmation libre

* La création d'une petite base de données peut être nécessaire
    * Pour contenir le login et le mot de passe à vérifier

**Les objectifs à remplir :**

Le projet est réalisé en symfony, nos objectifs sont :
* Création d'une page web ressemblant à l'authentification google
* Connexion avec un login / mot de passe
* Génération du token de session grâce au protocole Oauth2

---

## Contributeurs

Les **membres constituant le groupe** sont les suivants :

- Simon Bourrasseau ([simonbourrasseau](https://github.com/simonbourrasseau))
- Axelle Guinaudeau ([Theia01](https://github.com/Theia01))

---

## Utiliser l'application en local


### Dépendances requises :

Avant toute chose, certaines installations sont **requises** pour pouvoir utiliser ce projet :

- [PHP](https://www.php.net/downloads.php) (version 7 ou supérieure),
- [Composer](https://getcomposer.org/download/).
- [Symfony](https://symfony.com/download)

### Mettre en place le projet

Il vous faut ensuite **cloner le projet :**
```sh
git clone git@github.com:simonbourrasseau/CA_cybersecu_TP.git
```

Une fois cela fait, rentrez dans le fichier créé et exécutez les commandes suivantes :
```sh
composer install
```

Enfin, **lancez l'application** en utilisant la commande :
```sh
symfony server:start 
```

Puis vous devrez vous rendre sur [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## Plan du site

Les différentes pages:
- [login](http://127.0.0.1:8000/login)