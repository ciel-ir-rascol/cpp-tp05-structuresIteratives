# TP04 - Structures sélectives
**STS 1CIEL** - TP sur l'utilisation des différentes structures itératives vues en cours : `for`, `while`, `do while`.

Ce repository est un projet CLion dans lequel vous trouverez un certain nombre de fichiers `.cpp` qui vont vous permettre de coder chaque exercice demandé. Une fois terminé il suffira de faire un commit, puis un push vers GitHub afin de rendre votre travail.


## Exo1 - Somme des entiers pairs
Développez un code C++ qui demande à l'utilisateur de saisir un entier `max`. Le programme calculera la somme des entiers pairs en partant de 0 jusqu'à `max` compris, si il est pair. Vous afficherez cette somme à l'écran.

▶︎ Pour réaliser cet exo vous utiliserez une boucle `for`.

## Exo2 - Divisibilité
Nous donnons un vecteur d'entiers `vec`, vous devrez parcourir ce vecteur afin de compter le nombre d'éléments divisibles par 3 ou par 5. Vous stockerez ce nombre dans une variable `cpt`. Vous afficherez `cpt` à l'écran.

▶︎ Pour réaliser cet exo vous utiliserez une boucle `for` **range-based**.

## Exo3 - Calculatrice bis
Nous reprenons l'exercice de la calculatrice du TP03 dans lequel on propose à l'utilisateur de rentrer un opérateur puis 2 opérandes avant d'afficher le résultat. Cette fois-ci nous demanderons à l'utilisateur s'il souhaite faire un autre calcul avant de quitter le programme. L'utilisateur pourra recommencer des calculs indéfiniment.

▶︎ Pour reboucler sur le menu principal si l'utilisateur souhaite poursuivre, vous utiliserez une boucle `while` ou `do while`

## Exo4 - Factorielle
La factorielle d’un nombre est le produit de tous les entiers à partir de 1 jusqu’à ce nombre. La factorielle peut seulement être définie pour des entiers positifs.
La factorielle d’un nombre négatif n’existe pas et la factorielle de 0 est 1.

Par exemple : <br>
La factorielle de 5 est définie par l’expression mathématique 5! et vaut :
```text
5! = 1x2x3x4x5 = 120
```

Créez un programme qui demande à l’utilisateur de saisir un entier n , qui vérifiera si `n>=0` et calculera sa factorielle, **dans le cas contraire un message d’erreur sera affiché et il sera demandé à l’utilisateur de saisir un nouveau nombre**. Le résultat du calcul sera affiché sur la console.

## Exo5 - Suite de Fibonacci
On considère la suite de nombres entiers dont les deux premiers termes sont :
```text
F0=1 F1=1
```
Les termes suivants de cette suite sont construits de la manière suivante :
```text
Fn = Fn-1 + Fn-2
```
Écrire un code qui à partir d’un entier `n>=0` affiche le n-ième terme de la suite.

Par exemple selon la valeur de n :

|n|n-ième terme <br>de la suite|
|:---:|:---:|
|1|1|
|2|1|
|3|2|
|4|3|
|5|5|
|6|8|
|7|13|
|8|21|

## Exo6 - Enclos à chèvres
Nous souhaitons créer un programme qui affiche à l’écran un carré de `o` formant un enclos de côté `n`. Nous donnons ci-dessous un exemple pour `n=5` :
```text
o o o o o
o       o
o       o
o       o
o o o o o
```
Nous demanderons à l'utilisateur la valeur de `n` souhaitée, il pourra après affichage saisir une nouvelle valeur ou bien quitter le programme.
