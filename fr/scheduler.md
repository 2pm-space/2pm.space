<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/fr/scheduler; edits here are overwritten by the next export. -->

# Scheduler : exécutez vos agents IA selon une planification

> Planifiez un agent IA pour qu'il s'exécute seul : une fois, quotidiennement, chaque semaine, chaque mois ou par expression cron, dans votre fuseau horaire. Le mode Batch API coûte environ moitié moins cher, avec des limites sur le nombre d'exécutions et une date d'expiration, et un historique de chaque réponse avec ses tokens et son coût.

[2pm.space/fr/scheduler](https://2pm.space/fr/scheduler) · [English](../scheduler.md) · [Tiếng Việt](../vi/scheduler.md) · [中文](../zh/scheduler.md) · [日本語](../ja/scheduler.md) · [한국어](../ko/scheduler.md) · [ไทย](../th/scheduler.md) · **Français** · [ລາວ](../lo/scheduler.md)

*Scheduler · Exécutions d'agents récurrentes*

## Des agents qui se présentent à l'heure, à chaque fois

Dites à un agent quoi faire et quand — un résumé des ventes à 8h00, une synthèse de contenu chaque lundi, une relance chaque soir. Il s'exécute seul, dans votre fuseau horaire, et range chaque réponse là où vous pouvez la lire.

[Commencer gratuitement](https://2pm.space/signup)

## Mettez un agent à l'heure

Choisissez l'agent, réglez l'heure, lisez les résultats.

1. **Choisissez un agent et une tâche** — Choisissez l'agent et écrivez ce qu'il doit recevoir, un message par ligne — chaque ligne est envoyée et traitée comme un élément séparé.
2. **Réglez le moment de l'exécution** — Une fois, quotidiennement, chaque semaine selon les jours cochés, chaque mois à une date, ou une expression cron — dans le fuseau horaire de votre choix.
3. **Lisez ce qu'il a fait** — Chaque exécution atterrit dans l'historique de la tâche avec chaque réponse, ses tokens et son coût. Exécutez-la maintenant, mettez-la en pause ou annulez-la depuis la liste.

## Une planification qui sait qu'elle fait tourner un agent

Pas une tâche cron qui déclenche un webhook — une exécution avec une conversation, des outils et un journal.

### Cinq types de planification

Une fois à une date, quotidiennement à une heure, chaque semaine sur les jours choisis, chaque mois à un jour du mois, ou n'importe quelle expression cron. Chaque planification respecte le fuseau horaire que vous réglez, pas celui du serveur.

### Les résultats vont là où on en a besoin

L'agent s'exécute avec ses outils, donc le rapport peut partir dès qu'il est rédigé : un message Telegram vers votre groupe commercial, un email, une notification à vos opérateurs, une ligne dans un tableau Drive.

### Moitié prix, quand ça peut attendre

Basculez un agent simple en Batch API et ses exécutions passent par la file d'attente batch du fournisseur — environ 50 % moins cher, terminées sous 24 heures. Pour les modèles Anthropic et OpenAI.

### De la mémoire d'une exécution à l'autre, si vous le souhaitez

Démarrez une nouvelle conversation à chaque exécution, continuez d'alimenter la plus récente pour que l'agent se souvienne de la dernière fois, ou publiez dans une conversation précise.

### Il s'arrête quand vous le décidez

Réglez une date d'expiration ou un nombre maximal d'exécutions, et choisissez combien de messages s'exécutent en parallèle — de un à dix.

### Chaque exécution consignée

Chaque exécution garde son statut, son début et sa fin, ainsi que la réponse ou l'erreur de chaque message avec ses tokens et son coût — également rassemblés sous Paramètres › Journaux.

## Toutes les options de planification

Ce que propose la fenêtre Créer une tâche, champ par champ.

### Planification

- Une fois, à une date et une heure
- Quotidiennement à une heure
- Chaque semaine, sur les jours que vous cochez
- Chaque mois, à un jour du mois
- Une expression cron personnalisée
- N'importe quel fuseau horaire

### Exécution

- Immédiatement, de 1 à 10 messages à la fois
- Batch API, environ 50 % moins cher, sous 24 h
- Batch pour les agents simples sur les modèles Anthropic ou OpenAI
- Les agents avec une étape Human Review ne peuvent pas être planifiés

### Entrée et conversation

- Un message par ligne, chacun son propre élément
- Une nouvelle conversation à chaque exécution
- Ou poursuivre la conversation la plus récente
- Ou une conversation précise par ID

### Limites

- Une date et une heure d'expiration
- Un nombre maximal d'exécutions
- Exécutions comptées dans la liste, par ex. 6/12

### Contrôle

- Exécuter maintenant
- Mettre en pause et reprendre
- Annuler
- Modifier ou supprimer
- Rechercher, et filtrer par statut ou mode

### Historique et journaux

- Le statut de chaque exécution et de chaque message
- Chaque réponse ou erreur, en intégralité
- Tokens et coût par message et par exécution
- Un onglet Exécutions du Scheduler dans les journaux de l'espace de travail

## Cron et scripts contre le Scheduler

Le même rapport matinal, de deux façons.

| Sans 2pm.space | Avec 2pm.space |
| --- | --- |
| Une tâche cron, un script et un serveur à maintenir en vie — pour poser une seule question. | Choisissez l'agent, écrivez la question, réglez l'heure. |
| Une exécution échoue à 3h du matin et vous ne le découvrez qu'une semaine plus tard. | Le statut et l'erreur de chaque exécution se trouvent dans l'historique de la tâche. |
| Chaque rapport repart de zéro. | Poursuivez la conversation la plus récente, et l'agent se souvient de la précédente. |
| Payer plein tarif pour un travail dont personne n'a besoin avant demain. | Les exécutions en Batch API coûtent environ moitié moins. |

## Questions sur le Scheduler

Ce que les gens demandent avant d'automatiser leur premier rapport.

### Que puis-je planifier ?

N'importe quel agent actif de votre espace de travail. Vous écrivez les messages qu'il doit recevoir, un par ligne, et chaque exécution les envoie et enregistre les réponses.

### Comment les résultats me parviennent-ils ?

Via les propres outils de l'agent. Donnez-lui Telegram Send Message, Gmail ou Notify Operators et indiquez dans le message où le résultat doit aller. Chaque réponse est aussi conservée dans l'historique d'exécution de la tâche.

### Qu'est-ce que le mode Batch API ?

Il envoie les messages d'une exécution via la file d'attente batch du fournisseur de modèle au lieu d'y répondre immédiatement. Cela coûte environ moitié moins et se termine sous 24 heures. Cela fonctionne pour les agents simples sur les modèles Anthropic ou OpenAI ; les workflows agentiques nécessitent une exécution multi-tours, donc ils s'exécutent toujours immédiatement.

### Quel fuseau horaire utilise-t-il ?

Celui que vous choisissez sur la tâche — par défaut, celui de votre navigateur. Les heures quotidiennes, hebdomadaires et mensuelles sont lues dans ce fuseau horaire.

### Puis-je planifier un agent avec une étape Human Review ?

Non. Une exécution planifiée n'a personne pour l'approuver, donc la fenêtre ne planifiera pas un agent dont le workflow contient un nœud Human Review.

### Une tâche peut-elle s'arrêter après un certain nombre d'exécutions ?

Oui. Réglez un nombre maximal d'exécutions, une date d'expiration, ou les deux. Vous pouvez aussi mettre en pause, reprendre ou annuler une tâche à tout moment.

## Laissez l'agent tenir le calendrier

Créez-le une fois, mettez-le à l'heure, et lisez les résultats devant votre café.

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
