# Optimisation-par-des-algorithmes-d-heuritstiques
Ce code développé en C++ permet de résoudre des problèmes d'optimisation multi-objectifs

Ce programme est conçu pour résoudre 4 problèmes d'optimisation multi-objectifs :
- Booth à 2 dimensions
- Sphere à 50 et 100 dimensions
- Alpin à 50 et 100 dimensions
- Rastringin à 50 et 100 dimensions
Ce sont des problèmes de minimisation

I) On procède d'abord à l'initialisation d'une population  
II) On procède au croisement des solutions par la méthode binomiale ou exponentielle  
III) On procède à la mutation des solutions par la méthode BEST2 ou CURRENTOBEST1  

On itère ce processus II) et III) un nombre défini de fois.  

Le but est d'arriver à trouver une solution qui nous permet d'obtenir une fonction objectif proche de 0.  

J'ai établi un design avec des paramètre qui est assez robuste pour résoudre ces 4 problèmes dans un temps raisonnable.
