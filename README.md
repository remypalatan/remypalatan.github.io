# Site CV — Rémy Palatan

Site statique d'une seule page, pensé pour un hébergement gratuit sur GitHub Pages.

## Contenu

- `index.html`, la page du CV, autonome, HTML et CSS dans un seul fichier.

## Mettre en ligne sur GitHub Pages

1. Créer un dépôt sur GitHub, par exemple `cv` ou `remypalatan.github.io`.
2. Lier ce dossier au dépôt distant, puis pousser.
   ```
   git remote add origin https://github.com/<ton-identifiant>/<nom-du-depot>.git
   git branch -M main
   git push -u origin main
   ```
3. Sur GitHub, onglet Settings, puis Pages, choisir la branche `main` et le dossier racine.
4. Le site est servi à l'adresse indiquée par GitHub.

Si le dépôt s'appelle `<ton-identifiant>.github.io`, le site est servi directement à cette adresse.

## À compléter dans `index.html`

- l'adresse de contact et le lien GitHub en en-tête
- la ligne des langues dans la section Compétences
- toute rubrique à ajouter, enseignements, communications, prix
