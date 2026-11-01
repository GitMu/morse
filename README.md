# Morse à l'oreille

Webapp pour apprendre le code morse à l'écoute, pensée pour le téléphone.

- 10 niveaux de 4 à 5 signes, en commençant par les signes remarquables : éléments identiques (E I S H 5, T M O 0), palindromes (K R P X), puis paires inversées (A/N, D/U, B/V, G/W, F/L, Q/Y) et chiffres miroirs.
- Chaque niveau comporte deux épreuves : signes seuls (20 signes, réussite à 90 %) et groupes de 3 ou 4 signes (10 groupes, réussite à 80 %).
- Espacements du code respectés : point = 1 unité, trait = 3, entre éléments = 1, entre signes = 3, entre mots = 7.
- Réglages : vitesse, tonalité, volume, affichage du code avant la réponse.
- La progression est enregistrée dans le navigateur.

Tout le programme tient dans `morse.html`, sans dépendance. Les fichiers d'icône et `manifest.webmanifest` permettent de l'ajouter à l'écran d'accueil d'un téléphone.

## Utilisation

Ouvrir `morse.html` dans un navigateur, ou activer GitHub Pages (Settings → Pages → branche `main`, dossier racine).
