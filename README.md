# Directives
Contient les directives pour le code, strucutre de projet... pour uniformiser le travail.

### Conventions de programmation :
- Utiliser les extensions **`.cpp`** et **`.hpp`** pour les fichiers C++
- Commenter bien les header file,  le lecteur est interessé par l'interface de classe/structure plus que par les détails d'implémentaton (fichier .cpp)
- Préférence de ne pas dépasser 80 caractères par ligne
- Utiliser tab pour identation, pas des espaces
- Utiliser toujours des accolades pour boucles if else while meme s'il s'agit d'une seule ligne
- Nommer les fonctons avec la notation PascalCase  : ex **`NomFonction`**
- Nommer les classes et structures (struct, enum...)  avec la notation PascalCase  : ex **`NomClasse`**
- Si les fichiers .cpp et .hpp servent à définir une classe, nommer ces fichier avec le meme nom que celui de la classe
- Rajouter le préfixe **`Interface`** pour le nom des classes interfaces et **`Abstract`** pour les classes abstraites
- Pour les variables et les parametres de fonction, utiliser camelCase : **`nomVariable`** et **`nomParametre`**
- Rajouter le prefixe **`g_`** pour les variables globales et **`c_`** pour les constantes globales :**`g_variableGlobale`** et **`c_constanteGlobale`** 
- Pour les variables membres d'une classe , rajouter le préfixe m_ : **`m_nomVariableMembre`**
- Pour les variables statique d'une classe, rajouter le préfixe s_ : **`s_nomVariableMembre`**
- Utiliser **`#pragma once`** au lieu des include guards classiques.
- Eviter les abbréviations dans les noms des variables qui ne sont pas clairs au lecteur externe

    -(Si ca te prend plus que 1-2s de réflexion pour comprendre ton abbrévation, c'est probablement pas un bon nom de variable) 

- Pour le nom des macros, utiliser la notation snake_case en majuscule : **`NOM_MACRO`**
  - Commencer le nom de la macro avec un nom general du software , ensuite le namespace et finalement le nom de la macro : **`EULER_SOLVER_NOM_MACRO`**
