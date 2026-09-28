<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/fr/ask-data; edits here are overwritten by the next export. -->

# Dialoguez avec votre base de données — analytique IA et tableaux BI

> Connectez PostgreSQL, MySQL, Redshift, ClickHouse, Snowflake ou BigQuery, définissez vos mesures une fois, et laissez votre équipe poser ses questions en langage courant — avec le SQL et un graphique joints à chaque réponse.

[2pm.space/fr/ask-data](https://2pm.space/fr/ask-data) · [English](../ask-data.md) · [Tiếng Việt](../vi/ask-data.md) · [中文](../zh/ask-data.md) · [日本語](../ja/ask-data.md) · [한국어](../ko/ask-data.md) · [ไทย](../th/ask-data.md) · **Français** · [ລາວ](../lo/ask-data.md)

*6 bases de données et entrepôts*

## Interrogez votre base de données, obtenez une réponse vérifiable

Connectez Postgres, BigQuery, Snowflake ou ClickHouse, définissez vos mesures une fois, et laissez n’importe qui dans l’équipe poser sa question en langage courant. Chaque réponse arrive avec un graphique, un tableau et le SQL exécuté.

[Commencer gratuitement](https://2pm.space/signup)

## Se connecte à la base de données que vous utilisez déjà

Six moteurs, d'un Postgres sur votre propre serveur à un projet BigQuery. Choisissez-en un, collez les identifiants, sélectionnez les tables — la connexion est testée avant d'être enregistrée.

- **PostgreSQL** — Hôte, port 5432, mode SSL
- **MySQL** — Hôte, port 3306, mode SSL
- **ClickHouse** — Hôte, port HTTP 8123
- **Snowflake** — Compte, entrepôt et schéma
- **BigQuery** — Clé de compte de service et région
- **Redshift** — Point de terminaison du cluster, port 5439

- Identifiants chiffrés au repos, jamais renvoyés au navigateur
- Mode lecture seule : seul SELECT l'atteint
- Seules les tables que vous choisissez sont modélisées

## D’une chaîne de connexion à un tableau de bord

La modélisation est une première version que vous retouchez, pas un projet à planifier.

1. **Connectez une base de données** — Branchez PostgreSQL, MySQL, Redshift, ClickHouse, Snowflake ou BigQuery. Les identifiants sont chiffrés au repos, et une connexion peut être marquée en lecture seule pour que seul SELECT l’atteigne.
2. **Affinez le modèle** — Le schéma est analysé et une première version des cubes, jointures et mesures est générée. Masquez ce que personne ne doit interroger, renommez ce que seul son auteur comprenait, et ajoutez les mesures sur lesquelles votre activité rend réellement compte.
3. **Demandez, puis épinglez** — Posez vos questions en langage courant, vérifiez le SQL derrière la réponse, et épinglez celles qui méritent d’être gardées sur un tableau de bord que votre équipe ouvre chaque matin.

## Une analytique en libre-service qui n’invente pas de chiffres

Une couche sémantique sous les questions, pour que les réponses concordent entre elles.

### Demandez en langage courant

Tapez la question comme vous la poseriez à un collègue. La réponse revient sous forme de tableau et du graphique adapté à la forme du résultat — avec la requête exécutée, pour que chacun puisse vérifier le raisonnement.

### Un modèle sémantique, pas une supposition

Mesures, dimensions et jointures sont définies une fois et compilées dans chaque requête. Le chiffre d’affaires veut dire la même chose dans chaque réponse, et une question que le modèle ne sait pas exprimer ne devient pas en douce une jointure hallucinée.

### Une question vérifiée le reste

Enregistrez une réponse que vous avez vérifiée comme exemple vérifié. Sa question et son SQL rejoignent les exemples que le modèle lit avant d’écrire une requête : la prochaine question similaire suit le schéma que vous avez approuvé.

### Des tableaux de bord bâtis à partir des réponses

Épinglez n’importe quelle réponse sur un tableau de bord. Les tableaux de bord ont plusieurs onglets, des filtres partagés et une période qui reste relative — un tableau enregistré sur « 7 derniers jours » signifie toujours les 7 derniers jours le mois suivant.

### SQL Lab pour le reste

Certaines questions sont plus rapides à taper qu’à expliquer. Écrivez le SQL vous-même sur le même modèle sémantique, enregistrez les requêtes que vous réutilisez, tracez un résultat et épinglez-le à un tableau.

### Partagez des chiffres, pas des identifiants

Un tableau de bord partagé montre les chiffres sans livrer la base de données qui est derrière. L’accès s’accorde par source de données, et un lecteur reçoit un tableau de bord plutôt qu’une console de requêtes.

## Ce qu’il connecte, et ce que vous obtenez

Tout ce que la couche de modélisation, les tableaux de bord et la console SQL prennent réellement en charge.

### Bases de données et entrepôts

- PostgreSQL et MySQL
- Redshift et ClickHouse
- Snowflake et BigQuery
- Tables choisies à la connexion — le modèle ne lit qu’elles

### La couche sémantique

- Cubes générés à partir de votre schéma, puis affinés
- Mesures et dimensions calculées que vous définissez
- Jointures suggérées à partir des clés, confirmées par vous
- Cubes dérivés pour les formes que le SQL seul rend illisibles
- Contexte métier et vocabulaire lus par le modèle

### Tableaux de bord et graphiques

- Plusieurs onglets dans un même tableau de bord
- Des périodes relatives qui restent relatives
- Des filtres remontés de chaque tuile au niveau du tableau de bord
- Des graphiques choisis selon la forme du résultat
- Partage par lien, sans exposer la source de données

### Pour ceux qui écrivent du SQL

- SQL Lab sur la même connexion
- Paires question-SQL vérifiées
- Périmètre des tables — ce que le modèle peut voir ou non
- Limites de lignes appliquées à chaque requête
- Actualisation du schéma quand l’entrepôt évolue

### Accessible à vos agents

- Les agents peuvent interroger le même modèle sémantique
- Les réponses arrivent dans le chat, la boîte de réception ou un rapport planifié
- Endpoint MCP pour les clients externes
- Journal par exécution de la question, de la requête et du coût

### Contrôle

- Accès accordé par source de données
- Connexions en lecture seule
- Identifiants chiffrés au repos, jamais renvoyés au navigateur
- Partage de tableaux de bord sans la connexion

## Pourquoi les équipes arrêtent de faire des captures de tableaux de bord

Ce qui change quand les chiffres répondent d’eux-mêmes.

| Sans 2pm.space | Avec 2pm.space |
| --- | --- |
| Chaque question sur les chiffres part dans la file de l’analyste et revient la semaine suivante | Chacun pose sa question en langage courant et obtient la réponse, SQL joint |
| Un LLM branché sur des tables brutes, qui joint avec assurance les deux mauvaises colonnes | Des requêtes compilées à partir d’un modèle sémantique que vous avez défini et pouvez auditer |
| Le « chiffre d’affaires » veut dire une chose dans le fichier de la finance et une autre dans le tableau de bord des opérations | Une seule définition de chaque mesure, utilisée par chaque réponse et chaque tableau de bord |
| Un tableau de bord enregistré sur « 7 derniers jours » qui désigne en douce une semaine de mars pour toujours | Des périodes relatives qui restent relatives |
| Partager un chiffre implique de partager un identifiant de base de données | Des tableaux de bord partagés sans la connexion qui est derrière |

## Questions sur l’interrogation de vos données

Ce que les équipes data vérifient avant de brancher l’outil sur la production.

### Quelles bases de données et quels entrepôts puis-je connecter ?

PostgreSQL, MySQL, Redshift, ClickHouse, Snowflake et BigQuery. Une connexion peut être marquée en lecture seule pour que seul SELECT l’atteigne, et les identifiants sont chiffrés au repos et jamais renvoyés au navigateur.

### En quoi est-ce différent de laisser un LLM écrire du SQL brut ?

Un modèle qui devine d’après les noms bruts des tables joindra sans hésiter les deux mauvaises colonnes et vous donnera un chiffre faux avec assurance. Ici, les questions s’exécutent sur un modèle sémantique : vous définissez une fois les mesures, les dimensions et les jointures, et chaque réponse est compilée à partir de ces définitions. Le « chiffre d’affaires » veut dire la même chose dans chaque graphique, et une question que le modèle ne sait pas exprimer ne devient pas en silence une requête inventée.

### Dois-je tout modéliser avant d’obtenir une réponse ?

Non. Le schéma est analysé à la connexion et une première version des cubes, jointures et mesures est générée pour vous. Vous l’affinez ensuite — masquez les tables que personne ne doit interroger, renommez les colonnes dont le nom n’a de sens que pour leur créateur, et ajoutez les mesures sur lesquelles votre activité rend réellement compte.

### Puis-je encore écrire du SQL quand j’en ai besoin ?

Oui. SQL Lab exécute du SQL écrit à la main sur la même connexion et le même modèle sémantique — enregistrez les requêtes que vous réutilisez, tracez un résultat et épinglez-le à un tableau, ou transformez une requête en cube dérivé. Les exemples vérifiés viennent de ChatQL lui-même : enregistrez une réponse dont vous êtes sûr, et sa question et son SQL guident les requêtes écrites ensuite pour des questions similaires.

### Puis-je transformer les réponses en tableau de bord ?

Chaque réponse revient avec un tableau et un graphique que la plateforme a choisi selon la forme du résultat, et chacun peut être épinglé sur un tableau de bord. Les tableaux de bord ont plusieurs onglets, leurs propres filtres et périodes, et peuvent être partagés avec les personnes qui doivent voir les chiffres sans recevoir l’accès à la base de données qui est derrière.

### Qui peut voir quelles données ?

L’accès s’accorde par source de données, et un tableau de bord partagé n’emporte pas la connexion avec lui — le lecteur voit le tableau de bord, pas une console de requêtes. Connexions en lecture seule, limites de lignes sur chaque requête et journal par exécution de ce qui a été demandé et de ce que cela a coûté s’appliquent partout.

## Connectez une base de données et posez-lui une question

Gratuit pour commencer, sans carte bancaire, et des connexions en lecture seule pour que la première question ne puisse rien casser.

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
