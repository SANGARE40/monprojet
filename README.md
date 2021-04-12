# monprojet
c'est mon premier projet 
##exercice 1


´´´python
#Exercice 01 : Nombre mysterieux
from random import *
aa=randint(1,100)
ab=0
while aa != ab :
  ab= int(input("Quel est le nombre mystérieux : ?"))
  if ab < aa :
    print("Faux : votre nombre est petit !")
  elif ab>aa :
    print("Faux : votre nombre est grand !")
  else :
    print("Bravo : vous avez trouvé !")
´´´
