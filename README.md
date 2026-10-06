# PL — site vitrine

Page d'accueil des outils pédagogiques que je construis pour mes élèves au Cycle d'Orientation : [PL-planif'](https://7nel.github.io/PL-planif/), [PL-lect'](https://7nel.github.io/PL-lect/) et [PL-CPS](https://7nel.github.io/PL-CPS/).

**En ligne :** https://7nel.github.io/PL/

## Structure

```
index.html          accueil : outils, à propos, contact
reflexions.html     page secondaire : les trois textes de réflexion
style.css           styles partagés par les deux pages
icon-*.png          icône du site (onglet, écran d'accueil) en 32, 180 et 512 px
manifest.json       nom et couleurs pour l'ajout à l'écran d'accueil
img/
  lac-valais.jpg     photo du lac de Salanfe (section "À propos")
  pl-planif.jpg      capture de PL-planif' (hero)
  pl-lect.jpg        capture de PL-lect' (carte outil)
  pl-cps.jpg         capture de PL-CPS (carte outil)
fonts/
  atkinson-*.woff2   Atkinson Hyperlegible auto-hébergée (aucun appel à Google Fonts)
```

## Mettre à jour le site

Le site tient en deux pages HTML et une feuille de style, sans dépendance de build : il suffit de modifier `index.html`, `reflexions.html` ou `style.css` directement (dans l'éditeur GitHub en ligne, ou en clonant le dépôt) et de valider (« commit ») sur la branche `main`. GitHub Pages republie automatiquement en une à deux minutes.

## Identité visuelle

Le site applique le système d'identité des outils PL : palette sobre, police [Atkinson Hyperlegible](https://www.brailleinstitute.org/freefont/) (accessibilité renforcée, servie depuis `fonts/`), monogramme PL. Voir le [design system](https://claude.ai/artifact/8Y4yKxJy4C4u5vBcKg4h4Z) pour les tokens complets (couleurs, typographie, espacement).

## Formulaire de contact

Le formulaire utilise [Web3Forms](https://web3forms.com) pour transmettre les messages par e-mail sans exposer d'adresse dans le code source ni afficher de boîte mail publique.

## Licence

Voir [LICENSE](./LICENSE) — tous droits réservés.
