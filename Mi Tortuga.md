<h1 align="center">
    RETO NRO. 1
</h1>

![IMAGEN NO CARGA](img/reto_1.JPG)

Mi solucion fue un poco dura ya que decidi añadir la imagen de la tortuga, la cual casi no la consigo. Ademas cometi tantos errores que no me queria correr correctamente el programa.
Hasta que le pregunte a la IA "GEMINI" y me recomendo resetear el kernel, despues de hacerlo el programa corrio correctaente.

````
Python

tortuga = "🐢"
pasos_adelante= int (input("Ingrese el número de pasos hacia adelante: "))
print ("_ " * (pasos_adelante - 1) + tortuga)

````
<br>
<h1 align="center">
    RETO NRO. 2
</h1>

![IMAGEN NO CARGA](img/reto_2.JPG)

Este reto no estuvo demasiado dificil, ya que me base en el anterior, lo unico que debi buscar fue como hacer el salto de linea sin tener que repetir varias veces la funcion "Print".

````
Python

tortuga = "🐢"
pasos_abajo= int (input("Ingrese el número de pasos hacia abajo: "))
print (" \n| " * (pasos_abajo) + tortuga)

````
<br>
<h1 align="center">
    RETO NRO. 3
</h1>

![IMAGEN NO CARGA](img/reto_3.JPG)

Este reto se me complico mucho ya que no era capaz de alinear el camino horizontal con el vertical. Logre hacerlo, gracias a que copie el codigo que hice en GEMINI para saber que era el error. Logre encontrarlo con esta ayuda y lo pude solucionar.

````
Python

tortuga = "🐢"
pasos_adelante= int (input("Ingrese el número de pasos hacia adelante: "))
print ("_ " * pasos_adelante)
espacios = "  " * pasos_adelante 
camino_abajo = espacios + "|\n"
pasos_abajo= int (input("Ingrese el número de pasos hacia abajo: "))
print(camino_abajo * (pasos_abajo - 1), end='')
print(espacios + tortuga)

````
<br>
<h1 align="center">
    RETO NRO. 4
</h1>

![IMAGEN NO CARGA](img/reto_4.JPG)

En este reto me fue mal, casi no logro dar con la solucion, aunque no lo pude ensayar; ya que en VSC no me corre el programa y por la terminal me dice que el directorio no existe. Debido a esto le pregunte a GEMINI que si el codigo estaba correcto, a lo cual me respondio que "SI".

````
Python

tortuga = "🐢"
espacios = ""
camino_abajo = ""

def adelante():
    pasos_adelante= int (input("Ingrese el número de pasos hacia adelante: "))
    print ("_ " * pasos_adelante)
    global espacios, camino_abajo
    espacios = " " * pasos_adelante
    camino_abajo = espacios + "|\n"
def abajo():
    global espacios, camino_abajo
    pasos_abajo= int (input("Ingrese el número de pasos hacia abajo: "))
    print(camino_abajo * (pasos_abajo - 1), end='')
    print(espacios + tortuga)

````
