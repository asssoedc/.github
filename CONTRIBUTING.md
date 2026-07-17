# Comment contribuer

Merci de vouloir contribuer à un projet de l'association !

## Avant de commencer

- Vérifie qu'une issue n'existe pas déjà pour ce que tu veux faire
- Si tu ajoutes une fonctionnalité importante, ouvre une issue avant de coder pour en discuter

## Workflow

- `main` : code en production, toujours stable
- Toute modification passe par une branche dédiée, jamais de push direct sur `main`

### Nomenclature des branches

| Préfixe | Usage | Exemple |
|---|---|---|
| `feature/` | Nouvelle fonctionnalité | `feature/formulaire-adhesion` |
| `fix/` | Correction de bug | `fix/erreur-envoi-email` |
| `hotfix/` | Correctif urgent à déployer rapidement en production | `hotfix/faille-connexion` |
| `docs/` | Modification de documentation uniquement | `docs/maj-readme-installation` |
| `chore/` | Maintenance (dépendances, configuration, nettoyage) | `chore/maj-dependances` |

Règles :
- Minuscules, mots séparés par des tirets (`-`), pas d'espaces ni d'accents
- Nom court mais explicite (2 à 4 mots)
- Toujours créée à partir de `main` à jour (`git pull` avant de créer la branche)
- Supprimée après le merge de la pull request associée

### Étapes

1. Crée ta branche selon la nomenclature ci-dessus
2. Fais tes modifications avec des commits clairs et atomiques
3. Ouvre une pull request vers `main` en remplissant le template
4. Attends une revue avant de merger (même seul, ça laisse une trace des décisions)

## Convention de commits

Format recommandé : `type: description courte`

Exemples :
- `fix: corrige l'affichage du formulaire de contact`
- `feat: ajoute la page adhésion`
- `docs: met à jour le README`


