# Journal des versions de Noah

Noah est le coach formateur de l'équipe, conçu par Devlogy. Chaque version part de l'instance zéro (Devlogy) et rejoint les instances des clients quand leur admin l'applique.

## 2.3.0 — Des sources discrètes

*2026-10-30 · Mineure · touche : Interface*

Les sources consultées se replient en une ligne discrète, « 5 sources consultées », toujours en bas de la réponse. Un clic les déplie en une liste de liens. Même présentation dans les articles des Actualités.

### Pour l'équipe

**Mes sources se font discrètes.** Elles tiennent sur une ligne en bas de ma réponse, « 5 sources consultées » : un clic la déplie pour voir les liens.

- **Plus de confusion** avec les réponses à choisir au-dessus du champ de saisie.
- **Même présentation dans les articles** des Actualités.

### Pour l'admin

Rien à faire : la mise à jour ne touche que l'affichage. Les exports Word et PDF gardent la liste complète des sources en fin de document.

## 2.2.0 — Le quiz de positionnement

*2026-10-30 · Recommandée · touche : Interface, Prompt*

Le quiz de positionnement devient une étape de la méthode de Noah : cinq questions avant le plan, notées par l'app. Le niveau de départ reste en mémoire pendant toute la formation, et la progression apparaît sur l'attestation.

### Pour l'équipe

**Je mesure d'abord où tu en es.** Avant de te proposer le plan, je te fais passer un court quiz de positionnement : cinq questions, une à la fois.

- **Ton plan est calibré sur le résultat** : on passe vite sur ce que tu sais déjà, on insiste sur le reste.
- **Ton niveau de départ reste affiché** dans le volet de ta formation.
- **Ton attestation montre ta progression**, du quiz de départ au dernier quiz.

### Pour l'admin

Le tableau de bord montre, par formation, le niveau moyen au départ et à la fin. Un pré-prompt peut exclure le quiz (« pas de quiz de positionnement ») ou le préciser (nombre de questions, questions pièges, moment).

## 2.1.0 — Une question à la fois

*2026-10-30 · Recommandée · touche : Interface, Prompt*

Noah suit son parcours : au plus une question par message, des réponses proposées au-dessus du champ de saisie, des quiz pas à pas, et plus de pistes de relance qui dispersent.

### Pour l'équipe

**Je pose mes questions une par une.** Tu choisis ta réponse d'un clic, juste au-dessus du champ de saisie, ou tu écris la tienne.

- **Les quiz défilent une question à la fois**, avec la correction après chaque réponse, puis ton score.
- **Je reste sur notre parcours** : plus de pistes de relance en fin de message, on avance selon le plan validé.

### Pour l'admin

Rien à faire : la mise à jour ne touche ni les formations, ni le catalogue, ni les données de l'équipe. Si l'annexe technique a été personnalisée (Admin → Configuration), la remettre à l'original pour profiter des nouvelles consignes.

## 2.0.0 — Noah passe sur Claude

*2026-10-30 · Majeure · touche : Interface, Prompt, Base de données, Tâches planifiées*

Première version de Noah sur Claude, construite avec le kit des employés digitaux Devlogy. Le prompt du GPT est gardé au plus près ; une formation reste un pré-prompt.

### Pour l'équipe

**Je suis Coach Noah 2.0, et je passe sur Claude.** Quand j'apprends quelque chose de nouveau, je te le dis ici, dans un article « Nouveau chez Noah ».

Ce que tu as dans cette version :

- **Des formations sur mesure.** Choisis une formation du catalogue, ou écris la tienne, comme avec le GPT.
- **Seul ou en groupe.** Sur un même écran, je m'adresse à chacun par son prénom.
- **Un plan que tu valides.** Je le prépare avec toi, tu le valides d'un clic, et je m'y tiens à chaque séance.
- **Des séances courtes.** Explications, pratique, quiz et récap, puis la date de la séance suivante.
- **Tes supports, relus.** PDF, Word, PowerPoint, tableurs : je les relis à chaque séance.
- **Ton attestation** à la fin de la formation, et des rappels les jours de tes séances.

### Pour l'admin

- **Admin → Formations** : le catalogue de l'équipe. On y importe les formations du Catalogue Devlogy ou on écrit les siennes ; chaque formation est un pré-prompt, avec des variables remplies au lancement ({{ORG}}, {{APPRENANT}}, {{DATE_DEBUT}}, {{GROUPE}}).
- **Admin → Supports** : les documents que Noah relit pendant les formations, rattachés ou non à une formation.
- **Tableau de bord** : inscriptions, séances faites et prévues, scores des quiz, par formation ; jamais le contenu des échanges.
