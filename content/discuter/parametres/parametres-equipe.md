---
title: "Paramètres d'équipe "
description: "Paramètres d'équipe"
date: 2021-01-30T10:30:29+02:00
draft: false
type: "mattermost"
weight: 4
---


# Paramètres d'équipe

___

Le menu Paramètres d"équipe permet aux administrateur·trice·s d'équipes, aux propriétaires d'équipes et aux administrateur·trice·s système de modifier les paramètres appliqués à une équipe en particulier.

Les paramètres suivants sont disponibles sur un site d'équipe depuis le menu **Trois-points** en haut du panneau latéral gauche dans **Paramètres d'équipe**.

### Général

Les paramètres généraux dans le menu **Paramètres d'équipe** > **Général** configurent la manière dont une équipe est affichée aux utilisateur·trice·s.

#### Nom d'équipe

Votre **Nom d'équipe** est affiché sur la page de connexion et en haut de la barre latérale gauche pour votre équipe.

#### Changer le nom affiché de l'équipe

Pour spécifiez le nom de l'équipe tel qu'il apparaîtra sur la page de connexion et en haut de la barre latérale de gauche, vous devez&nbsp;:

  1. cliquer sur <i class="fa fa-bars" aria-hidden="true"></i>
  * aller dans **Paramètres d'équipe**
  * aller dans **Général**
  * cliquer sur **Modifier** dans **Nom d'équipe**
  * faire le changement
  * cliquer sur **Save**

#### Autoriser tout le monde à s'inscrire depuis la page de connexion

Activer cette option ajoute un lien vers la page de création de compte sur la page de connexion de cette équipe.

Les administrateur·trice·s d'équipe devraient activer cette option lorsque iels travaillent sur internet et désirent autoriser n’importe qui à s’inscrire.

Les administrateur·trice·s d'équipe devraient désactiver cette option lorsque ils travaillent sur Internet et ne désirent qu’une petite équipe privée sur la base d’invitations. Pour ce faire il faut&nbsp;:

  1. cliquer sur l'icône <i class="fa fa-bars" aria-hidden="true"></i>
  * cliquer sur **Paramètres d'équipe**
  * cliquer sur **Permettre à n'importe quel utilisateur·trice disposant d'un compte de rejoindre cette équipe**
  * cocher **Non**
  * cliquer sur **Enregistrer**

#### Ajouter cette équipe dans le répertoire des équipes

Activer cette option ajoute le nom de l’équipe sur la page l’accueil et un lien vers cette équipe sur la page de connexion.

Les administrateur·trice·s d'équipe devraient activer cette option lorsque iels travaillent sur internet et désirent autoriser tout le monde à s’inscrire à leur équipe depuis la page d’accueil du serveur Mattermost.

Les administrateur·trice·s d'équipe devraient désactiver cette option lorsque ils travaillent sur Internet et ne désirent qu’une petite équipe privée sur la base d’invitations.

Les administrateur·trice·s peuvent désactiver le répertoire des équipes pour tout le système en désactivant l’option **Console système** > **Paramètres d’équipe** > **Activer le répertoire des équipes**.

#### Code d'invitation

Le **Code d’invitation** est utilisé dans l’URL du lien d’invitation dans l’équipe disponible dans **Menu principal** > **Obtenir le lien d’invitation**. Cliquer sur **Re-générer** puis **Sauvegarder** pour obtenir un nouveau lien d’invitation et invalider le précédent.

### Gestion

#### Quitter une équipe


{{< hint warning >}}
Si vous quittez une équipe privée vous devrez vous faire inviter à nouveau !
{{< /hint >}}

Pour quitter une équipe vous devez&nbsp;:

 * cliquer sur l'icône <i class="fa fa-bars" aria-hidden="true"></i>
 * cliquer sur **Quitter l'équipe**

#### Ajouter et retirer un canal des "Favoris"

Vous avez la possibilité de marquer des canaux comme **Favori**. Cela permet de les regrouper dans une même section, au-dessus des canaux publics et privés. Pour ajouter ou retirer un canal des favoris vous devez&nbsp;:

  * aller dans le canal
  * cliquer sur l'icône <i class="fa fa-star" aria-hidden="true"></i> à côté du nom du canal en haut de la page

### Importation

#### Importer depuis Slack (Bêta)

*Note : En tant que service propriétaire, Slack peut changer son format d’exportation rapidement et sans avertissement. Si vous rencontrez des problèmes non mentionnés dans la documentation ci-dessous, merci d’en informer l’équipe de production en [signalant un problème](https://github.com/mattermost/platform/issues).*

L’option d’import depuis Slack est en « bêta » et se concentre sur la migration d’équipes de moins de 100 utilisateur·trice·s inscrits. Mode d’emploi :

1. Générez un « fichier d’export » Slack dans **Slack > Paramètres d’équipe > Importer/Exporter des informations > Exporter > Commencer l’export**.

2. Dans Mattermost, allez dans **Paramètres d’équipe > Importer > Importer depuis Slack**. Il faut être propriétaire d'équipe ou administrateur·trice d'équipe pour avoir accès à ce menu.

3. Cliquez sur **Choisir un fichier** pour envoyer votre fichier d’export Slack et cliquez sur **Importer**.

4. Les adresses e-mail et noms d’utilisateur·trice·s de Slack sont utilisés pour créer les nouveaux comptes Mattermost.

5. Les utilisateur·trice·s de Slack peuvent activer leur nouveau compte Mattermost depuis la page de réinitialisation des mots de passe avec leur adresse mail de Slack afin de définir de nouveaux mots de passe pour leur compte Mattermost.

6. Une fois connectés, les utilisateur·trice·s de Mattermost auront accès aux précédents messages dans les canaux publics importés depuis Slack.

#### Limites

- Les utilisateur·trice·s ne sont pas automatiquement ajoutés aux canaux ou groupes lors de l’import depuis Slack.

- Le nouveau support de la syntaxe markdown ajouté dans les messages Slack 2.0 et annoncé le 28 septembre 2015 n’est pas encore supporté.

- Slack n’exporte pas les fichiers ou images que votre équipe a stockés dans la base de données Slack. Mattermost fournira des liens vers vos contenus dans l’interface web de Slack.

- Slack n’exporte aucun élément des groupes privés ou des messages privés que votre équipe a stockés dans la base de données de Slack.

- En version bêta, les comptes Slack avec des noms d’utilisateur·trice·s ou des adresses e-mail identiques à ceux de comptes Mattermost existants ne seront pas importés et seront désignés par leur identifiant Slack. Il n’y a pour le moment aucun outil de vérification avant import ou d’annulation.
