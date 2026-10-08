# Politique de confidentialité — bot Discord MedievalGames

*Dernière mise à jour : 8 octobre 2026*

Cette politique explique quelles données le bot Discord **MedievalGames** (« le bot ») traite, pourquoi, et comment les faire effacer. Le responsable du traitement est **Balbereith** (« l'exploitant »), joignable en ouvrant un ticket sur [github.com/Balbereith/documents/issues](https://github.com/Balbereith/documents/issues).

En résumé : le bot **n'a pas de base de données**, ne collecte rien en dehors de Discord, ne revend rien et ne fait ni publicité ni profilage.

## 1. Données traitées

| Donnée | Pourquoi | Où elle se trouve |
| --- | --- | --- |
| **Identifiants Discord** (utilisateur, serveur, salon ou post) | Savoir qui joue, à qui c'est le tour, qui peut répondre à un défi | Dans les messages publiés par le bot, et en mémoire le temps de traiter une demande |
| **Données de partie** : plateau choisi, règles, liste des coups, proposition de nulle | Rejouer et reprendre la partie | Dans le pied de page des messages de plateau et de défi publiés par le bot |
| **Contenu de vos commandes, boutons et menus** (cases jouées, choix de l'assistant) | Exécuter votre action | Traité à la volée ; seul le résultat figure dans les messages du bot |
| **Contenu des messages des salons que le bot peut voir** | Reconnaître le texte `/tablut new` écrit dans un post de forum, pour ouvrir l'assistant de configuration | Reçu par le bot (c'est le sens de l'intention « Message Content » de Discord), **examiné uniquement pour y chercher ce texte**, puis ignoré immédiatement : il n'est ni enregistré, ni journalisé, ni transmis |
| **Historique récent d'un salon** (les 50 derniers messages) | Retrouver le dernier message du bot qui contient l'état de la partie | Lu à la demande ; seuls les messages du bot qui contiennent un état sont utilisés |

Le bot **ne lit pas** vos messages privés, ne collecte ni adresse e-mail, ni adresse IP, ni localisation, et ne crée aucun profil.

## 2. Où sont stockées les données

Le bot n'enregistre rien dans une base de données ou un fichier. L'état de la partie est écrit **dans les messages du bot, sur Discord** : ces messages sont donc hébergés par Discord, selon la [politique de confidentialité de Discord](https://discord.com/privacy), et visibles par toute personne qui peut lire le salon.

Le bot écrit des **journaux techniques** (démarrage, état de la connexion à Discord, erreurs) dans la console de la machine qui l'héberge. Ils peuvent mentionner des identifiants techniques (par exemple celui d'un salon ou d'un fil) mais **jamais le contenu de vos messages**. Ils servent uniquement à corriger des problèmes de fonctionnement et ne sont pas partagés.

## 3. Durée de conservation

- Les données de partie restent aussi longtemps que **le message du bot** qui les contient existe sur Discord. Supprimer ce message, le fil ou le salon les efface.
- Les journaux techniques sont conservés sur la machine d'hébergement et renouvelés automatiquement : au plus 3 fichiers de 5 Mo, les plus anciens étant écrasés.

## 4. Partage des données

Les données ne sont **ni vendues, ni louées, ni cédées**. Elles ne sont accessibles qu'à :

- **Discord**, qui héberge les messages et fait fonctionner le service ;
- l'hébergeur de la machine sur laquelle tourne le bot, **balbereith.com**, uniquement pour faire fonctionner le programme.

## 5. Vos droits

Conformément au RGPD, vous pouvez demander l'accès à vos données, leur rectification ou leur effacement, ou vous opposer à leur traitement, en ouvrant un [ticket](https://github.com/Balbereith/documents/issues) (sans y indiquer de donnée personnelle, voir la section 9). Comme les données se trouvent dans les messages du bot, le plus simple pour les effacer est de **supprimer ces messages** (ou de demander à un modérateur du serveur de le faire). Vous pouvez aussi introduire une réclamation auprès de la CNIL ([cnil.fr](https://www.cnil.fr)).

## 6. Base légale

Le traitement est nécessaire pour fournir le service que vous demandez en utilisant le bot (exécution de la demande) et correspond à l'intérêt légitime de l'exploitant à le faire fonctionner de manière fiable.

## 7. Mineurs

Le bot suit les règles de Discord, dont l'âge minimum d'utilisation (13 ans, ou plus selon le pays). Il ne vise pas les enfants et ne collecte pas volontairement de données les concernant.

## 8. Modifications

Cette politique peut évoluer. La date de dernière mise à jour figure en tête de ce document.

## 9. Contact

Pour toute question sur vos données, ouvrez un [ticket](https://github.com/Balbereith/documents/issues). Les tickets GitHub étant publics, n'y indiquez **aucune donnée personnelle** (ni identifiant, ni capture d'écran) : décrivez simplement votre demande, l'exploitant vous répondra et vous proposera au besoin un moyen d'échange plus discret.
