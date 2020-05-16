# Hermes, the state-of-the-art extension for oCaml

Add **Snippets** and **KeyBindings** for oCaml.

Permet d'avoir une **autocompletion** et les **raccourcis** assortis pour oCaml.

## Features

### Raccourcis (Shortcuts)

Combinaison | Resultat
---------|----------
 `Alt+N` | Crée un corps de fonction avec le contrat et tests 
 `Alt+C` | Crée un block de commentaires pour les contrats 
 `Alt+B` | Crée un block de trois tests génériques
 `Alt+M, Alt+M` | Un match with générique
 `Alt+M, Alt+L` | Un match with pour les listes
 `Alt+M, Alt+O` | Un match with pour les type option 
 `Alt+L, Alt+M` | Un map generique
 `Alt+F, Alt+G` | Un fold left generique
 `Alt+F, Alt+D` | Un fold right generique

### Autocompletion (Snippets)

Prefix | Resultat
---------|----------
 **Fonctions** | 
 `spec`, `new` | Crée un corps de fonction avec le contrat et tests 
 `cc`, `contrat` | Crée un block de commentaires pour les contrats 
 `btest`, `tests` | Crée un block de trois tests génériques
 `af`, `aux` | Crée une fonction auxiliaire recursive
 `fun`, `(fun)` | Crée une fonction anonyme
 `test`, `let%test` | Crée un test générique
 **Comparateurs** | 
 `if` | Crée un if/then/else générique
 `match` | Un match with générique
 `ml`, `match_list` | Un match with pour les listes
 `mo`, `match_option` | Un match with pour les type option
 **Arbres** |
 `tree`, `arbre_bin` | Crée un type d'arbre binaire générique avec un arbre de test
 `tree-n`, `arbre_naire` | Crée un type d'arbre n-aire générique avec un arbre de test et les getters
 **Listes** | 
 `left`, `fold_left` | Un List.map generique
 `right`, `fold_right` | Un List.fold_left generique
 `map` | Un List.map generique
 `iter` | Un List.iter generique
