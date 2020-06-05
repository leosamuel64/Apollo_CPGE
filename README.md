# Apollo - Ocaml Extension

Extension inspirée de  : https://gitlab.com/otumn/hermes-ocaml.git

Version adaptée au programme d'Option Informatique de Maths Sup/Spé.

Permet d'avoir l'**autocompletion** et les **raccourcis** pour Ocaml.

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
 **Boucles** |
 `for` | Crée un for i=? to ? do ... done;
 `forArray`, `fa` | Crée un for i=0 to (Array.length ?-1) do ... done;
 `while` | Crée un while ? do ... done;
 **Arbres** |
 `treeInit`, `arbre_bin` | Crée un type d'arbre binaire générique avec un arbre de test
 `tree-n`, `arbre_naire` | Crée un type d'arbre n-aire générique avec un arbre de test et les getters
 `matchTreeBin`| Crée un match pour un arbre Binaire
 **Listes** | 
 `left`, `fold_left` | Un List.map generique
 `right`, `fold_right` | Un List.fold_left generique
 `map`,`List.map` | Un List.map generique
 `iter`, `List.filter` | Un List.iter generique
 `List.filter` | Garde dans la liste les éléments compatible avec le prédicat
 `List.mem` | Teste si l'élément est présent dans la liste
 **Piles** | 
 `Stack.create`, `sc` | Ajoute Stack.create classique
 `Stack.push`, `spu` | Un Stack.push classique
 `Stack.pop`, `spo` | Un Stack.pop classique
 `Stack.is_empty`, `sie` | Un Stack.is_empty classique
  **File** | 
 `Queue.create` | Ajoute Queue.create classique
 `Queue.add` | Un Queue.add classique
 `Queue.take` | Un Queue.take classique
 `Queue.is_empty` | Un Queue.is_empty classique
  **Hashtbl** | 
 `Hashtbl.create` | Créer une table de hashage d'une certaine longueur
 `Hashtbl.add` | Ajoute un élément dans le dico
 `Hashtbl.take` | Retourne la valeur associé à la clef
 `Hashtbl.is_empty` | Teste si une clef est présente dans un dico
 `Hashtbl.remove` | Enlève une clef du dico

