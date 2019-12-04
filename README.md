# torsion-points-elliptic-curve
Script PARI/GP qui permet de calculer l'ensemble des points de torsions rationnel d'une courbe elliptique E/Q.

* Pour representer la courbe elliptique E : y^2 = x^3 + ax + b, on écrit E = [a,b].
* Les points sur une courbes ellitiques correspondent à une liste de deux elements P = [x,y]
* Le point à l'infinie d'une courbe elliptique est représenté par oo (double "o").

Voici la liste des fonctions dans le fichier torsion.gp :
* polrootsrat(f) : Retourne les racines rationnelles d'un polyneme à coefficient entier
* elldbl(E, P) : retourne le point 2P
* ellptadd(E,P,Q) : retourne le point P+Q
* ellmultbyN(E, P, N) : retourne le point NP
* order(E, P) : retourne l'ordre de P
* elltorsion(E) : retourne une liste contenant tous les points de torsion rationnel de E avec leur ordre respectif.

Pour obtenir de l'aide sur une fonction, après avoir importé le script torsion.gp, il suffit d'écrire <? nom-de-la-fonction>.
