==>Description
Ce projet en C++ implémente une classe `Matrix` pour effectuer des opérations matricielles de base 
telles que l'addition, la soustraction, la multiplication et la comparaison de matrices. Il inclut également 
un programme principal avec un menu interactif pour sélectionner et exécuter ces opérations.

==>Fichiers
- main.cpp : Contient le programme principal avec un menu pour interagir avec l'utilisateur.
- Matrix.cpp : Contient les implémentations des méthodes de la classe `Matrix`.
- Matrix.h : Contient la définition de la classe `Matrix`.

==>Fonctionnalités
- Addition de matrices
- Soustraction de matrices
- Multiplication de matrices
- Comparaison de matrices (égalité, inégalité, supérieur, inférieur)

==>Instructions
1. Compiler le programme:
   
    => g++ main.cpp Matrix.cpp -o matrix_program
  
2. Exécuter le programme:
 
    => ./matrix_program
  

==>Utilisation
1. Lancez le programme.
2. Choisissez une opération dans le menu :
   - 1: Addition
   - 2: Soustraction
   - 3: Multiplication
   - 4: Comparaison
   - 5: Fermer le programme
   - 6: Utiliser le résultat précédent (si disponible)
3. Suivez les instructions pour entrer les dimensions et les éléments des matrices.
4. Le résultat de l'opération sera affiché à l'écran.

==> Exemple
                       OPERATIONS SUR MATRICES
                ========================================
                          ****** MENU ******
                ========================================
                1. Addition             2. Soustraction
                3. Multiplication       4. Comparaison
                5. Fermer
     ---------------------------------------------------------------------
  => Choisissez une operation: 1 Entrer les dimensions de la premiere matrice (lignes colonnes): 3 3
  =>Entrer les elements de la matrice (3x3):
2 3 4
9 0 0
1 3 2
 =>Entrer les dimensions de la deuxieme matrice (lignes colonnes): 3 3
 =>Entrer les elements de la matrice (3x3):
4 1 3
7 8 1
0 1 5
        Resultat de l'addition:
6  4  7
16 8  1
1  4  7
