# TP 1 : Premier projet Angular 22 avec Tailwind CSS

## Environnement
- Node.js v22.22.3 (installé avec nvm), npm 10.9.8
- Angular CLI 22.2.0
- Éditeur : Visual Studio Code


## Création du projet
```bash
ng new my-first-app
cd my-first-app
ng serve
```
Application disponible sur http://localhost:4200.

**Git :** un dépôt parasite existait dans `C:\Users\ASUS`. J'ai fait `git init -b main` dans le projet, puis `git push` vers GitHub.

## Arborescence
- `src/app/` : composants, services et routes de l'application
- `src/styles.css` : styles globaux (Tailwind y est importé)
- `src/index.html` : page HTML unique, contient `<app-root>`
- `src/main.ts` : point d'entrée qui démarre l'application
- `angular.json` : configuration du workspace (build, serve, styles)
- `package.json` : dépendances et scripts npm

## Tailwind CSS
1. `npm install tailwindcss @tailwindcss/postcss postcss`
2. Fichier `.postcssrc.json` avec le plugin `@tailwindcss/postcss`
3. `@import 'tailwindcss';` dans `src/styles.css`
4. Page avec titre et carte dans `src/app/app.html`

