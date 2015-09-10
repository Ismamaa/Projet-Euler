# Projet-Euler
 Créé par Villebon charpak, le 09/09/2015 en Python 3.2
a = 0
i = 0
while i < 1001: # Tant que i est inférieure à 1000
    if i % 3 == 0:
        a = a+i
    elif i % 5 == 0:
        a = a+i
    else :
        a=a

    i += 1 # Dans le cas classique on ajoute juste 1 à i


print(a)


# Créé par Villebon charpak, le 09/09/2015 en Python 3.2

a=1
b=2
c=1
d=0

while b<4000001:
    c=c+b
    (b,a)=(a+b,b)


print (b)
print (c)

