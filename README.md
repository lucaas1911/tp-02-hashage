# tp-02-hashage
Exercice 1 : Effet d'avalanche    
Exercice 2 : 1) Longueur fixe. 2) 32 octets. L'affichage compte 64 caractères car 1 octet = 2 caractères hexadécimaux.   
Exercice 3 : La moindre altération modifie l'empreinte, ce qui permet de détecter immédiatement la falsification.   
Exercice 4 : 1) L'empreinte MD5 est plus courte, ce qui réduit les possibilités et favorise les collisions. 2) MD5 est déconseillé car il est vulnérable à ces collisions.   
Exercice 5 : 1) Non, les contenus sont différents. 2) Leurs MD5 sont identiques, mais leurs SHA-256 diffèrent. 3) MD5 est définitivement cassé. 4) L'attaquant peut modifier le document sans altérer l'empreinte MD5.   Exercice 6 : 1) Le texte change mais l'empreinte SHA-1 reste identique. 2) La signature ne garantit plus rien. 3) SHA-256, car il résiste toujours aux attaques de collision.
