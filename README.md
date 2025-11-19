# AMADE-PELCODE — Jekyll site (GitHub Pages ready)

Contenu prêt pour GitHub : pages, assets, workflow d'automatisation pour construire et déployer le site sur GitHub Pages.

## Étapes rapides pour publier
1. Créez un nouveau dépôt GitHub (par ex. `AMADE-PELCODE-website`).  
2. Poussez le contenu de ce dossier sur la branche **main**.
3. La GitHub Action `Build and deploy Jekyll site to GitHub Pages` (fichier `.github/workflows/pages.yml`) s'exécutera automatiquement pour construire le site et le déployer sur GitHub Pages.

Après le premier push, allez dans *Settings → Pages* pour vérifier l'URL du site.

## Chemin local du document fourni (inclus dans assets)
- `/mnt/data/Présentation ONG AMADE-PELCODE (3).docx`

## Prévisualiser localement
1. Installer Ruby & Jekyll (https://jekyllrb.com/docs/installation/)
2. `bundle install`
3. `bundle exec jekyll serve`
4. Ouvrir `http://localhost:4000`

## Remarques
- Modifiez `_config.yml` > `url` pour mettre l'URL GitHub Pages de votre site, si vous le souhaitez.
- Pour activer les formulaires (contact, dons), utilisez Formspree, Netlify Forms, ou intégrez Stripe/PayPal.
