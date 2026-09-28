<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/fr/integrations; edits here are overwritten by the next export. -->

# Intégrations — canaux, API, bases de données et MCP

> Connectez à vos agents IA des canaux de messagerie, des API HTTP, 6 bases de données, des serveurs MCP et du code en sandbox — décrits plutôt que codés, avec une API et un endpoint MCP propres à la plateforme.

[2pm.space/fr/integrations](https://2pm.space/fr/integrations) · [English](../integrations.md) · [Tiếng Việt](../vi/integrations.md) · [中文](../zh/integrations.md) · [日本語](../ja/integrations.md) · [한국어](../ko/integrations.md) · [ไทย](../th/integrations.md) · **Français** · [ລາວ](../lo/integrations.md)

*Canaux · Outils · MCP · API*

## Connectez-le à tout ce que vous utilisez déjà

Canaux de messagerie, API HTTP, bases de données, serveurs MCP et code en sandbox — décrits plutôt que codés, pour qu’un agent puisse atteindre le système qui détient la réponse au lieu de s’excuser de ne pas savoir.

[Commencer gratuitement](https://2pm.space/signup)

## Six façons d’atteindre le reste de votre stack

Quel que soit le système, l’une d’elles le couvre déjà.

### N’importe quelle API, décrite et non codée

Donnez à un outil une URL, une méthode, un en-tête d’authentification et un JSON Schema pour ses paramètres, puis accordez-le aux agents qui doivent l’appeler. Rien à déployer au-delà de l’endpoint que vous avez déjà.

### Du code quand décrire est plus difficile

Du Python en sandbox, appelable comme un outil : les arguments arrivent dans ARGS et le résultat est ce qu’il affiche. Pour les transformations, analyses et calculs plus rapides à écrire qu’à expliquer à un modèle.

### MCP, dans les deux sens

Pointez un outil vers n’importe quel serveur MCP, découvrez ses outils en un clic et activez, désactivez ou soumettez chacun à approbation — et pilotez cet espace depuis un client MCP externe, y compris un agent de code qui construit vos agents pour vous.

### Des agents comme outils

Exposez un agent à un autre. Un superviseur délègue à un spécialiste et reçoit une réponse structurée, au lieu d’embarquer une seconde copie du spécialiste dans son propre prompt.

### Les canaux comme intégrations

Messenger, Zalo personnel, Telegram, Pancake et un widget de site se connectent comme canaux à part entière. Tout le reste passe par le canal API personnalisée — un webhook entrant, un webhook sortant.

### Des événements envoyés chez vous

Les événements de la boîte de réception atteignent des endpoints qui vous appartiennent : un nouveau message peut déclencher une action dans votre stack. Les livraisons sont journalisées, et un récepteur tombé en panne reste visible au lieu de se perdre.

## Le catalogue

Ce qui se connecte aujourd’hui, par catégorie.

### Canaux de messagerie

- Facebook Messenger, et commentaires avec réponse privée
- Zalo personnel, Zalo Official Account bientôt
- Bots Telegram
- Comptes Pancake
- Widget de chat pour site web
- API personnalisée — webhook entrant, webhook sortant

### Types d’outils

- Outils intégrés, dont Viettel Post, KiotViet et WordPress
- Outils webhook — n’importe quelle API HTTP, avec authentification bearer ou par clé
- Fonctions Python en sandbox, hors ligne sauf si vous autorisez Internet
- Approbation humaine et cache des résultats, outil par outil
- Serveurs MCP — découvrez leurs outils, activez ou désactivez chacun
- Délégation à un agent utilisé comme outil

### Connexions de données

- PostgreSQL et MySQL
- Redshift et ClickHouse
- Snowflake et BigQuery
- Tables choisies à la connexion — le modèle ne lit qu’elles

### Publication et services

- Publication sur Pages Facebook et WordPress
- Destinations webhook personnalisées
- Comptes d’applications connectés pour les services tiers
- Livraison Viettel Post, avec paiement à la livraison

### Accès programmatique

- Clés API d’espace de travail, limitées aux autorisations de leur créateur
- Un endpoint MCP authentifié par la même clé
- Webhooks sortants sur les événements de la boîte de réception
- Journal de chaque appel, avec son coût

### Prêt à installer

- Une marketplace de modèles d’agents
- Des modèles clonés dans votre espace de travail, puis modifiés
- Compétences et outils partagés entre tous les agents
- Des applications bâties sur la plateforme et installées dans un espace de travail

## Ce qui cesse d’être un projet d’ingénierie

Les intégrations que vous auriez sinon dû écrire et maintenir.

| Sans 2pm.space | Avec 2pm.space |
| --- | --- |
| Une demande de connecteur dans le backlog de quelqu’un, en attendant qu’un éditeur le développe | Décrivez vous-même l’endpoint et l’agent peut l’appeler l’après-midi même |
| Du code de liaison déployé et maintenu pour chaque service interne que touche un agent | Des outils webhook, plus du Python en sandbox pour ce qui le demande |
| Un agent qui ne sait que parler, parce que rien de ce dont il a besoin ne lui est accessible | Canaux, API, bases de données et serveurs MCP, tous appelables depuis la même boucle |
| Copier le prompt d’un agent spécialiste dans chaque autre agent qui en a besoin | Un agent exposé comme outil, auquel les autres délèguent |
| Un jeton collé dans une configuration partagée pour qu’un script atteigne la plateforme | Des clés API d’espace de travail limitées aux autorisations de leur créateur, révocables une par une |

## Questions sur les intégrations

Ce que demandent les ingénieurs avant de brancher l’outil sur un système interne.

### Comment connecter un service qui ne figure pas dans la liste ?

Avec un outil webhook. Vous lui donnez l’URL, la méthode, l’en-tête d’authentification et un JSON Schema pour ses paramètres, puis vous l’accordez aux agents qui doivent s’en servir — ou vous le rendez Global pour tous. Aucun code déployé de notre côté, et rien du vôtre au-delà de l’endpoint que vous avez déjà.

### Les agents peuvent-ils exécuter du code ?

Oui — du Python, en sandbox, comme outil qu’un agent peut appeler. C’est la bonne réponse pour les transformations plus simples à écrire qu’à décrire : remettre en forme une charge utile, faire des calculs qu’on ne confie pas à un modèle, analyser quelque chose de biscornu. L’accès à Internet reste coupé tant que vous ne l’activez pas.

### MCP est-il pris en charge ?

Dans les deux sens. Un outil MCP pointe vers n’importe quel serveur : découvrez ses outils en un clic, puis choisissez ceux que les agents peuvent utiliser et ceux qui exigent une approbation. Et la plateforme expose son propre serveur MCP pour qu’un client externe — y compris un agent de code — pilote votre espace : créer des agents, modifier des documents, interroger des tableaux, gérer compétences et outils.

### Un agent peut-il en appeler un autre ?

Oui. Un agent peut être exposé comme outil : un superviseur peut ainsi déléguer à un spécialiste et recevoir une réponse structurée, plutôt que de réimplémenter ce que le spécialiste sait déjà faire.

### Comment fonctionnent les webhooks dans l’autre sens ?

Les événements de la boîte de réception peuvent être envoyés vers des endpoints qui vous appartiennent : un nouveau message ou une conversation résolue peut déclencher une action dans votre propre stack. Les livraisons sont journalisées, et un récepteur tombé en panne reste visible au lieu de devenir un message dont vous n’avez jamais entendu parler.

### Y a-t-il une API ?

Oui. Les clés API sont émises par espace de travail et portent les autorisations du membre qui les a créées : une clé ne peut pas faire plus que la personne derrière elle. La même clé authentifie l’endpoint MCP.

## Branchez-le sur le système qui a la réponse

Décrivez un endpoint, connectez une base de données ou indiquez-lui un serveur MCP. Gratuit pour commencer, sans carte bancaire.

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
