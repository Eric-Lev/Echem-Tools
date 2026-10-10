# Site Echem-Tools — mise en ligne sur GitHub Pages

Un seul site pour les trois logiciels : une page d'accueil, puis une page par
logiciel, chacune en anglais et en français.

## Contenu
- `index.html` / `fr/index.html` : l'accueil (les trois logiciels, gratuité et inscription, rubrique « Données » commune)
- `cvsim/`, `datafit/`, `secplot/` : une page par logiciel (`fr/` pour le français)
- `assets/` : feuille de style (une couleur par logiciel), polices, script
- `docs/` : les trois licences d'utilisation (versions validées par les tutelles) et les plaquettes de CVSim
- `images/` : illustrations, captures, icônes

## Ce que le site contient de lui-même
- Les deux polices (Source Sans 3, Source Serif 4, licence SIL OFL 1.1) sont servies par le site : aucune requête vers Google Fonts.
- Aucun cookie, aucune mesure d'audience, rien chargé depuis un autre site.

## Mise en ligne
1. Sur GitHub : **New repository**, nom `echem-tools`, **Public**, puis *Create repository*.
2. *uploading an existing file* : glisser **le contenu** du dossier (pas le dossier lui-même), en gardant tous les sous-dossiers. *Commit changes*.
3. **Settings > Pages** : *Source* = *Deploy from a branch*, branche `main`, dossier `/ (root)`, *Save*.
4. Après une à deux minutes : `https://<votre-compte>.github.io/echem-tools/` ; CVSim à `.../echem-tools/cvsim/`, DataFit à `.../datafit/`, SECPlot à `.../secplot/` (français : ajouter `fr/`).

Mise à jour : déposer le fichier modifié au même endroit (*Add file > Upload files*), le site se met à jour seul.
