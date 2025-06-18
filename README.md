# Calculator App

Une application web de calculatrice simple développée avec [React](https://reactjs.org/) et bootstrappée avec [Create React App](https://github.com/facebook/create-react-app).

## Fonctionnalités

- Addition, soustraction, multiplication et division
- Réinitialisation de l'entrée ou du résultat
- Interface utilisateur simple et responsive

## Prérequis

- [Node.js](https://nodejs.org/) (version 14 ou supérieure recommandée)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

## Installation

Clonez le dépôt puis installez les dépendances :

```sh
git clone <url-du-repo>
cd calculator-app
npm install
```

## Lancement en développement

```sh
npm start
```
L'application sera accessible sur [http://localhost:3000](http://localhost:3000).

## Construction pour la production

```sh
npm run build
```
Le build sera généré dans le dossier `build/`.

## Exécution des tests

```sh
npm test
```
Les tests sont configurés avec [Jest](https://jestjs.io/) et [Testing Library](https://testing-library.com/).

## Structure du projet

```
calculator-app/
├── public/
├── src/
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   ├── index.css
│   ├── reportWebVitals.js
│   ├── setupTests.js
│   └── assets/
└── package.json
```

## Utilisation rapide

1. Saisissez un nombre dans le champ prévu.
2. Cliquez sur l'opération souhaitée (addition, soustraction, multiplication, division).
3. Utilisez les boutons "reset Input" ou "reset result" pour réinitialiser respectivement l'entrée ou le résultat.

## Auteurs

- ABDOULAYE TRAORE — Développeur principal

## Contact

Pour toute question ou suggestion, veuillez ouvrir une issue ou contacter abdoulaye.traore@apna-asso.org

## Améliorations possibles

- Ajout de tests unitaires pour chaque opération
- Gestion des erreurs (ex : division par zéro)
- Amélioration de l’accessibilité et du design