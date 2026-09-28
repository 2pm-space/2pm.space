<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/fr/mcp-server; edits here are overwritten by the next export. -->

# MCP Server : connectez Claude Code et Cursor à votre espace de travail

> Un serveur MCP distant pour votre espace de travail 2pm.space. Connectez Claude Code, Cursor ou n'importe quel client MCP avec une clé API, et créez des agents, modifiez des documents Drive et des cartes mentales, interrogez des bases de données et gérez des tableaux de bord depuis votre éditeur — plus de 300 outils, limités à ce que la clé autorise.

[2pm.space/fr/mcp-server](https://2pm.space/fr/mcp-server) · [English](../mcp-server.md) · [Tiếng Việt](../vi/mcp-server.md) · [中文](../zh/mcp-server.md) · [日本語](../ja/mcp-server.md) · [한국어](../ko/mcp-server.md) · [ไทย](../th/mcp-server.md) · **Français** · [ລາວ](../lo/mcp-server.md)

*MCP Server · Claude Code · Cursor*

## Votre espace de travail, à l'intérieur de votre client IA

Connectez Claude Code, Cursor ou n'importe quel client MCP à 2pm.space avec une seule clé API. Demandez-lui de créer un agent, corriger un workflow, remplir un tableau Drive ou mettre un graphique sur un tableau de bord — il fait le travail à travers les mêmes opérations que l'application utilise, et seulement celles que votre clé autorise.

[Commencer gratuitement](https://2pm.space/signup)

## Connecté en trois étapes

Une clé, un extrait, une demande.

1. **Créez une clé API** — Sous Paramètres › Clés API & MCP, créez une clé et choisissez ce qu'elle peut faire. Une clé ne peut jamais détenir plus que la personne qui l'a créée.
2. **Collez l'extrait** — Copiez le bloc de serveur pour Claude Code ou Cursor — le endpoint, et votre clé dans un en-tête X-API-Key — dans le fichier de configuration du client.
3. **Demandez le travail** — Dites au client ce que vous voulez. Il liste les outils de l'espace de travail, lit le guide adapté à la tâche, et les appelle étape par étape.

## Tout l'espace de travail, sous forme d'outils

Pas une fenêtre en lecture seule — les mêmes opérations que celles de l'application.

### N'importe quel client MCP

Un serveur distant en Streamable HTTP, qui fonctionne donc avec Claude Code, Cursor et tout autre client parlant MCP. La page de configuration dans l'application vous donne l'extrait pour chacun.

### Plus de 300 outils

Les agents et leurs canevas, les outils, les compétences, les connaissances, les garde-fous et la mémoire, les documents Drive, les tableaux, les cartes mentales et les storyboards, les sources de données et les tableaux de bord, les marques, le calendrier de contenu et les canaux.

### Limité à la clé

Le serveur ne liste que les outils que les permissions de la clé autorisent, et une clé agit comme le membre qui l'a créée. Donnez à une clé des permissions de lecture seule, et elle ne peut rien changer.

### Des guides pour les tâches longues

Dix-neuf guides intégrés — créer un agent, mettre en place le RAG, organiser une source de données, planifier un calendrier de contenu — que le client lit avant de commencer.

### Votre Drive, depuis l'éditeur

Créez et modifiez des documents, remplissez des tableaux Drive, ajoutez des nœuds à une carte mentale ou des plans à un storyboard — et les changements sont là, dans l'application, pour votre équipe.

### Données et tableaux de bord

Interrogez une base de données connectée via son modèle sémantique, construisez un tableau de bord et ajoutez-y des graphiques, ou ajustez les mesures et relations du modèle.

## Ce que le serveur expose

La connexion, la clé, et les parties de l'espace de travail où un client peut travailler.

### Connexion

- Un serveur MCP distant en Streamable HTTP
- Un seul endpoint, affiché sur la page de configuration
- Des extraits pour Claude Code et Cursor
- Découvrable à /.well-known/ai-catalog.json

### Clés et permissions

- Une clé API d'espace de travail dans l'en-tête X-API-Key
- Une clé agit comme le membre qui l'a créée
- Des permissions jamais plus larges que celles de son créateur
- Une date d'expiration optionnelle
- Seuls les outils autorisés sont listés

### Agents

- Créer, configurer et supprimer des agents
- Modifier le canevas de workflow nœud par nœud
- Attribuer des outils, des compétences et des connaissances
- Enregistrer et restaurer des versions de canevas
- Lancer un test et lire la trace

### Drive et contenu

- Documents, dossiers et tableaux Drive
- Cartes mentales — nœuds, formes et tableaux
- Storyboards — scènes, plans et images
- Marques, leurs produits et leurs images
- Emplacements du calendrier de contenu

### Données

- Sources de données, tableaux et périmètres
- Le modèle sémantique : cubes, mesures, jointures
- Des requêtes en CubeQL ou en SQL
- Tableaux de bord BI, onglets, graphiques et filtres

### Canaux et inbox

- Les canaux et leurs paramètres
- Les conversations et leurs messages
- Les agents Care et leurs déclencheurs
- Les garde-fous et la mémoire

## Copier-coller entre onglets contre MCP

Le même changement, réalisé de deux façons.

| Sans 2pm.space | Avec 2pm.space |
| --- | --- |
| Décrivez l'application à votre IA, puis recopiez sa réponse dans l'application à la main. | Le client fait lui-même le changement, via les propres opérations de l'espace de travail. |
| Un jeton à accès complet collé dans un chat. | Une clé limitée à ce que son créateur peut faire — et la liste d'outils s'arrête là. |
| Le client devine comment fonctionne une configuration à plusieurs étapes. | Il lit d'abord le guide adapté à la tâche. |
| Reconstruire le même agent à la main dans chaque espace de travail. | Demandez une fois, et le client le construit nœud par nœud. |

## Questions sur MCP

Ce que les gens demandent avant de connecter un client.

### Quels clients fonctionnent ?

Tout client prenant en charge les serveurs MCP distants en Streamable HTTP. La page de configuration fournit des extraits prêts à l'emploi pour Claude Code et Cursor.

### Que peut faire un client dans mon espace de travail ?

Tout ce que la clé autorise : créer et tester des agents ; modifier des documents Drive, des tableaux, des cartes mentales et des storyboards ; interroger des bases de données connectées ; gérer des tableaux de bord, des marques, le calendrier de contenu et les paramètres de canal. La liste d'outils que voit le client est déjà filtrée selon ces permissions.

### Est-il sûr de donner une clé à un client IA ?

Une clé agit comme le membre qui l'a créée et ne peut détenir aucune permission que cette personne n'a pas. Il n'y a pas d'invite d'approbation sur MCP, donc les permissions de la clé font office de portail : n'accordez des permissions de lecture qu'à un client qui ne doit que lire, et fixez une date d'expiration sur une clé qui doit cesser de fonctionner.

### Est-ce que cela utilise mon crédit ?

La plupart des outils ne font que lire et écrire. Les outils qui génèrent quelque chose — un plan de calendrier, une image, une exécution de test d'un agent — utilisent le crédit de l'espace de travail exactement comme dans l'application.

## Travaillez dans votre espace de travail sans quitter votre éditeur

Créez une clé, collez l'extrait, demandez.

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
