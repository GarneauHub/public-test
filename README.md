# GarneauHub — site de test

Version de **test** du frontend de GarneauHub (portail d'examens et sites de cours du Cégep Garneau), publiée sur GitHub Pages :

**https://garneauhub.github.io/public-test/**

> Ce dépôt ne contient **que le site construit** (HTML, CSS, JS) : aucun code source, aucun secret.
> Le code source est dans le dépôt privé `GarneauHub/GarneauHub`.

## À quoi sert ce site

- Tester les nouveautés **avant** qu'elles arrivent sur le vrai site.
- Présenter l'application sans toucher aux vraies données.

Le vrai site (production) est sur https://techinfo.cegepgarneau.ca/hub/

## Choisir le serveur : TEST ou PRODUCTION

Un sélecteur en haut de page permet de choisir le serveur :

| Serveur | Données | Ce qu'on peut faire |
| --- | --- | --- |
| **TEST** (par défaut) | données de démonstration | tout : créer, modifier, supprimer, passer des examens |
| **PRODUCTION** | vraies données | **lecture seule** : consulter seulement. Les créations, modifications et suppressions sont refusées. |

Changer de serveur déconnecte : il faut se reconnecter.

## Comptes

Les comptes de démonstration du serveur **TEST** sont fournis par l'équipe sur demande.
Ne jamais utiliser ce site pour des données personnelles réelles.

## Mise à jour

Le site est **publié automatiquement** à chaque changement du frontend dans le dépôt source (GitHub Actions).
Il ne faut **pas modifier** la branche `gh-pages` à la main : elle est remplacée à chaque publication.

- La nouvelle version apparaît environ une minute après la publication.
- Si la page semble ancienne : **Ctrl+F5**.

## Signaler un problème

Ouvrez une issue dans le dépôt source `GarneauHub/GarneauHub`, en précisant :
- le serveur choisi (TEST ou PRODUCTION) ;
- la page (adresse) ;
- ce que vous avez fait, et ce qui s'est passé.
