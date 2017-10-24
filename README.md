## Site du club robotique de l'ENSTA Bretagne

Ce site utilise le thème Lanyon de Jekyll. 

N'hésitez pas à proposer des ajouts ou modifications.

TODO : Un moyen simple de faire une arborescence dans la sidebar

### Origine du projet
Pour la petite histoire, ce site est issu d'un besoin de rassembler des informations qui se perdent promo après promo. L'objectif était donc de fournir un espace aux étudiants pour qu'ils puissent ajouter les liens intéressants qu'il ont dénichés en ralation avec la robotique ou de mettre le lien vers leur propre projet.

Initialement il a pris la forme d'un repository appelé `liens_robotique` mais il s'est rapidement transformé en wiki github puis en site github pour atteindre sa forme actuelle.

### Consigne d'utilisation
##### Ajout de post sur le blog
Les post sont là pour informer d'évenements, donc ne les utilisez pas pour y mettre des informations à conserver. Par contre les utiliser pour notifier d'un ajout dans les docs ou faire part d'évenements, ça c'est bien.

Pour ajouter un post il faut ajouter un fichier dans le dossier `_posts` avec un nom formaté comme ceci : `annee-mois-jour-nom-avec-des-tirets-comme-espaces.md`. Le tout premier post peut facilement servir d'exemple. Puis ajoutez le header nécessaire pour que Jekyll reconnaisse qu'il s'agit d'un post : 
```
---
layout: post
title: Titre dont j'ai envie
---
```

##### Ajout de pages de documentations
A l'heure actuelle (24/10/2017) il n'y a pas d'arborescence dans la sidebar, du coup ne créez une nouvelle page que si vous abordez un thème vraiment nouveau, sinon ajoutez vos informations à une page existante.

Pour créer une page il suffit de créer un fichier en `.md` dans le dossiers docs et de lui donner un titre en header 1 en haut de la page. Par exemple : `# Titre`

Il est aussi possible de spécifier le titre comme ci-dessous
```
---
layout: page
title: Titre dont j'ai envie
---
```
