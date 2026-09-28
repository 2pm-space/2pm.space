<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/fr/security; edits here are overwritten by the next export. -->

# Sécurité et gouvernance pour les agents IA

> Autorisations par ressource, rôles personnalisés, accès par équipe et par canal, identifiants chiffrés, garde-fous sur les réponses des agents, journaux d’audit par exécution et sauvegardes planifiées.

[2pm.space/fr/security](https://2pm.space/fr/security) · [English](../security.md) · [Tiếng Việt](../vi/security.md) · [中文](../zh/security.md) · [日本語](../ja/security.md) · [한국어](../ko/security.md) · [ไทย](../th/security.md) · **Français** · [ລາວ](../lo/security.md)

*Rôles · Partage · Audit · Sauvegarde*

## Donnez à chacun exactement l’accès dont il a besoin

Autorisations par ressource, accès aux canaux par équipe, identifiants chiffrés, garde-fous sur ce que les agents peuvent dire, et un journal de chaque exécution — pour que mettre l’IA face à vos clients soit une décision que vous pouvez défendre.

[Commencer gratuitement](https://2pm.space/signup)

## Une gouvernance qui tient dès la deuxième équipe

Les contrôles qui décident si l’on peut confier à l’IA une vraie conversation client.

### Des rôles adaptés au poste

Propriétaire, Admin et Membre d’emblée, et des rôles personnalisés quand ceux-ci ne conviennent pas. Les autorisations s’accordent par ressource et par action : « gère la boîte de réception, ne voit jamais la facturation » devient un rôle plutôt qu’une règle que quelqu’un doit retenir.

### Partage par ressource

Un agent, un document, un dossier, un outil ou un tableau de bord porte sa propre liste d’accès en plus des rôles — voir, utiliser, modifier ou gérer (voir, commenter ou modifier pour un document), accordé à un membre, à une équipe ou à tout le monde.

### Séparation par canal

Les canaux sont fermés par défaut. Attribuez une Page, un compte Zalo ou un widget à un membre, à un rôle ou à une équipe au niveau Voir, Répondre, Configurer ou Accès complet, et la boîte de réception qu’ils ouvrent ne contient que ces conversations — ce dont une agence a besoin, comme une équipe de support dédiée à un seul produit.

### Des secrets qui restent secrets

Identifiants de base de données, jetons de canaux et en-têtes d’authentification des endpoints sont chiffrés au repos et jamais renvoyés au navigateur. Les formulaires indiquent qu’un secret est configuré ; ils ne le réaffichent pas.

### Des garde-fous sur ce que disent les agents

Des règles appliquées à ce qui entre dans un agent et à ce qui en sort, avec un audit indiquant quel garde-fou s’est déclenché, ce qu’il a fait et pourquoi — une réponse bloquée devient une trace, pas un mystère.

### Un journal pour chaque type d’exécution

Exécutions d’agents avec leurs appels d’outils et leur coût, tâches planifiées, livraisons de webhooks, envois de suivi, erreurs de la plateforme et chaque modification d’accès — chacun avec sa propre liste plutôt qu’un flux indifférencié.

## Ce que vous pouvez contrôler

Accès, traitement des données, visibilité et continuité.

### Identité et accès

- Rôles système Propriétaire, Admin et Membre
- Rôles personnalisés avec droits par ressource et par action
- Équipes, avec responsables et membres
- 55 ressources soumises à autorisation, 201 permissions
- Invitations et révocation des accès depuis un seul écran

### Partage au niveau des ressources

- Voir, utiliser, modifier, gérer — voir, commenter, modifier pour les documents
- Accordés à un membre, à une équipe ou à l’espace de travail
- S’applique aux agents, documents, dossiers et outils
- S’applique aux bases de connaissances, canaux, sources de données et tableaux de bord
- Documents partagés par lien, au niveau de votre choix

### Traitement des données

- Isolation de l’espace de travail à chaque requête
- Identifiants chiffrés au repos
- Secrets jamais renvoyés au navigateur
- Connexions aux bases de données en lecture seule là où vous le voulez
- Données clients externes récupérées, pas copiées en silence

### Visibilité

- Journaux d’exécution par exécution avec tokens et coût
- Audit des garde-fous — lesquels se sont déclenchés, et ce qu’ils ont fait
- Historique des exécutions planifiées
- Journal de livraison des webhooks
- Journal des erreurs de la plateforme, et journal des accès pour chaque changement de rôle ou de partage

### Sauvegarde et continuité

- Sauvegardes à la demande et planifiées
- Restauration dans l’espace de travail
- Export des données de l’espace de travail
- Utilisation du stockage visible par espace de travail

### Accès programmatique

- Clés API limitées aux autorisations de leur créateur
- La même clé authentifie l’endpoint MCP
- Clés révocables une par une
- Journal de chaque appel avec attribution du coût

## Ce qui change quand l’accès est granulaire

Les contournements qui ne sont plus nécessaires.

| Sans 2pm.space | Avec 2pm.space |
| --- | --- |
| Toute personne qui peut se connecter voit tout, parce que l’accès est tout ou rien | Des autorisations par ressource et par action, plus une liste d’accès par ressource |
| Confier une Page à un prestataire revient à lui livrer tout l’espace de travail | Un accès aux canaux attribué à un membre, à un rôle ou à une équipe |
| Un jeton d’API collé dans un fichier de configuration et partagé dans toute l’équipe | Des identifiants chiffrés au repos, jamais réaffichés une fois enregistrés |
| Une réponse de l’IA qui a mal tourné, sans moyen de voir ce qu’elle a fait ni ce qu’elle a coûté | Un journal par exécution avec chaque appel d’outil, chaque résultat de garde-fou et le coût de chaque étape |
| Des sauvegardes qui existent si quelqu’un a pensé à en lancer une | Des sauvegardes planifiées, avec restauration dans l’espace de travail |

## Questions sur la sécurité et la gouvernance

Ce qu’un administrateur vérifie avant d’inviter la deuxième équipe.

### Quel est le niveau de finesse des autorisations ?

Les autorisations s’accordent par type de ressource et par action — lire les agents, créer des outils, restaurer des sauvegardes, lancer un entraînement : 55 ressources et 201 permissions, autant de droits distincts. Trois rôles existent d’emblée (Propriétaire, Admin, Membre) et vous pouvez définir les vôtres, vides ou copiés de l’un d’eux : « peut répondre dans la boîte de réception mais ne peut pas toucher à la facturation » devient un rôle plutôt qu’une exception que quelqu’un doit retenir.

### Puis-je partager un seul agent ou un seul document sans partager l’espace de travail ?

Oui. En plus des autorisations de rôle, chaque ressource — agents, documents, dossiers, outils, bases de connaissances, canaux, sources de données et tableaux de bord — porte sa propre liste d’accès. Vous accordez à un membre, à une équipe ou à tout l’espace de travail un niveau sur cet élément précis : voir, utiliser, modifier ou gérer pour un agent, un outil ou un tableau de bord ; voir, commenter ou modifier pour un document ou un dossier.

### Une agence peut-elle donner à l’équipe d’un client l’accès à ses seuls canaux ?

C’est exactement le rôle de l’accès par canal. Les canaux sont fermés par défaut : une Page, un compte Zalo ou un widget est attribué à un membre, à un rôle ou à une équipe au niveau Voir, Répondre, Configurer ou Accès complet, et la boîte de réception qu’ils ouvrent ne contient que les conversations de ce qui leur est confié. Les propriétaires et les admins voient tous les canaux. Pour répondre à un client, il faut les deux moitiés : la permission Répondre du rôle et le niveau Répondre sur ce canal.

### Où sont conservés les identifiants et les jetons d’API ?

Chiffrés au repos, et jamais renvoyés au navigateur. Un formulaire de paramètres qui affiche une intégration connectée indique qu’un secret est configuré ; il ne réaffiche pas sa valeur. Cela vaut aussi bien pour les connexions aux bases de données que pour les jetons de canaux et les en-têtes d’authentification des endpoints d’enrichissement.

### Que puis-je voir de ce que l’IA a réellement fait ?

Chaque exécution est journalisée de bout en bout : les messages, les outils appelés et ce qu’ils ont renvoyé, les tokens et le coût par étape, et les garde-fous déclenchés avec ce qu’ils ont fait. Des journaux distincts couvrent les exécutions planifiées, les livraisons de webhooks, les envois de suivi et les erreurs de la plateforme.

### Puis-je récupérer mes données, et puis-je les supprimer ?

Les sauvegardes peuvent être lancées à la demande ou selon un planning, et restaurées dans l’espace de travail. La suppression est une action à part entière plutôt qu’un ticket de support : un membre peut supprimer son propre compte depuis le site, et les données d’un espace de travail disparaissent avec lui.

## Configurez-le à l’image de votre organisation

Rôles, équipes et accès par ressource sont là dès le premier espace de travail. Gratuit pour commencer, sans carte bancaire.

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
