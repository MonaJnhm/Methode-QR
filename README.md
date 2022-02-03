# Methode-QR

Dans ce projet, nous avons cherché à trouver les valeurs propres et les vecteurs propres d'une
matrice symétrique. Pour cela, nous avons utilisé plusieurs fois le principe de la décomposition QR
avec la méthode de Householder.

Ci joint dans le dossier: 

--PDF correspondant au sujet du projet06.
--Makefile
--Programme Fortran QR.f
--Programme Matlab/octave QR.m
--fichiers tests (hil.txt, test.txt)
--Rapport rapport-projet6.pdf
--aareadme

[MéthodeQR-Fortran&Matlab.zip](https://github.com/MonaJnhm/Methode-QR/files/7996896/MethodeQR-Fortran.Matlab.zip)

Le programme QR.f demande à la saisie 
--la taille de la matrice carré
-- O si l'utilisateur veut faire tourner le programme avec une matrice qu'il rentre ou 1 (autre que 0) pour la matrice d'Hilbert, qui sera alors calculée par le programme.

Le programme renvoie 
--La matrice A rentrée par l'utilisateur
--Les valeurs propres de cette dernière
--Les vecteurs propres, chaque colonne correspond à chaque valeur propre.

Le fichier test.txt permet de tester la matrice du sujet, et hil.txt avec une matrice de Hilbert de taille 4*4.

En commentaire, nous avons laissé la vérification des vecteurs en effectuant A*X=lambda*X
