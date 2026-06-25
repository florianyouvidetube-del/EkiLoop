# EkiLoop — séquenceur musical

## Fichiers
- **index.html** — application complète, autonome (tout le code inliné). Ouvre-le dans un navigateur ou dépose-le sur un hébergeur (GitHub Pages, Netlify…). C'est ce fichier qu'on met en ligne.
- **EkiLoop.dc.html** — le code source (Design Component) : template + logique. C'est le fichier à éditer pour modifier l'app.
- **support.js** — runtime nécessaire pour ouvrir EkiLoop.dc.html directement (doit rester à côté de EkiLoop.dc.html).

## Mettre en ligne (GitHub Pages)
1. Crée un repo GitHub.
2. Dépose `index.html` à la racine.
3. Settings → Pages → branche `main` → Save.
4. L'app est en ligne à `https://<pseudo>.github.io/<repo>/`.

## Modifier l'app
Édite `EkiLoop.dc.html`, puis régénère `index.html` (re-bundle) pour publier la nouvelle version.
