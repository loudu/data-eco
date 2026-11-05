# Infos changement climatique

Site statique présentant les chiffres clés du réchauffement climatique, sur trois pages accessibles depuis le menu burger en haut à droite :

- `index.html` : Climat (données France, Monde, Politique)
- `economie.html` : Économie (coût des dégâts, énergies fossiles, investissements, compagnies pétrolières)
- `culture.html` : Culture (cultures agricoles menacées)

Le style commun est dans `style.css` et le comportement du menu dans `menu.js`.

Toutes les données proviennent de sources scientifiques ou officielles, listées en bas de page : GIEC (AR6), OMM, Haut Conseil pour le Climat, Météo-France, Citepa, SDES, Santé publique France et Global Carbon Project.

## Utilisation

Ouvrir `index.html` dans un navigateur. Aucun build n'est nécessaire ; la page peut être hébergée telle quelle (GitHub Pages, Netlify…).

## Mise à jour des chiffres

Les valeurs sont écrites directement dans `index.html`, `economie.html` et `culture.html`. Les publications de référence sont annuelles :

- Météo-France (bilan climatique) : janvier
- Santé publique France (bilan chaleur) : fin d'hiver
- Citepa (rapport Secten) : juin
- Haut Conseil pour le Climat (rapport annuel) : juin-juillet
- SDES (empreinte carbone) : automne
- Global Carbon Project : novembre

Les cartes « Politique » additionnent les émissions annuelles de CO2 fossile (Global Carbon Project) sur les années civiles de chaque mandat.
