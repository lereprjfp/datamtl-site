# datamtl.com

Site vitrine de DataMtl — page unique, bilingue FR/EN, HTML/CSS/JS sans dépendances, sans traceurs.

- `index.html` — tout le site (styles, contenu FR dans le balisage, dictionnaire FR/EN dans le script)
- `CNAME`, `robots.txt`, `sitemap.xml`, `site.webmanifest`, `favicon.svg`
- Image OG servie depuis `datamtl.github.io/datamtl-assets/og-datamtl.png`

## Déploiement
GitHub Pages (branche `main`, racine) derrière Cloudflare. Aucune étape de build.

## Modifier le texte
Chaque élément traduit porte un `data-i18n="clé"`. Modifier la valeur dans `I18N.fr` **et** `I18N.en` (le balisage FR sert de secours). La langue par défaut est FR; `?lang=en` force l'anglais.

## Formulaire
Envoi via Web3Forms (clé `WEB3FORMS_KEY` dans le script, destinataire configuré côté Web3Forms : info@datamtl.com). Honeypot anti-bot inclus.
