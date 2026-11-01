# SG Palette — variante « Clean Modern »

Site vitrine bilingue (français / arabe) de **SG Palette (SGP) — Société Galgaoui**, fabricant
N°1 de palettes en bois en Tunisie.

Cette variante **« Clean Modern »** adopte un style contemporain de type SaaS/tech :
surfaces claires et aérées, dégradés bleu → cyan → turquoise, grandes surfaces arrondies,
navigation collante translucide (effet verre dépoli) et micro-interactions soignées.

- **Langue principale :** français (`lang="fr"`, `dir="ltr"`), bascule arabe (RTL) gérée en JavaScript.
- **URL en ligne :** https://ghassentimoumi.github.io/sg-palette-modern/

## Structure
- `index.html` — page unique (hero, points forts, produits, galerie, devis en ligne, pourquoi, processus, à propos, contact).
- `css/styles.css` — thème « Clean Modern ».
- `js/` — scripts partagés (préchargeur, i18n, calculateur de devis, révélations au défilement). **Ne pas modifier.**
- `assets/` — logo, favicon et photos de la galerie. **Ne pas modifier.**
- `robots.txt`, `sitemap.xml` — SEO.

## Contrôle qualité
```
node scripts/check.mjs
```
Doit afficher `ISSUES (0)`.
