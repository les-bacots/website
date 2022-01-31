---
title: "Salle de rédaction en ligne"
description: "Salle de rédaction en ligne"
lead: ""
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  comment_participer:
    parent: "comment_contribuer"
weight: 40
toc: true
---

[GitHub](https://fr.github.com/) est un outil de gestion de code source, très largement utilisé pour les projets opensource collaboratifs.

C'est un outil qui permet à des millions de développeurs dans le monde de écrire et de revoir des milliards de lignes de codes.

Toutes les demandes et les actions sont tracées dans des questions et des demandes de changements.
Une fois que les changements sont revus et approuvés, ils sont publiés dans les documents de référence.

Pour la gestion des contenus du site d'information *lesbacots.org* nous proposons d'utiliser l'outil GitHub d'une façon simple et efficace.

L'espace `lesbacots.org` sur GitHub accessible à l'adresse [github.lesbacots.org](https://github.com/les-bacots/les-bacots.github.io) est donc la salle de rédaction du site d'information où sont rédigées puis ensuite revues et validées les publications qui sont mises en ligne sur le site internet public [lesbacots.org](https://www.lesbacots.org/). 


Le seul pré-requis pour faire une contribution sur lesbacots.org avec *GitHub* est la nécessité d'avoir un compte utilisateur GitHub ainsi qu'un profil publié sur lesbacots.org pour obtenir les droits de contribution. Cette inscription peut-être réalisée à cette url [https://github.com/signup](https://github.com/signup) et votre profil peut-être renseigné via ce [formulaire](https://www.lesbacots.org/devenir_membre/).

| :memo: [documentation pour l'inscription](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account) |
|---------------------------------------------------------------------------------------------------------------------------------------------|

## Faire une contribution

[GitHub](https://fr.github.com/) fonctionne selon le principe de *contributions*, *relectures* et *approbations*.

### Cliquer le lien *Editer cette page sur GitHub*

Sur le site un lien est disponible en bas de chaque page pour son édition en ligne.

![Lien pour l'édition](images/editer-sur-github.png "Lien pour l'édition")

Cliquer ce lien ouvre la page du fichier source à éditer sur le site *Github*.

![Fichier source de la page](images/source-de-la-page-sur-github.png "fichier source de la page")

### Editer le contenu de la page

Pour éditer le contenu d'une page il faut cliquer sur l'icône *stylo* en haut à droite du fichier.

![Icône stylo pour éditer](images/icone-stylo-pour-editer.png "Icône stylo pour éditer")

L'affichage du fichier change pour passer en mode édition.

![Edition de la page](images/edition-de-la-page.png "Edition de la page")

Chaque page est découpée en 2 parties.

La première partie contient les *metadata* de la page. Celles-ci sont nécessaires pour l'organisation du site.

Le seconde partie est le contenu de la page. Ce contenu est au format [markdown](https://docs.framasoft.org/fr/grav/markdown.html). Il permet une structuration simple, ex.:

```
# Titre niveau 1
##  Titre niveau 2
### ...
texte normal
*texte en italique*
**texte en gras**
- élément d'une liste
...
```

### Créer la contribution

Une fois le contenu mis à jour, la création de la contribution s'effectue en cliquant sur le bouton `Commit changes` en bas.

![Creation de la contribution #1](images/creation-de-la-contribution-1.png "Creation de la contribution #1")

Cette contribution doit être confirmée avec le bouton `Create pull request` sur la page suivante.

![Creation de la contribution #2](images/creation-de-la-contribution-2.png "Creation de la contribution #2")

| :memo: ajouter un *message* et *des details* peut favoriser la prise en compte de la contribution par les relecteurs |
|----------------------------------------------------------------------------------------------------------------------|

Plus bas on trouve la différence entre l'ancienne version de la page et la nouvelle version.

![Creation de la contribution #3](images/creation-de-la-contribution-3.png "Creation de la contribution #3")

## Félicitations

Félicitations, vous venez de créer votre première contribution !

Les référents du projet vont recevoir une notification et relire cette contribution. Des questions, ou des retours, peuvent être fait.

Une fois la contribution validée, celle-ci sera incluse dans la branche principale du site. A chaque mise à jour de la branche principale, le site est republié et le contenu devient donc accessible à tous les visiteurs du site.
