# Word Searcher

Un outil de recherche de mots en français et en anglais, pensé pour jouer plus vite à des jeux comme Word Bomb. Tape une suite de lettres et la liste des mots qui la contiennent s'affiche instantanément, avec tri, filtres et favoris.

Tout tourne dans le navigateur, sans serveur ni installation : un seul fichier HTML et des listes de mots en `.txt`.

## Fonctionnalités

- Recherche instantanée en tapant n'importe où sur la page (pas besoin de cliquer dans un champ)
- Dictionnaire français et anglais
- Plusieurs modes de tri : longueur croissante/décroissante, fréquence, aléatoire
- Mode de tri avancé avec filtres personnalisés (longueur min/max, uniquement voyelles, uniquement consonnes, sans lettres doublées)
- Favoris persistants entre les sessions (stockés dans le navigateur)
- Affichage/masquage des mots composés
- Export des résultats de recherche en fichier `.txt`
- Panneau de statistiques (longueur moyenne, lettres les plus fréquentes, etc.)
- Raccourcis clavier (Echap pour effacer, Ctrl+Retour pour tout effacer)

## Utilisation

1. Ouvre `index.html` dans un navigateur.
2. Choisis une langue (français ou anglais).
3. Choisis un mode de tri.
4. Sélectionne le fichier de dictionnaire correspondant (`wordlist_fr.txt` ou `wordlist_eng.txt`) quand l'application le demande.
5. Tape pour chercher.

Le chargement du dictionnaire se fait via un sélecteur de fichier local : aucune donnée n'est envoyée où que ce soit, tout reste sur ta machine.

## Structure du dépôt

```
.
├── wordbomb_word_searcher.html   # application
├── wordbomb_wordlist_fr.txt      # dictionnaire français
├── wordbomb_wordlist_fr_old.txt  # ancienne version du dictionnaire français
├── wordbomb_wordlist_eng.txt     # dictionnaire anglais
└── README.md
```

## Technologies

HTML, CSS et JavaScript natifs. Aucune dépendance, aucune étape de build.

## Licence

Aucune licence n'est définie pour le moment. Tu peux en ajouter une (MIT par exemple) directement depuis l'interface GitHub lors de la création du dépôt, ou plus tard via un fichier `LICENSE`.
