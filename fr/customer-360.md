<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/fr/customer-360; edits here are overwritten by the next export. -->

# Customer 360 — une seule fiche sur tous les canaux

> Customer 360 dans la boîte de réception : ouvrez une conversation et les messages de la même personne sur vos autres canaux y sont déjà — rapprochés par téléphone ou e-mail — à côté des numéros détectés, du client lié et des données en direct de vos propres systèmes.

[2pm.space/fr/customer-360](https://2pm.space/fr/customer-360) · [English](../customer-360.md) · [Tiếng Việt](../vi/customer-360.md) · [中文](../zh/customer-360.md) · [日本語](../ja/customer-360.md) · [한국어](../ko/customer-360.md) · [ไทย](../th/customer-360.md) · **Français** · [ລາວ](../lo/customer-360.md)

*Tous les canaux, une seule fiche*

## Customer 360, construit à partir de ce qui s’est déjà passé

Les conversations de tous les canaux, les numéros repérés en cours d’échange et les données en direct de vos propres systèmes se rassemblent en une seule vue client — celle que lit votre équipe et sur laquelle vos agents s’appuient pour répondre.

[Commencer gratuitement](https://2pm.space/signup)

## Comment la fiche se construit toute seule

Aucun chantier de saisie. Le profil découle des conversations que vous avez déjà.

1. **Connectez vos canaux** — Chaque conversation traitée par la boîte de réception alimente la fiche : qui a écrit, d’où, à quel sujet. Rien de plus à remplir — le profil existe parce que les conversations existent.
2. **Ajoutez vos propres données** — Branchez un endpoint d’enrichissement, importez un tableur ou synchronisez depuis une API interne. Puis choisissez une fois, pour tout l’espace de travail, si l’historique s’affiche dans le fil, dans un onglet Customer 360, ou pas du tout.
3. **Travaillez avec la vue d’ensemble** — Votre équipe répond avec l’historique sous les yeux, et vos agents répondent avec le même contexte — y compris ce qui vit dans vos systèmes plutôt que dans les nôtres.

## Un profil à jour parce qu’il est déduit

Pas un formulaire que quelqu’un doit penser à mettre à jour.

### Une personne, tous les canaux

Ouvrez un fil Messenger : les messages du chat du site et de Zalo de la même personne y sont déjà, rapprochés par le numéro de téléphone ou l’e-mail qu’ils partagent. Rien n’est rapproché sur un nom ressemblant — sans identifiant commun, deux fils restent séparés plutôt que d’être fusionnés au hasard.

### Des coordonnées que vous n’avez pas saisies

Les numéros que les clients écrivent en pleine conversation sont détectés, dédoublonnés avec ceux que vous avez déjà, et rattachés à la conversation — les numéros du personnel et des messages cités sont écartés au lieu d’être comptés.

### Vos systèmes, dans le panneau

Indiquez un endpoint que vous contrôlez. Nous envoyons les identifiants que nous détenons ; votre système répond avec des éléments de chronologie — commandes, appels, visites du site — affichés dans le fil ou dans l’onglet Customer 360, et non copiés dans notre base de données sauf si vous activez la mise en cache.

### Un contexte que votre agent peut utiliser

Mettez une source en cache et activez son contexte externe : l’agent qui répond le lit depuis ce cache — il peut parler de la commande sans que votre API interne se trouve sur le chemin critique de chaque message.

### Importez les clients que vous avez

Importez depuis un tableur avec un mappage de colonnes mémorisé, ou synchronisez depuis une source HTTP par curseur, chaque exécution reprenant là où la précédente s’est arrêtée. Les lignes sont indexées sur votre propre identifiant client : l’import suivant les met à jour au lieu de créer des doublons.

### Protégé dans la base de données, pas seulement dans l’API

Les fiches clients relèvent du système d’autorisations de l’espace de travail, appliqué au niveau de la base de données : un membre sans l’autorisation ne peut atteindre les lignes par aucun chemin — requête directe comprise.

## Ce que contient Customer 360

Ce qui arrive tout seul, ce que vous apportez, et qui a le droit de le voir.

### À côté de chaque conversation

- Les messages de la même personne sur ses autres canaux
- Les numéros de téléphone détectés, triés
- Le client lié, avec ses commandes récentes
- Étiquettes, notes internes et attributs personnalisés
- Un résumé structuré de la conversation

### Enrichissement depuis vos systèmes

- Un endpoint HTTP que vous contrôlez, en GET ou POST
- Identifiants envoyés : conversation, canal, ID externe, téléphones, e-mail, nom, attributs
- Un seul choix d’affichage pour l’espace de travail : dans le fil, en panneau ou masqué
- Limiter une source aux conversations individuelles ou de groupe
- En-tête d’authentification chiffré au repos, jamais renvoyé au navigateur

### Faire entrer vos clients

- Import de tableur avec mappage de colonnes mémorisé
- Sources HTTP en mode connexion ou synchronisation
- Synchronisation par curseur qui reprend là où elle s’est arrêtée
- Historique de synchronisation avec décomptes et erreurs
- Upsert sur votre ID externe, pour que les réimports mettent à jour

### Pour les agents

- Contexte externe activable par source
- Servi depuis le cache, hors du chemin critique de la réponse
- La mémoire que l’agent conserve sur le client
- Des outils qui peuvent agir sur la fiche

### Pour votre équipe

- Liste des clients avec recherche et filtres
- Une page détaillée par client
- Lier une conversation à un client, ou en créer un, depuis le panneau du contact
- Les autres canaux de la même personne, directement dans le fil ouvert

### Contrôle

- Protégé par autorisations, appliqué dans la base de données
- L’accès par canal s’applique : l’historique d’un canal qu’un membre ne peut pas ouvrir n’apparaît jamais dans son fil
- Données externes récupérées, pas copiées en silence
- Sources d’enrichissement désactivables sans être supprimées

## Ce que votre équipe n’a plus à reconstituer

La reconstitution manuelle qui disparaît quand la fiche se construit toute seule.

| Sans 2pm.space | Avec 2pm.space |
| --- | --- |
| Un client qui a écrit sur trois canaux, ce sont trois inconnus pour votre équipe | Les messages de ses autres canaux déjà dans le fil que vous ouvrez |
| Des numéros de téléphone recopiés à la main des conversations vers un tableur | Des numéros détectés, dédoublonnés et rattachés automatiquement |
| L’historique des commandes dans l’ERP, la conversation dans la boîte de réception, et un agent qui ne connaît ni l’un ni l’autre | Les données de vos systèmes dans le fil, et lisibles par l’agent une fois en cache |
| Un import CRM qui crée une liste parallèle que personne ne réconcilie | Des imports indexés sur votre propre identifiant client : réimporter met à jour au lieu de dupliquer |
| Toute personne ayant un compte peut lire tous les clients | Des fiches protégées par autorisations, appliquées dans la base de données comme dans l’API |

## Questions sur Customer 360

Ce que les équipes demandent avant d’y connecter un système interne.

### Qu’est-ce qui en fait une vue à 360° plutôt qu’une liste de contacts ?

Elle est assemblée plutôt que saisie, et se trouve là où vous travaillez : ouvrez une conversation et les messages de la même personne sur vos autres canaux — rapprochés par un numéro de téléphone ou un e-mail commun — sont déjà dans le fil, à côté des numéros qui y ont été détectés, du client auquel elle est liée avec ses commandes récentes, et de ce que remontent vos propres systèmes. Elle est à jour parce qu’elle est dérivée, pas parce que quelqu’un a pensé à la mettre à jour.

### Peut-elle afficher les données de notre propre CRM ou système de commandes ?

Oui. Vous indiquez un endpoint HTTP que vous contrôlez. Nous envoyons les identifiants que nous détenons — conversation, canal, ID externe, numéros de téléphone, e-mail, nom, attributs personnalisés — et votre endpoint répond avec les éléments de chronologie qu’il reconnaît : commandes, appels, visites du site. Rien n’est copié dans notre base par défaut ; c’est récupéré et affiché. Une source clients en mode connexion peut aussi afficher le nom, le téléphone et l’e-mail de la personne, lus en direct à l’ouverture de la conversation.

### L’agent IA peut-il utiliser ces données externes pour répondre ?

Seulement si vous l’activez pour cette source et en gardez une copie en cache. L’agent lit le contexte externe depuis ce cache au lieu de faire répondre votre endpoint à chaque message — une API interne lente ou limitée ne retarde donc jamais la réponse au client.

### Puis-je importer les clients que nous avons déjà ?

Oui — depuis un tableur avec un mappage de colonnes défini une fois et mémorisé, ou depuis une source HTTP synchronisée par curseur, chaque exécution reprenant là où la précédente s’est arrêtée. Les lignes sont indexées sur votre propre identifiant client : réimporter met à jour les mêmes clients au lieu d’en ajouter une seconde copie.

### Qui peut voir les fiches clients ?

Les données clients sont protégées par le système d’autorisations de l’espace de travail, et ce contrôle s’applique dans la base de données comme dans l’API — un membre sans l’autorisation ne peut lire les lignes par aucun chemin. L’accès par canal s’y ajoute : l’historique d’un canal qu’un membre ne peut pas ouvrir n’apparaît jamais dans son fil.

### Que se passe-t-il quand la même personne écrit depuis deux canaux ?

Les messages de l’autre canal apparaissent dans le fil ouvert, rapprochés par un numéro de téléphone ou un e-mail commun, tandis que les deux conversations restent distinctes. Rien n’est deviné à partir d’un nom ressemblant — sans identifiant commun, elles restent séparées. Dès que vous liez une conversation à un client, le rapprochement suit ce lien plutôt que les numéros. Si deux canaux décrivent en fait le même compte, le canal entier peut être fusionné dans l’autre.

## Voyez vos clients comme une seule personne

Connectez un canal et les fiches commencent à se construire d’elles-mêmes. Gratuit pour commencer, sans carte bancaire.

[Commencer gratuitement](https://2pm.space/signup) · [Nous contacter](contact.md)

---

**Produit**

- [AI Inbox](ai-inbox.md) — Messenger, Telegram, chat du site web et Zalo personnel dans une seule file
- [Live Chat](live-chat.md) — Un widget de chat IA sur votre propre site web
- [Customer 360](customer-360.md) — Une seule fiche sur tous les canaux
- [Ask Data](ask-data.md) — Interrogez votre base de données en langage courant
- [BI Dashboards](bi-dashboards.md) — Des tableaux de bord épinglés à partir de questions en langage courant
- [Content Calendar](content-calendar.md) — Planifier, rédiger, illustrer et publier
- [Brand Kit](brand-kit.md) — Voix, design et connaissances pour chaque rédacteur
- [Magic Studio](magic-studio.md) — Des images IA fidèles à votre marque, sur un canevas d’étapes
- [Storyboard](storyboard.md) — Du script aux plans, jusqu’aux clips rendus
- [Mind Map](mind-map.md) — Cartes mentales gratuites, en temps réel et sans limite
- [Application mobile](mobile-app.md)

**Plateforme**

- [Agent Builder](agent-builder.md) — Des agents de workflow qui recherchent, agissent et vérifient
- [Tool Catalog](tools.md) — 60 outils intégrés, vos propres API et MCP
- [Scheduler](scheduler.md) — Des agents qui s'exécutent selon un horaire
- [Intégrations](integrations.md) — Canaux, API, bases de données et MCP
- [MCP Server](mcp-server.md) — Travaillez dans votre espace de travail depuis Claude Code ou Cursor
- [Fine-Tuning](fine-tuning.md) — Entraînez un modèle sur vos propres conversations
- [Sécurité](security.md) — Rôles, partage, audit et sauvegarde
- [Tarifs](pricing.md)

**Entreprise**

- [Contact](contact.md)
- [Politique de confidentialité](https://2pm.space/privacy-policy)
- [Supprimer votre compte](https://2pm.space/delete-account)
