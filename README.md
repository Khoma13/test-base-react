# Petite explication (toute petite hein, en vocal ça sera mieux) et petits tests voir si tout fonctionne chez vous

* Toutes les dépendances sont contenus dans package.json normalement besoin de rien installer (à part yarn, il suffit juste de suivre l'installation en dessous)
* L'ensemble de l'application est contenu dans app/src/index.js
* Le message `Hello World` vient de app/src/components/App/index.js
* Le style de ce message vient de app.styl du même dossier
* La variable `$testcolor` provient de app/styles/style.styl
* Si vous pouvez modifier la couleur ou le texte, et que rien n'est affiché en console, tout fonctionne. (pour le texte `coucou`, c'est normal si vous trouvez pas)

# Installation

* Dans la console:
* Installer Yarn: `npm install yarn`

* Dans la console à la racine du projet:
* Installer les dépendances : `yarn`
* Lancer le serveur : `yarn start`
* Dans le navigateur : `http://localhost:3333`
* Arrêter le serveur: `ctrl c`

## Package Atom utiles

* Stylus
* language-babel
