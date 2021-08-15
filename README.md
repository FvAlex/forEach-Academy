# Execution du code

- Ouvrir un terminal
- Entrez : python3 appart.py
- Indiquez le nombre

# Explication de non finalité de l'exercice

N'ayant fais que peu de python, pas à un niveau suffisant pour régler cet exercice, j'ai compris la méthode/théorie, sauf la pratique.

Chaque tranche de nombre correspond à un chiffre:

- 1 = 1
- 11 = 2
- 111 = 3
- 1111 = 4
- 2 = 1
- 22 = 2 
- 222 = 3
- 2222 = 4

On retrouve donc " 1234 " pour chaque nombre en commun respectueusement( 1111, 2222, 3333, 4444, 5555, 6666, 7777, 8888, 9999).

Si on le retourne sous forme de tableau :

[1111, 2222, 3333, 4444, 5555, 6666, 7777, 8888, 9999] = [1234, 1234, 1234, 1234, 1234, 1234, 1234, 1234, 1234]


Le reste correspond à une addition, si je prend le nombre 666 ca donnera :

( 1+2+3+4 ) * 5 + (1 + 2 + 3) = 56


Bob aurait appuyé 56 fois pour que l'appartement 666 lui ouvre la porte.

La seule condition est qu'à chaque fois que l'addition arrive à la limite de 4 elle doit recommencer à 1, c'est donc une somme de serie.

# Bonus

Si vous voulez voir d'autre projet que j'ai pu créer, je vous laisse l'opportunité d'aller regarder mes autres repertoire GitHub