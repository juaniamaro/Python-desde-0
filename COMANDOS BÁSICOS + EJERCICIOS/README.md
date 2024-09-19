<h1 align="center">📚✨¿QUÉ ENCONTRARAS EN ESTE REPOSITORIO?✨📚</h1>
Aquí encontraras los comandos y herramientas básicas para usar python de 0 además de una serie de ejercicios resueltos que puedes usar para entender mejor el funcionamiento de las estructuras.
</br><b>Es importante que leas bien los enunciados de los ejercicios para poder llevarlos acabo</b>
<h2 align="center">📝¿CÓMO HACER LOS EJERCICIOS?📝</h2>
<ul>
  <li>LEE BIEN EL ENUNCIADO</li>
  <li>INTENTA HACERLO POR TU CUENTA</li>
  <li>COMPRUEBA EL CODIGO DEL REPOSITORIO SI NO CONSIGUES QUE FUNCIONE (TODO EL CÓDIGO ESTA COMENTADO PARA UNA MEJOR COMPRENSIÓN)</li>
</ul>
👮‍♂️Si encuentras una mejor forma de realizar los ejercicios o un error porfavor no dudes en contribuir con el repositorio:
<ul>
  <li>Haz un Fork del Repositorio: Crea tu propia copia del repositorio y realiza tus cambios allí.</li>
  <li>Crea una Pull Request: Envía tus cambios para revisión mediante una pull request.</li>
</ul>
<h1 align="center">🐍✨COMANDOS BÁSICOS DE PYTHON✨🐍</h1>
Aquí tienes un resumen de los comandos, operaciones y técnicas básicas que debes conocer para empezar con Python:
<h2 align="center">COMANDOS BÁSICOS</h2>
MOSTRAR INFORMACIÓN EN PANTALLA

````
print("Hola, mundo")
````

PEDIR ENTRADA POR TECLADO
> [!CAUTION]
> Por defecto todo dato introducido por teclado se reconoce como tipo string - str

````
nombre = input("Ingresa tu nombre: ")
print("Hola,", nombre)
````

COMENTAR

````
# Esto es un comentario
````

ASIGNAR VARIABLES
> [!NOTE]
>No necesitamos declarar de que tipo es la variable ya que python tiene una naturaleza de tipado dinamatica y ya lo reconoce.

````
nombre = "Ana"
````

OPERADORES ARITMETICOS

````
a = 5 + 2  # Suma
b = 5 * 2  # Multiplicación
c = 10 % 3 # Módulo (resto)
d = 2 ** 3 # Exponente (2^3)
````

OPERADORES COMPARADORES
> [!TIP]
> Igual a (==), distinto de (!=), mayor que (>), menor que (<), mayor o igual (>=), menor o igual (<=)

````
x = 5
y = 10
resultado = x > y  # False
````

OPERADORES LÓGICOS

````
True and False  # False
True or False   # True
not True        # False
````

CONDICIONALES

````
if condicion:
   acciones
elif condicion2:
   acciones
else
    acciones
````

BUCLES

````
for i in range(5):
    print(i)  # Imprime del 0 al 4
````

````
contador = 0
while contador < 5:
    print(contador)
    contador += 1
````

FUNCIONES

````
def saludar(nombre):
    print("Hola,", nombre)

saludar("Carlos")
````

LISTAS
> [!NOTE]
> Colección ordenada e inmutable.

````
numeros = [1, 2, 3, 4, 5]
print(numeros[0])  # Acceder al primer elemento
numeros.append(6)  # Añadir un elemento
print(numeros)
````

DICCIONARIOS
> [!NOTE]
> Colección de pares clave-valor.

````
persona = {"nombre": "Ana", "edad": 25}
print(persona["nombre"])  # Acceder a un valor
persona["edad"] = 26      # Modificar un valor
````

TUPLAS
> [!NOTE]
> Similares a las listas, pero inmutables.

````
tupla = (10, 20, 30)
print(tupla[0])
````

MANEJO DE ARCHIVOS

````
# Abrir y leer un archivo
archivo = open("archivo.txt", "r")
contenido = archivo.read()
archivo.close()

# Escribir en un archivo
archivo = open("archivo.txt", "w")
archivo.write("Hola, archivo")
archivo.close()
````

MANEJO DE ERRORES

````
try:
    division = 10 / 0
except ZeroDivisionError:
    print("Error: división entre cero no permitida")
````

IMPORTACIÓN DE MÓDULOS

````
import math
print(math.sqrt(16))  # Imprime la raíz cuadrada de 16
````

Estos son los fundamentos básicos que debes conocer para empezar a programar en Python. A partir de aquí, puedes ir aprendiendo conceptos más avanzados según tus necesidades y proyectos.

<a href=https://github.com/juaniamaro/Python-desde-0/tree/main/COMANDOS%20B%C3%81SICOS%20%2B%20EJERCICIOS/EJERCICIOS%20DE%20COMANDOS%20B%C3%81SICOS>COMIENZA A PRACTICAR</a>







    
