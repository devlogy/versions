# Journal des versions de Noah

Noah est le coach formateur de l'équipe, conçu par Devlogy. Chaque version part de l'instance zéro (Devlogy) et rejoint les instances des clients quand leur admin l'applique.

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
