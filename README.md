# StarCraft TMG – Outils de jeu

Outils web non officiels pour **StarCraft: Tabletop Miniatures Game** (Archon Studio).

| Application | Dossier | Rôle |
|---|---|---|
| Builder de listes | `builder/` | Construire une armée avec les coûts officiels, gérer sa collection, exporter en PDF/PNG ou pour l’aide de jeu. |
| Aide de jeu | `aide-de-jeu/` | Console de partie : rounds, phases, supply, PV, logigramme d’activation, résolution des attaques. |
| Règles en images | `regles-en-images/` | Dix planches illustrées des règles, vérifiées sur le livre de règles. |

La page `index.html` à la racine permet de choisir l’application.

## Mise en ligne avec GitHub Pages

1. Pousser le contenu de ce dossier à la racine du dépôt (branche `main`).
2. Dans le dépôt : **Settings → Pages → Build and deployment → Source : Deploy from a branch**, branche `main`, dossier `/ (root)`.
3. Le site est disponible à `https://<utilisateur>.github.io/<dépôt>/`.

Chaque application est un fichier HTML autonome (aucune compilation). Les données (base de cartes, missions, glossaire) sont intégrées dans les pages ; `StarCraft-TMG-Database.json` est la même base, fournie à part.

Les parties en cours et les réglages sont enregistrés dans le navigateur (localStorage).

StarCraft est une marque de Blizzard Entertainment. Projet de fan, sans lien avec Blizzard ni Archon Studio.
