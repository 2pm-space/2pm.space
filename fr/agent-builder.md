<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/fr/agent-builder; edits here are overwritten by the next export. -->

# Agent Builder : un créateur d'agents IA avec canevas de workflow visuel

> Créez des agents IA en un seul prompt ou sous forme de workflow : 16 types de nœuds pour la recherche, les outils, les boucles d'évaluation, la revue humaine et les embranchements. Testez vos exécutions avec un journal par étape, des versions de canevas, et un déploiement vers votre boîte de réception, une planification ou un client MCP.

[2pm.space/fr/agent-builder](https://2pm.space/fr/agent-builder) · [English](../agent-builder.md) · [Tiếng Việt](../vi/agent-builder.md) · [中文](../zh/agent-builder.md) · [日本語](../ja/agent-builder.md) · [한국어](../ko/agent-builder.md) · [ไทย](../th/agent-builder.md) · **Français** · [ລາວ](../lo/agent-builder.md)

*Agent Builder · Canevas de workflow · Exécutions de test*

## Des agents qui font le travail, pas juste des réponses à un prompt

Commencez avec un seul prompt, ou dessinez la tâche comme un workflow : trouver les bons documents, raisonner et appeler des outils, vérifier la réponse, demander à une personne quand c'est important, puis répondre. Chaque exécution montre ce qu'a fait chaque étape, ce qu'elle a dépensé et pourquoi.

[Commencer gratuitement](https://2pm.space/signup)

## De l'idée à l'agent opérationnel en trois étapes

Dessinez-le, équipez-le, mettez-le là où se trouve le travail.

1. **Dessinez la tâche** — Choisissez Simple pour un seul prompt, ou Agentic pour organiser la tâche en nœuds sur un canevas — recherche, raisonnement, vérifications, embranchements — reliés de gauche à droite.
2. **Donnez-lui ce dont il a besoin** — Attachez des outils, des compétences, des connaissances et de la mémoire à l'agent ou à un seul nœud, et définissez les garde-fous que chaque message doit traverser.
3. **Mettez-le au travail** — Testez-le sur le canevas, puis connectez-le à un canal de l'inbox, une planification, un autre agent en tant qu'outil, ou un client MCP.

## Plus qu'un prompt avec des outils

Un canevas pour les tâches qu'un seul prompt ne peut pas accomplir seul.

### Simple ou agentique

Un agent Simple est un seul appel de modèle avec votre prompt système — adapté aux questions, à la traduction et aux résumés. Un agent Agentic est un graphe de nœuds, pour les tâches qui demandent plusieurs étapes et une décision entre elles.

### Seize types d'étapes

Agent, Crew, Run Agent, Code, Knowledge Retrieval, Skill Retrieval, Drive Action, Condition, Parallel, Loop, Evaluation, Human Review, Message, Send — chacune une carte que vous glissez sur le canevas et reliez à la suivante.

### Il vérifie son propre travail

Un nœud Evaluation note la réponse avec des règles ou un LLM juge, puis l'oriente : Pass la fait avancer, Retry la renvoie à l'agent pour un nouvel essai, jusqu'au nombre de tentatives que vous autorisez.

### Une personne là où ça compte

Un nœud Human Review met l'exécution en pause jusqu'à ce que quelqu'un l'approuve ou la rejette, et un nœud Message peut demander des précisions au client via un formulaire ou des boutons avant que le flux ne se poursuive.

### Outils, compétences et connaissances

Soixante outils intégrés, vos propres API HTTP et votre Python, des serveurs MCP, et d'autres agents en tant qu'outils. Une compétence se charge dans chaque prompt, ou seulement quand une question lui correspond — pour qu'une grande bibliothèque ne coûte pas de tokens à chaque appel.

### Testez-le, tracez-le, revenez en arrière

Exécutez le flux depuis le canevas et lisez la sortie, les tokens et le coût de chaque nœud. Enregistrez des versions du canevas, et restaurez-en une quand un changement ne tient pas la route.

## Ce qu'il y a sur le canevas

Chaque nœud, le catalogue de modèles, et chaque endroit où un agent peut s'exécuter.

### Raisonnement et actions

- Agent — son propre modèle, prompt et outils, dans une boucle de raisonnement et d'action
- Crew — un équipage CrewAI d'agents et de tâches
- Run Agent — appelle un agent que vous avez déjà créé
- Code — Python ou Bash dans un bac à sable, sans coût LLM

### Contrôle de flux

- Start — là où un message entre
- Condition — embranchement sur une règle, sans coût LLM
- Parallel — toutes les branches sortantes à la fois
- Loop et Exit Loop — sur une liste ou N fois

### Vérifications et personnes

- Evaluation — règles ou LLM juge, puis Pass ou Retry
- Human Review — pause pour approuver ou rejeter
- Message — un message de chat, un formulaire ou des boutons
- Send — envoie un message au client et continue

### Connaissances et données

- Knowledge Retrieval — recherche sémantique, par mots-clés ou hybride
- Skill Retrieval — associe des compétences sans étape LLM
- Drive Action — crée, lit ou met à jour des documents, tableaux, cartes mentales et storyboards
- Une mémoire qui persiste d'une conversation à l'autre, et une mémoire d'espace de travail partagée par chaque agent

### Modèles

- Anthropic, OpenAI, Google et DeepSeek
- Alibaba Qwen, Z.AI GLM, xAI et MiniMax
- Un modèle par nœud Agent, pas un seul par workflow
- Facturé depuis le crédit de l'espace de travail — aucune clé de fournisseur à gérer

### Où il s'exécute

- Canaux de l'inbox : Messenger, Telegram, Zalo personnel, chat du site web
- Le Scheduler, selon un horaire récurrent
- Un autre agent, exposé comme outil
- Des clients MCP tels que Claude Code et Cursor
- Le Playground, avant qu'aucun client ne le voie

## Une simple zone de prompt contre un créateur d'agents

La même tâche, construite de deux façons.

| Sans 2pm.space | Avec 2pm.space |
| --- | --- |
| Un seul prompt essaie de rechercher, raisonner, vérifier et répondre en même temps — et vous ne voyez pas quelle partie a échoué. | Chaque tâche est son propre nœud, et le journal d'exécution montre ce que chaque nœud a reçu, renvoyé et dépensé. |
| Une mauvaise réponse part directement vers le client. | Un nœud Evaluation l'intercepte et la renvoie pour un nouvel essai avant que quiconque ne la voie. |
| Une action risquée nécessite qu'un développeur construise une étape d'approbation. | Placez un nœud Human Review devant elle, et l'exécution attend un accord. |
| Un changement qui casse l'agent oblige à le reconstruire de mémoire. | Restaurez la version du canevas d'avant le changement. |

## Questions sur Agent Builder

Ce que les gens demandent avant de construire leur premier workflow.

### Dois-je coder pour créer un agent ?

Non. Un agent Simple est un formulaire : modèle, prompt, outils. Un agent Agentic se dessine sur le canevas en glissant des nœuds et en les reliant. Le code est optionnel — un nœud Code exécute du Python ou du Bash quand vous voulez qu'une étape se fasse sans modèle.

### Quelle est la différence entre un agent simple et un agent agentique ?

Un agent simple effectue un seul appel de modèle avec votre prompt système et les outils et connaissances que vous y attachez. Un agent agentique exécute un graphe : chaque nœud fait une seule tâche — rechercher, raisonner, vérifier, s'embrancher, boucler, demander à une personne — et les liens décident de la suite.

### Quels modèles un agent peut-il utiliser ?

Le catalogue couvre Anthropic, OpenAI, Google, DeepSeek, Alibaba (Qwen), Z.AI (GLM), xAI et MiniMax, et sur un canevas agentique chaque nœud Agent choisit son propre modèle. L'usage est payé depuis le crédit de votre espace de travail, donc il n'y a aucune clé de fournisseur à gérer.

### Comment tester un agent avant que les clients ne le voient ?

Exécutez-le depuis le canevas ou le Playground. Chaque exécution est journalisée avec l'entrée, la sortie, les tokens, le coût et les appels d'outils de chaque étape, pour que vous puissiez voir où une réponse a dérapé et corriger ce nœud plutôt que tout le prompt.

### Plusieurs personnes peuvent-elles modifier le même agent ?

Oui. Le canevas se synchronise en temps réel et montre qui d'autre s'y trouve, et les versions de canevas vous permettent d'enregistrer un état sûr et de le restaurer plus tard.

### Où un agent peut-il s'exécuter une fois créé ?

Sur un canal de l'inbox — Messenger, Telegram, Zalo personnel ou le chat de votre site web — selon une planification, comme outil qu'un autre agent peut appeler, ou depuis un client MCP tel que Claude Code ou Cursor.

## Créez l'agent dont votre travail a vraiment besoin

Commencez avec un prompt. Faites-le grandir en workflow quand la tâche le demande.

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
