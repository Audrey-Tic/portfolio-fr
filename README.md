# portfolio-fr — Audrey Tichit

Copie autonome du portfolio français d’origine, avec la présentation de `portfolio-EN` (dossier local `portfolio-v2`) : bleu marine et doré, portrait détouré, cartes et boutons arrondis.

Le contenu français, les expériences, les filtres, les missions détaillées, les certifications, les loisirs interactifs et les crédits sont conservés.

## Ouvrir le portfolio

Ouvrir `index.html` directement dans un navigateur, ou lancer `npm run dev` depuis ce dossier et consulter http://localhost:4176. Aucune installation nécessaire ; Node.js 20 ou supérieur suffit pour le serveur local. Arrêter avec Ctrl+C.

`npm run check` vérifie la syntaxe JavaScript.

## Modifier le portfolio

- `index.html` : contenu français et rubriques.
- `experiences.js` : expériences professionnelles et bénévolat.
- `app.js` : filtres, navigation et interactions.
- `styles.css`, `theme.css`, `visual-theme.css` : présentation reprise de portfolio-EN.
- `assets/` : portrait, logos et illustrations locaux.

Cette copie fonctionne indépendamment des autres versions. La consigne de non-indexation est conservée.

## Publication GitHub Pages

- Dépôt : https://github.com/Audrey-Tic/portfolio-fr
- Site : https://audrey-tic.github.io/portfolio-fr/

Chaque push sur `main` lance la vérification JavaScript et la publication GitHub Pages avec le workflow `.github/workflows/deploy-pages.yml`. Seuls la page, ses feuilles de style, ses scripts et le dossier `assets` sont publiés.
