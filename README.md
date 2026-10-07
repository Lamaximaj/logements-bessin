# Occupation des logements, 5 rue du Bessin

Page autonome de suivi : la façade (une fenêtre par logement), l'occupation, les réserves en cours et les rendez-vous de levée des réserves.

Adresse : https://lamaximaj.github.io/logements-bessin/

## Fonctionnement

- Occupation : occupé, attribué, vacant ou à confirmer. Un logement attribué porte la date d'arrivée de l'occupant et s'affiche occupé à partir de ce jour-là, sans nouvelle saisie.
- Les données publiées sont celles écrites dans `index.html` (bloc `<script id="state">`).
- Sur ce site, la page est en consultation : les saisies de chacun restent dans son navigateur et se transmettent avec « Télécharger le tableau » (fichier CSV).
- Le site est public ; la balise `noindex` évite seulement son référencement par les moteurs de recherche.

## Mettre à jour

Remplacer `index.html` par la dernière version enregistrée sur claude.ai, puis pousser sur `main`. GitHub Pages republie la page en une minute environ.

## Publication

GitHub Pages, à activer une fois : **Settings > Pages > Build and deployment > Source : Deploy from a branch**, branche `main`, dossier `/ (root)`.
