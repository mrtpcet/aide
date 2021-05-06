---
title: "Astuces"
description: "Astuces"
date: 2020-05-03T10:30:29+02:00
draft: false
weight: 4
---

# Astuces
_____

## Intégrer des images à un Framadate

Framadate classique permet d'insérer des images pour faire un sondage. Pour cela, il faut que les images soient déjà en ligne. Si elles sont sur votre ordinateur, vous devez les mettre sur un hébergeur d'images. Dans notre exemple, celui-ci sera [Lutim](https://pic.infini.fr/).

**Sur Lutim** :

  * cliquez sur **Cliquez pour utiliser le navigateur de fichier**
  * sélectionnez les photos à insérer (maintenez la touche `ctrl` en cliquant sur les photos pour en sélectionner plusieurs)
  * cliquez sur **Ouvrir** pour les envoyer sur Framapic

Vous obtenez alors les liens vers vos photos. Les liens utiles pour Framadate sont ceux fléchés :

![Lien markdown framapic pour insérer dans framadate](../img/framapic_photo_date.png)

En copiant ces liens et en les collant dans Framadate :

![Liens markdown des images dans Framadate](../img/date_classique_liens_md.png)

Vous obtenez l'affichage des images :

![Affichage des images dans Framadate](../img/date_classique_images.png)

## Intégrer un Framadate dans un site

Pour afficher un Framadate directement dans un site vous pouvez utiliser un code HTML `iframe` : `<iframe src="https://date.pcet.link/lien-public" width="100%" height="700px" />`

  * `src=""` doit contenir le lien **public** de votre Framadate
  * `width=""` est la largeur que doit prendre le framadate dans votre page (`100%` signifie qu'il prendra toute la largeur de la page)
  * `height=""` est la hauteur ; vous pouvez utiliser des pixels (comme ci-dessus) ou des pourcentages (`90%` par exemple)
