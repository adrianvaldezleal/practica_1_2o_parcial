#almacenar las materias de un curso en lista junto a sus calificaciones
materia1 = input("ingresa la primer materia: "), int(input("calificacion de la materia 1: "))
materia2 = input("ingresa la segunda materia: "), int(input("calificacion de la materia 2: "))
materia3 = input("ingresa la tercera materia: "), int(input("calificacion de la materia 3: "))
materia4 = input("ingresa la cuarta materia: "), int(input("calificacion de la materia 4: "))
materia5 = input("ingresa la quinta materia: "), int(input("calificacion de la materia 5: "))

thislist = [materia1, materia2, materia3, materia4, materia5]
print(" ")
print("materias del 1 curso", thislist) #apareceran las materias del primer curso

print(" ")
for materia in thislist:
   #se mostraran las materias que se estan cursando y la calificacion que has obtenido
   print("Estoy cursando", materia[0], "y has obtenido", materia[1]) 


![image](https://github.com/user-attachments/assets/5b7763f8-46d9-494c-bb59-19901c7b6b17)
![image](https://github.com/user-attachments/assets/57a3d26e-45a6-447e-bf6c-aefa82b97856)
