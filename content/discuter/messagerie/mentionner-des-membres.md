---
title: "Mentionner des membres"
description: "Mentionner des membres"
date: 2021-01-30T10:30:29+02:00
draft: false
type: "mattermost"
weight: 3
---

# Mentionner des membres

_____

## @Mentions

Utilisez les @mentions pour attirer l'attention de certains membres d'une équipe.

#### @utilisateur

Vous pouvez mentionner une personne en utilisant le symbole '@' puis leur nom d'utilisateur·trice pour leur envoyer une notification de mention. Saisissez '@' et vous verrez une liste des membres de votre équipe pouvant être mentionnés.

Saisissez complètement un nom d'utilisateur·trice ou utilisez les flèches **Haut** et **Bas** et appuyez ensuite sur **ENTRÉE** afin de sélectionner les utilisateur·trice·s que vous souhaitez mentionner.

L'exemple suivant envoie une notification spéciale qui alertera **Alice** et lui indiquera le canal et le message dans lesquels elle a été mentionnée. Si **Alice** n'est pas connectée sur Mattermost et a activé les [notifications par e-mail](lien vers notifications emails), elle recevra un e-mail lui indiquant la même chose.


```
@Alice tu pourrais nous envoyer le compte rendu de la dernière réunion ?
```

Si l'utilisateur·trice que vous avez mentionné n'est pas présent dans le canal, un message système vous sera envoyé pour vous le faire savoir. Ce message est temporaire et peut seulement être vu par la personne l'ayant déclenché. Pour ajouter l'utilisateur·trice mentionné au canal, allez dans le menu déroulant en dessous du nom du canal et sélectionnez **Ajouter des membres**.

#### @channel


Vous pouvez alerter un canal entier en tapant @channel. Tous les membres du canal recevront alors une notification, comme s'ils avaient été alertés personnellement.

```
@channel Mardi soir ça vous va pour notre prochaine réunion ?
```

### @all


Vous pouvez alerter une équipe entière en tapant @all. Tous les membres de la framateam recevront alors une notification.

```
@all j'ai crée un nouveau canal "Gestion nourriture" pour gérer la nourriture de notre fête ! Pensez à joindre ce nouveau canal !
```


## Mots qui déclenchent des alertes

En plus d'être notifié par @nomutilisateur et @channel, vous pouvez sélectionner des mots pour qu'ils déclenchent des notifications dans **Paramètres du compte** > **Notifications** > **Mots déclenchant des mentions**. Par défaut, vous recevrez des notifications de mention sur votre prénom, et vous pouvez ajouter plus de mots en les saisissant dans la zone de texte, séparés par des virgules. C'est utile si vous voulez être notifié sur tous les posts d'un certain sujet, par exemple, « entretiens » ou « marketing ».

## Mentions récentes

Cliquez sur `@` à côté du champ de recherche pour chercher vos récentes @mentions et les mots qui produisent des mentions. Cliquez sur **Sauter** à côté d’un résultat de recherche sur le panneau de droite pour faire sauter le panneau central sur le canal à l’endroit du message avec la mention.
