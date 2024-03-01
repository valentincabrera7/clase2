#[] lista (las listas y los strings (cadenas) se pueden concatenar, la unica diferencia es que las listas son mutables), contienen la funcion append
#() tupla se utiliza para asegurarnos que una coleccion de datos no se modifique (no se pueden mutar)(las tuplas no contienen la funcion append, pero se puede agregar concatenando)
# en python, una lista y una tupla pueden ser anidadas: esto significa que pueden contener una lista o una tupla dentro de si

datos = [10, "a", 20]
print(datos[0])
print(len(datos))

# Definir la lista_1 y la lista_2
lista_1 = [1, "Hola"]
lista_2 =[2, "Chau"]

# Añadir int y str a la lista_1
lista_1.append(12345)
lista_1.append("Como va?")

# Añadir int y str a la lista_2
lista_2.append(67989)
lista_2.append("Bien y vos?")

# Generar una lista_3 con todos los elementos de la lista_1 menos el ultimo
lista_3 = lista_1 [:-1]

# Generar una lista_4 con todos los elementos de la lista_2 menos el primero y el ultimo
lista_4 = lista_2 [1:-1]
