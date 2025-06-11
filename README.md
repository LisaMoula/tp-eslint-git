Vérifications & preuves d’exécution

1. Hook Husky (pré-commit)

Tout commit contenant des erreurs ESLint est bloqué.

[Error] ESLint failed. Commit aborted

2. Correctif automatique ESLint

Lancement de npx eslint --fix . : toutes les erreurs sont corrigées.

Afin d’autoriser console.log sans avertissement, la règle a été désactivée :

"no-console": "off"

3. Validation GitHub Actions

Le workflow CI se déclenche automatiquement à chaque push ou pull request.

Tableau de bord : tp-eslint-git → Actions

Dernier statut : OK

