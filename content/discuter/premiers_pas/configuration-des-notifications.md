---
title: "Configuration des notifications"
description: "Configuration des notifications"
date: 2021-01-30T10:30:29+02:00
draft: false
type: "mattermost"
weight: 4
---

# Configuration des notifications

_____

Les notifications de bureau, de courriel et de push mobile vous informent de l'activité dans Mattermost. Lorsque vous rejoignez une équipe, Mattermost vous informe des messages qui vous sont adressés, y compris lorsque :

  * quelqu'un vous mentionne spécifiquement avec votre identifiant `@nom`
  * quelqu'un vous envoie un message direct
  * quelqu'un mentionne votre nom d'utilisateur ou votre prénom dans un canal
  * quelqu'un notifie un canal dans lequel vous êtes en utilisant `@channel` ou `@all`
  * quelqu'un utilise un mot-clé que vous avez configuré


## Notifications de messages non lus

Vous êtes notifié par un nom de canal en gras et un astérisque de notification sur l'onglet de votre navigateur lorsqu’il y a eu de l’activité dans les canaux dont vous êtes membre depuis votre dernière connexion. Quand vous ouvrez un canal avec des messages non lus, un indicateur de messages non lus se trouve à l’endroit du dernier message lu.

#### Canal en caractères gras

Les canaux avec des messages non lus sont indiqués en gras dans le panneau de gauche. En cliquant sur le nom du canal, vous ferez disparaître les caractères en gras.

<div class="alert-info alert">
Modifiez les paramètres affichant le nom du canal en gras en cliquant sur <b>Menu du canal</b> > <b>Préférences de notification</b> > <b>Marquer le canal comme non-lu</b>.
</div>


#### Astérisques de mention

Les mentions non lues dans un canal sont indiquées en gras et par un astérisque de mention à côté du nom du canal dans le panneau de gauche. Cliquer sur le nom du canal supprime les caractères en gras et le astérisque de mention. Vous pouvez toujours vérifier les mentions récentes en cliquant sur **@** à côté du champ de recherche en haut de l’écran. En apprendre plus sur la manière de [mentionner une autre personne de l'équipe](http://docs.framateam.org/help/messaging/mentioning-teammates.html).

## Notifications par courriel

Des courriels sont envoyés pour toute mention que vous recevez alors que Mattermost est fermé ou que votre navigateur n’enregistre plus d’activité **pendant plus de 5 minutes**.

- Activez ou désactivez les notifications par courriel dans <i class="fa fa-bars" aria-hidden="true"></i> > **Paramètres du compte** > **Notifications** > **Notifications par e-mail**. Les choix sont&nbsp;:
  * Immédiatement
  * Toutes les 15 minutes
  * Toutes les heures
  * Jamais

- Configurez l’adresse de courriel où les notifications sont envoyées dans <i class="fa fa-bars" aria-hidden="true"></i> > **Paramètres du compte** > **Général** > **Courriel**.

## Notifications de bureau

Ce sont des notifications du navigateur qui apparaissent dans le coin de votre écran. Par défaut, ces notifications sont affichées pour tout type d'activité, tant que Mattermost est ouvert. Les notifications sur le bureau sont disponibles sur Firefox, Safari et Chrome.


- Configurez les cas où les notifications sont affichées dans <i class="fa fa-bars" aria-hidden="true"></i> > **Paramètres du compte** > **Notifications** > **Notifications de bureau**.


- Configurez les notifications sur le bureau pour chaque canal dans le **Menu du canal** > **Préférences de notification** > **Envoyer des notifications sur le bureau**. Par défaut, tous les canaux utilisent le paramètre global configuré dans **Paramètres du compte**.


## Sons des notifications


Un son de notification est joué pour toute activité qui déclenche une notification sur le bureau. Les sons des notifications sont disponibles sur Safari, Chrome et Edge.

- Activez ou désactivez les sons des notifications dans **Paramètres du compte** > **Notifications** > **Sons des notifications**.


## Notifications dans l'onglet du navigateur


L’icône de l’onglet du navigateur change pour vous informer des nouveaux messages non lus et des mentions, et indique si Mattermost est ouvert dans un onglet inactif du navigateur. Les notifications dans l’onglet du navigateur sont disponibles sur Firefox et Chrome.

- Les messages non lus sont indiqués par un astérisque (*) à côté d’une icône de Mattermost noire.

- Les mentions sont indiquées par une icône Mattermost rouge, avec le nombre de mentions non lues entre crochets.
