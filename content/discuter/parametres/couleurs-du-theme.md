---
title: "Couleurs du thème"
description: "Couleurs du thème"
date: 2021-01-30T10:30:29+02:00
draft: false
type: "mattermost"
weight: 3
---

# Couleurs du thème

_____

Les couleurs de l'interface utilisateur de Mattermost sont personnalisables dans **Paramètres du compte** > **Affichage** > **Thème**. Il est possible d'importer son propre thème depuis Slack, de personnaliser les couleurs soi-même, ou de choisir parmi les quatre thèmes par défaut conçus par l'équipe Mattermost.

## Thèmes standard

Sélectionnez **Couleurs du thème** pour choisir parmi les quatre thèmes par défaut conçus par l'équipe Mattermost. Pour personnaliser l'un d'eux, cliquez dessus puis sur **Personnaliser** pour le charger dans le sélecteur de couleurs.

## Importer des Thèmes depuis Slack


Pour importer un thème, allez dans le menu **Préférences > Thème de barre latérale** depuis Slack, ouvrez l'option de thème personnalisable, copiez le thème *color vector* et collez-le dans la zone de texte *Contribution thème Slack* de Mattermost. Les paramètres de thème qui ne sont pas personnalisables dans Slack seront les paramètres par défaut de Mattermost.


## Thèmes personnalisés

Vérifiez l'aperçu en temps réel des vos couleurs de thème personnalisé et cliquez sur **Sauvegarder** pour confirmer les modifications. Annulez vos modifications en sortant du module de paramétrage et en cliquant sur **Oui, Annuler**

#### Styles du menu latéral

- **Barre latérale BG :** Couleurs d'arrière-plan de la fenêtre des canaux, et les barres latérales de paramètres du Compte et du Groupe.

- **Barre latérale Texte :** Couleur du texte des canaux diffusés dans la fenêtre canaux, et onglets dans la barre latérale des paramètres du compte et du groupe.

- **Barre latérale Entête BG :** Couleur d'arrière-plan de l'entête en haut de la fenêtre des Canaux et d'entêtes des différents modules.

- **Barre latérale Entête du texte :** Couleur du texte de l'entête en haut de la fenêtre des Canaux et d'entête de tous les modules.

- **Barre latérale Texte Non Lu :** Couleur du texte des canaux non lus dans la fenêtre Canaux.

- **Barre latérale texte survolé BG :** Couleur de fond des noms de canaux et des onglets de paramètres lorsque vous les survolez

- **Barre latérale bordure de texte actif :** Couleur du marqueur rectangulaire à gauche du panneau des Canaux ou de la barre latérale des Paramètres indiquant le canal ou l'onglet actif.

- **Barre latérale couleur du texte actif :** Couleur du texte du canal ou de l'onglet actif dans le panneau des Canaux ou dans la barre latérale des Paramètres.

- **Indicateur de connexion :** Couleur de l'indicateur de connexion apparaissant près des noms des membres de l'équipe dans la liste des messages privés.

- **Indicateur d'absence.** Couleur de l'indicateur d'absence apparaissant à côté des noms des membres du groupe dans la liste des Messages Directs lorsqu'ils sont inactifs depuis 5 minutes.

- **Diamant de mention BG :** Couleur de fond du diamant indiquant les mentions non lues, qui apparaît à droite du nom du canal. C'est aussi la couleur de fond pour l'indicateur des « Messages non lus en dessous/ au dessus » apparaissant en haut ou en bas du panneau des canaux sur les plus petites fenêtres de navigation.

- **Texte du Diamant de Mention :** Couleur du texte du diamant de mention indiquant le nombre de mentions non-lues. C'est aussi la couleur de l'indicateur des "messages non lus en dessous/au dessus".

#### Styles du Canal Central

- **Canal Central BG :** Couleur du panneau central, RHS, et du fond des modales.

