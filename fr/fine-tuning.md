<!-- Generated from the 2pm.space marketing site — the live page is https://2pm.space/fr/fine-tuning; edits here are overwritten by the next export. -->

# Fine-tuning d’un modèle IA sur vos propres conversations

> Notez les réponses de votre agent IA dans la boîte de réception, corrigez celles qui ont manqué leur cible, affinez un modèle open-weight sur ces paires avec LoRA, et branchez un agent sur le résultat — facturé sur le même solde de crédit que tout le reste.

[2pm.space/fr/fine-tuning](https://2pm.space/fr/fine-tuning) · [English](../fine-tuning.md) · [Tiếng Việt](../vi/fine-tuning.md) · [中文](../zh/fine-tuning.md) · [日本語](../ja/fine-tuning.md) · [한국어](../ko/fine-tuning.md) · [ไทย](../th/fine-tuning.md) · **Français** · [ລາວ](../lo/fine-tuning.md)

*LoRA sur modèles open-weight*

## Affinez un modèle sur vos propres conversations

Notez les réponses de votre agent dans la boîte de réception et corrigez celles qui ont manqué leur cible, affinez un modèle open-weight sur ces paires, et branchez un agent sur le résultat — le ton que vous réexpliquez sans cesse dans un prompt vit alors dans les poids.

[Commencer gratuitement](https://2pm.space/signup)

## Jeu de données, entraînement, agent

Trois étapes, toutes dans l’espace de travail où le modèle travaillera.

1. **Constituez un jeu de données** — Choisissez un jeu de données d’entraînement dans une conversation de la boîte de réception, puis mettez un 👍 aux réponses de l’IA à garder et améliorez celles qui ont manqué leur cible. Chaque paire attend votre Inclure ou Exclure avant que quoi que ce soit parte à l’entraînement.
2. **Choisissez une base et entraînez** — Choisissez un modèle de base open-weight, consultez le coût estimé une fois le jeu de données exporté, gardez les hyperparamètres par défaut ou modifiez-les, et lancez l’exécution.
3. **Branchez un agent dessus** — L’adaptateur terminé apparaît dans le sélecteur Modèle d’un agent, sous My Adapters. Branchez-y un agent, rejouez de vrais messages clients avec cet agent via « Run with… » dans la boîte de réception, et gardez celui qui répond le mieux.

## Le fine-tuning sans stack à part

Pas de console fournisseur, pas de capacité réservée, pas de contrat — le même solde de crédit que tout le reste.

### Entraînez sur des réponses déjà relues

Les paires d’entraînement viennent de votre boîte de réception : les réponses de l’IA que vous avez notées 👍, les corrections écrites quand une réponse a manqué sa cible, les épisodes bien notés de la mémoire de l’agent, et les Q&R que vous ajoutez — plutôt que des exemples inventés pour qu’un modèle les imite.

### Un modèle plus petit qui se tient

Une fois le ton et le vocabulaire intégrés aux poids, ils ne vous coûtent plus de tokens de prompt à chaque appel — ce qui signifie souvent un modèle plus petit et plus rapide pour un travail qui en exigeait un grand.

### Estimé avant de commencer

Une fois le jeu de données exporté, la fenêtre d’entraînement affiche le coût estimé et le nombre de tokens d’entraînement avant le lancement. L’exécution est débitée à la fin, sur le même solde de crédit que tout le reste — ni contrat séparé, ni capacité réservée.

### Un menu déroulant, pas une migration

Un adaptateur terminé apparaît comme un modèle que vos agents peuvent sélectionner, à côté des fournisseurs hébergés. Branchez un agent dessus, comparez, et gardez celui qui répond le mieux.

### Des tâches que vous pouvez suivre

Jeux de données, entraînements et adaptateurs terminés ont chacun leur propre liste, avec l’état, le modèle de base et le coût de chaque entraînement bien visibles plutôt qu’enfouis dans une console fournisseur.

### Une autorisation à part

Les données d’entraînement sont faites de vraies conversations clients : toute cette partie porte donc sa propre autorisation — liste des candidates comprise — distincte du reste de l’espace de travail.

## Ce que le pipeline prend en charge

Des conversations qui entrent jusqu’à l’adaptateur qu’appellent vos agents.

### Jeux de données

- Construits à partir des réponses de l’IA notées et corrigées dans la boîte de réception
- Chaque paire candidate attend un Inclure ou Exclure avant l’export
- Une vue détaillée du jeu de données montrant ce qui sera entraîné
- Réutilisables pour plusieurs entraînements

### Modèles de base

- Familles open-weight : Llama, Qwen, Mistral et Mixtral
- Distillations DeepSeek R1 et gpt-oss
- Nombre de paramètres affiché pour chaque modèle
- Coût estimé affiché une fois le jeu de données exporté
- Une liste sélectionnée de bases que le fournisseur d’entraînement sait affiner

### Entraînements

- Adaptateurs LoRA, avec des valeurs par défaut raisonnables pour chaque hyperparamètre
- État et historique de chaque entraînement
- Coût enregistré sur l’entraînement
- Échecs signalés, pas relancés en silence indéfiniment

### Mise en service

- Les adaptateurs apparaissent comme un fournisseur de modèles dans le sélecteur d’agent
- Facturés au tarif d’inférence du modèle de base, multiplié par le coefficient premium de l’adaptateur
- Utilisables par tous les agents de l’espace de travail
- Interchangeables par agent, par nœud

### Contrôle

- Sa propre clé d’autorisation, avec l’entraînement comme action distincte
- Conversations candidates protégées par la même clé
- Numéros de téléphone et e-mails retirés avant l’envoi du JSONL au fournisseur d’entraînement, Together AI
- Jamais mutualisés, ni utilisés pour entraîner quoi que ce soit d’autre

### Coût

- Le même solde de crédit que le reste de la plateforme
- Pas d’abonnement, pas de facturation par siège
- Estimation affichée avant l’exécution, coût réel débité après

## Ce que change un modèle affiné

Là où partent réellement le coût et l’incohérence.

| Sans 2pm.space | Avec 2pm.space |
| --- | --- |
| Un prompt système de 2 000 tokens qui réexplique votre ton à chaque appel | Le ton et le vocabulaire dans les poids, payés une seule fois |
| Se rabattre sur le plus gros modèle parce que le petit ne respecte pas la marque | Un petit modèle affiné qui se tient, pour une fraction du coût par appel |
| Rédiger des exemples d’entraînement synthétiques pour un domaine dont vous avez déjà les transcriptions | Un jeu de données construit à partir des réponses de l’IA que vous avez déjà notées et corrigées |
| Entraîner dans une console fournisseur, coupée de l’endroit où le modèle est utilisé | Jeu de données, entraînement et adaptateur en service dans le même espace de travail que les agents |

## Questions sur le fine-tuning

Ce que les équipes vérifient avant d’entraîner sur des conversations clients.

### Qu’apporte le fine-tuning qu’un bon prompt n’apporte pas ?

Un prompt dit à un modèle quoi faire ; un fine-tuning lui apprend comment vous le faites. Une fois le ton, le vocabulaire produit et la forme d’une bonne réponse intégrés aux poids, vous cessez de les payer dans chaque prompt — ce qui signifie souvent un modèle plus petit, moins cher et plus rapide pour un travail qui exigeait jusque-là un grand modèle.

### D’où viennent les données d’entraînement ?

De votre boîte de réception. Choisissez un jeu de données d’entraînement dans les paramètres d’une conversation, puis notez les réponses de l’agent — un 👍 fait d’une réponse une candidate — et utilisez Améliorer pour écrire ce que la réponse aurait dû être ; cette correction devient elle aussi une paire d’entraînement. Les épisodes que la mémoire de l’agent note 8 sur 10 ou plus peuvent être ajoutés automatiquement, et vous pouvez ajouter des Q&R à la main. Les réponses écrites par votre équipe ne sont pas collectées. Chaque paire attend votre Inclure avant d’être exportée, et comme ce sont de vrais messages de clients, toute la surface est protégée par une permission distincte du reste de l’espace de travail.

### Quels modèles de base puis-je entraîner ?

Uniquement des modèles open-weight, car un modèle hébergé comme Claude ou GPT ne peut pas être affiné avec LoRA. La liste est une sélection de modèles que le fournisseur d’entraînement sait affiner — Llama, Qwen, Mistral, Mixtral, distillations DeepSeek R1 et gpt-oss, de 1B à 120B paramètres — chacun affiché avec son nombre de paramètres.

### Combien ça coûte ?

L’entraînement est mesuré par million de tokens au tarif du modèle de base, avec le minimum par exécution du fournisseur, et la fenêtre d’entraînement affiche l’estimation une fois le jeu de données exporté. L’exécution est débitée à la fin, sur le même solde de crédit que tout le reste. Une fois entraîné, un adaptateur est facturé au tarif d’inférence de son modèle de base multiplié par son coefficient premium. Pas d’abonnement ni de facturation par siège — consultez la page Tarifs pour comprendre la facturation à l’usage.

### Comment utiliser un modèle entraîné ?

Il apparaît dans la liste Modèle de vos agents, sous My Adapters, à côté des fournisseurs hébergés. Branchez-y un agent, rejouez de vrais messages clients via « Run with… » dans la boîte de réception, et gardez celui qui répond le mieux — le changement se fait dans une liste, pas par une migration.

### Mes données d’entraînement servent-elles à entraîner autre chose ?

Non. Un jeu de données constitué dans votre espace de travail entraîne un adaptateur qui appartient à votre espace de travail, et la plateforme ne le mutualise ni ne le partage avec d’autres espaces. Pour l’entraînement, le JSONL exporté — débarrassé des numéros de téléphone et des e-mails — est envoyé au fournisseur d’entraînement, Together AI, qui exécute l’affinage et sert l’adaptateur appelé par vos agents.

## Entraînez un modèle qui parle déjà comme vous

Constituez un jeu de données à partir des réponses que votre agent a déjà données. Gratuit pour commencer — l’entraînement est débité de votre solde de crédit à la fin de l’exécution.

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
