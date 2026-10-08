# Guide du joueur

Ce guide s'adresse à celles et ceux qui jouent.

## But du jeu

- ⚫ Les **attaquants** encerclent le roi.
- ⚪ Les **défenseurs** aident le roi 👑 à s'échapper.

Une pièce se déplace en ligne droite, comme une tour, sans sauter par-dessus les autres. Elle est capturée quand elle est prise en sandwich entre deux ennemis (se placer soi-même entre deux ennemis est sans risque). Les conditions de victoire du roi et de sa capture dépendent du plateau et des règles choisis : un **défi** affiche toutes les règles avant d'être accepté.

Les colonnes sont des lettres (`a`, `b`, `c`…) et les lignes des chiffres, la **ligne 1 étant en bas**, comme aux échecs.

## Lancer une partie

Une seule partie (ou un seul défi) à la fois par salon **ou par fil** : chaque post de forum a sa propre partie.

1. Tapez **`/tablut new`**. Un **assistant** privé s'ouvre avec des menus : plateau, adversaire, camp, puis, si vous le souhaitez, n'importe quelle règle.
2. Cliquez sur **Lancer le défi**. Le défi est publié dans le salon avec le récapitulatif des règles (✏️ = règle modifiée par rapport au plateau).
3. L'adversaire clique sur **Accepter** (ou **Refuser**). Vous pouvez **Annuler** tant que le défi n'est pas accepté. Sans adversaire désigné, le défi est ouvert : n'importe qui peut l'accepter.

Se défier soi-même lance une **partie solo** immédiatement, pratique pour tester un plateau ou des règles.

### Quand les commandes sont bloquées (post de forum)

Si le forum interdit d'écrire aux membres, les commandes `/` ne sont pas utilisables. Écrivez simplement le texte **`/tablut new`** dans le post (par exemple dans son message de départ) : le bot répond avec l'assistant, réservé à l'auteur du message. Les boutons du jeu, eux, fonctionnent toujours.

## Jouer

Tout se fait avec les **boutons sous le plateau** :

| Bouton | Effet |
| --- | --- |
| 🎯 **Jouer un coup** | Choisissez la pièce, puis sa destination dans les menus, puis confirmez. |
| 🤝 **Nulle** | Propose la nulle, ou l'accepte si l'adversaire l'a proposée (continuer à jouer = refuser). |
| 🏳️ **Abandonner** | Abandonne la partie, après confirmation. |
| 🔄 **Réafficher** | Republie le plateau en bas du salon. |

Seul le joueur dont c'est le tour peut jouer un coup. Le bot ne vous mentionne que lorsque c'est à vous de répondre ou de jouer.

### Commandes équivalentes

| Commande | Rôle |
| --- | --- |
| `/tablut move from:e1 to:e4` | Jouer un coup en tapant les cases. |
| `/tablut moves square:e1` | Lister les destinations possibles d'une pièce. |
| `/tablut board` | Réafficher le plateau. |
| `/tablut draw` · `resign` · `cancel` | Nulle · abandon · annuler son défi. |
| `/tablut challenge` | Lancer un défi en une seule commande (`opponent`, `board`, `side` et toutes les règles). |
| `/tablut boards` · `rules` · `help` | Plateaux, règles et aide. |

## Fin de partie

Le dernier plateau annonce le résultat. Le bouton ♟️ **Nouvelle partie** permet d'en lancer une autre dans le même fil sans rien taper.

## Partie perdue de vue ?

Le bot retrouve la partie dans les 50 derniers messages du salon. S'il y en a eu plus depuis le dernier plateau, faites un clic droit sur un message de plateau du bot → **Applications** → **Reprendre la partie**. Ne supprimez pas le dernier plateau : la partie reprendrait au précédent.
