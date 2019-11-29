# torsion-point-elliptic-curve
Script PARI/GP qui permet de calculer l'ensemble des points de torsions rationnel d'une courbe elliptique E/Q.
contient toutes les fonctions necessaires pour calculer les points rationnels d'ordre fini sur une courbe elliptique E.\n
* Pour representer la courbe elliptique E : y^2 = x^3 + ax + b, on ecrit E = [a,b].
* Les points sur une courbes ellitiques correspondent a une liste de deux element P = [x,y]
* Le point a l'infinie d'une courbe elliptique est représenter par oo.

Voici la liste des fonctions dans ce fichier :\n
* polrootsrat(f) : Retourne les racines rationnelles d'un polyneme a coefficient entier
* elldbl(E, P) : retourne le point 2P
* ellptadd(E,P,Q) : retourne le point P+Q
* ellmultbyN(E, P, N) : retourne le point NP
* order(E, P) : retourne l'ordre de P
* elltorsion(E) : retourne une liste contenant tous les points de torsion rationnel de E avec leur ordre respectif.
