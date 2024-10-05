#numeros de loteria
print("¿Cuáles son los números ganadores de la lotería?")
print(" ")

#pide al usuario por cinco números ganadores
num1 = int(input("¿Cuál es el número 1? "))
num2 = int(input("¿Cuál es el número 2? "))
num3 = int(input("¿Cuál es el número 3? "))
num4 = int(input("¿Cuál es el número 4? "))
num5 = int(input("¿Cuál es el número 5? "))

#se almacenan los números ingresados en una lista
thislist = [num1, num2, num3, num4, num5]

#se ordena los numeros de menor a mayor
thislist.sort()

print(" ")
#imprime el mensaje indicando que se mostrarán los números ordenados
print("Ahora los números se mostrarán en orden de menor a mayor:")
#se muestra la lista de números ordenados
print(thislist)

![image](https://github.com/user-attachments/assets/3390792c-1cf6-4269-ae4a-89381a98898d)
![image](https://github.com/user-attachments/assets/ca1d90c6-4b04-42fe-bd35-459056150bb1)
