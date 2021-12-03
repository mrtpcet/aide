---
title: "Sites restreints"
description: "Articles à accès restreint"
date: 2020-05-03T10:30:29+02:00
draft: false
weight: 6
url: "/later/articles/sites-restreints/"
---

# Articles à accès restreint

wallabag offre un système pour récupérer les articles d'un site dont l'accès au contenu est restreint en fournissant vos identifiants lorsqu'un article est récupéré.

## Liste des sites compatibles

### Français

| Nom | Disponible à partir de la version |
| ------|-------- |
| Alternatives Economiques | 2.3 |
| Arrêt sur Images | 2.2 |
| Canard PC | 2.3 |
| Courrier International | 2.3 |
| GameKult | 2.3 |
| Le Figaro | 2.3 |
| Le Monde | 2.3 |
| Le Monde Diplomatique | 2.3 |
| Le Point | 2.3 |
| LWN.net | 2.3 |
| Mediapart | 2.2 |
| Next INpact | 2.2 |
| Reflets.info | 2.3 |
| The Economist | 2.3 |


## Gérez vos accès aux sites

Vous remarquez une entrée dans le menu de gauche: **Accès aux sites**.

Cliquez sur le lien pour aller à la gestion de vos accès aux sites. Vous pourrez ajouter autant de login / mot de passe que vous le souhaitez.

{% hint style="info" %}
Ces informations sont accessible uniquement par **VOUS** et aucun autre utilisateur de l'instance wallabag.
{% endhint %}

## Sécurité

Les logins et mots de passe que vous allez définir seront encodés dans la base de donnée. Cela veut dire qu'en tant qu'administrateur de wallabag, je (Herminien) peux les lire (si je récupère la clé d'encodage et que je décode vos identifiants manuellement).
Bien évidemment, je m'engage à ne pas le fairee.

Si vous souhaitez plus de détails technique, vous pouvez lire [ces informations (en anglais)](https://github.com/defuse/php-encryption/blob/master/docs/Tutorial.md#scenario-1-keep-data-secret-from-the-database-administrator).