- **Texte du Canal Central :** Couleur de tous les textes (à l'exception des mentions, liens, hashtags, et blocs de code) dans le panneau central, RHS et les modales.

- **Séparateur des nouveaux messages :** Le séparateur des nouveaux messages apparaît en-dessous du dernier message lu quand vous cliquez sur un canal avec des messages non lus.

- **Soulignage de mention BG :** Couleur de soulignage sous vos mots qui déclenchent des mentions dans le panneau central et RHS.

- **Texte de soulignage des mentions :** Couleur du texte des mots qui déclenchent des mentions dans le panneau central et RHS.

- **Thème du code :** Couleur de fond et de syntaxe pour tous les blocs de code.

#### Style des liens et des boutons

- **Couleur des liens :** Couleur du texte de tous les liens, hashtags, mentions des coéquipiers, et boutons de basse priorité.

- **Fond des boutons :** Couleur du fond rectangulaire de tous les boutons de haute priorité.

- **Texte des boutons :** Couleur du texte sur le fond rectangulaire de tous les boutons de haute priorité.

#### Exemples de thème personnalisé


Personnalisez les couleurs de votre thème et partagez-les en copiant-collant les vecteurs de thèmes dans la zone de texte. Voir les exemples de thèmes et leurs vecteurs correspondants ci-dessous.

**GitHub**

![theme2](../../images/theme2.PNG)


```
{"awayIndicator":"#D4B579","buttonBg":"#66CCCC","buttonColor":"#FFFFFF","centerChannelBg":"#FFFFFF","centerChannelColor":"#444444","codeTheme":"github","linkColor":"#3DADAD","mentionBg":"#66CCCC","mentionColor":"#FFFFFF","mentionHighlightBg":"#3DADAD","mentionHighlightLink":"#FFFFFF","newMessageSeparator":"#F2777A","onlineIndicator":"#52ADAD","sidebarBg":"#F2F0EC","sidebarHeaderBg":"#E8E6DF","sidebarHeaderTextColor":"#424242","sidebarText":"#2E2E2E","sidebarTextActiveBorder":"#66CCCC","sidebarTextActiveColor":"#594545","sidebarTextHoverBg":"#E0E0E0","sidebarUnreadText":"#515151"}
```


**Monokai**

![theme3](../../images/theme3.PNG)


```
{"awayIndicator":"#B8B884","buttonBg":"#90AD58","buttonColor":"#FFFFFF","centerChannelBg":"#FFFFFF","centerChannelColor":"#444444","codeTheme":"monokai","linkColor":"#90AD58","mentionBg":"#7E9949","mentionColor":"#FFFFFF","mentionHighlightBg":"#54850C","mentionHighlightLink":"#FFFFFF","newMessageSeparator":"#90AD58","onlineIndicator":"#99CB3F","sidebarBg":"#262626","sidebarHeaderBg":"#363636","sidebarHeaderTextColor":"#FFFFFF","sidebarText":"#FFFFFF","sidebarTextActiveBorder":"#7E9949","sidebarTextActiveColor":"#FFFFFF","sidebarTextHoverBg":"#525252","sidebarUnreadText":"#CCCCCC"}
```


**Solarized Dark**

![theme1](../../images/theme1.PNG)


```
{"awayIndicator":"#E0B333","buttonBg":"#859900","buttonColor":"#fdf6e3","centerChannelBg":"#073642","centerChannelColor":"#93a1a1","codeTheme":"solarized-dark","linkColor":"#268bd2","mentionBj":"#dc322f","mentionColor":"#ffffff","mentionHighlightBg":"#d33682","mentionHighlightLink":"#268bd2","newMessageSeparator":"#cb4b16","onlineIndicator":"#2AA198","sidebarBg":"#073642","sidebarHeaderBg":"#002B36","sidebarHeaderTextColor":"#FDF6E3","sidebarText":"#FDF6E3","sidebarTextActiveBorder":"#d33682","sidebarTextActiveColor":"#FDF6E3","sidebarTextHoverBg":"#CB4B16","sidebarUnreadText":"#FDF6E3","errorTextColor":"#dc322f"}
```


**Gruvbox Dark**

![theme4](../../images/theme4.PNG)


```
{"awayIndicator":"#fabd2f","buttonBg":"#689d6a","buttonColor":"#ebdbb2","centerChannelBg":"#3c3836","centerChannelColor":"#ebdbb2","codeTheme":"monokai","errorTextColor":"#fb4934","linkColor":"#83a598","mentionBj":"#b16286","mentionColor":"#fbf1c7","mentionHighlightBg":"#d65d0e","mentionHighlightLink":"#fbf1c7","newMessageSeparator":"#d65d0e","onlineIndicator":"#b8bb26","sidebarBg":"#282828","sidebarHeaderBg":"#1d2021","sidebarHeaderTextColor":"#ebdbb2","sidebarText":"#ebdbb2","sidebarTextActiveBorder":"#d65d0e","sidebarTextActiveColor":"#fbf1c7","sidebarTextHoverBg":"#d65d0e","sidebarUnreadText":"#fe8019"}
```

[Voir plus de thèmes](https://docs.mattermost.com/help/settings/theme-colors.html).
