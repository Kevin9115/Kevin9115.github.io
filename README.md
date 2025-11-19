# 🧠 Mi Primera Página: PENSAMIENTO ALGORÍTMICO

---

Durante las primeras clases, el profesor Juan Camilo nos dio una breve introducción a lo que es este gran mundo de la **programación**. Empezó hablando sobre cómo fueron los inicios de las computadoras, dándonos como ejemplo "**El Ábaco**" que, si lo pensáramos bien, fue el principio de lo que actualmente conocemos como computador.

También vimos conceptos fundamentales como los siguientes:

---

## 💻 Conceptos Fundamentales de la Programación

### **LENGUAJE DE PROGRAMACIÓN**

Es un lenguaje formal que le proporciona a un programador la capacidad de escribir una serie de instrucciones o secuencias de órdenes en forma de **algoritmos**, con el fin de controlar el comportamiento físico o lógico de una computadora para obtener diversos resultados o ejecutar tareas.

#### Tipos de Lenguajes

**1. Por su Uso (Máquina o Sistema Operativo):**

* **Interpretados:** Las instrucciones son traducidas **una a una** por una aplicación (intérprete).
    * *Ejemplos:* **Python**, Perl, Bash.
* **Compilados:** Las instrucciones son traducidas **en grupo** por una aplicación (compilador).
    * *Ejemplos:* Fortran, C/C++.
* **Intermedios:** En parte compilados, en parte interpretados.
    * *Ejemplos:* Java, Scala.

**2. De Acuerdo a su Nivel de Abstracción:**

* **Alto Nivel:** La información compleja es representada con **objetos simples**.
    * *Ejemplos:* **Python**, C++, C#, Java.
* **Bajo Nivel:** La información compleja debe representarse **literalmente**.
    * *Ejemplos:* Assembly y Machine.

### **ENTORNO DE DESARROLLO (IDE)**

También conocidos como **IDE** (*Integrated Development Environment*), son **editores de código** diseñados para que los desarrolladores puedan escribir el código. Una IDE muy usada académicamente es **Google Colaboratory** o **Colab**.

### **PROGRAMA**

Es un conjunto de **instrucciones ordenadas** que una computadora puede interpretar y ejecutar para realizar una tarea o función específica, dirigida a **resolver un problema** o suplir alguna necesidad.

### **ALGORITMO**

Es un conjunto de **instrucciones o reglas detalladas y ordenadas** que al seguirse permiten resolver un problema específico o realizar una tarea determinada.

Está compuesto por 3 elementos básicos: **Entradas**, **Procesos** y **Salidas**.

* **Entradas:** Los **insumos** (datos) requeridos para la solución (números, nombres, fechas, entre otros).
* **Procesos:** Las **acciones** que manipulan los datos de entrada para generar los resultados.
* **Salidas:** La **solución** o la forma en que se presentan los resultados.

> El Programador se sitúa en las **Entradas** (comprende el algoritmo) y el Cliente en las **Salidas** (solo le interesa el resultado).

**Condiciones que debe cumplir:** debe resolver un problema, debe ser **finito** y debe interactuar con **datos externos y/o variables**.

---

## 💾 Almacenamiento y Operaciones

### **VARIABLES Y CONSTANTES**

* **Variables:** Espacios en memoria que almacenan, de manera **temporal**, los datos que serán utilizados en el procesamiento.
* **Constantes:** **Valores invariables** durante la ejecución del algoritmo.

### **TIPOS DE ACCIONES O INSTRUCCIONES DE PROCESAMIENTO**

* **Instrucciones Lógicas:** Operan datos de tipo **lógico o booleano** (**verdadero o falso**).
* **Instrucciones Matemáticas:** Se aplican sobre datos de tipo **numérico** para realizar operaciones aritméticas.

### **OPERADORES**

| Tipo de Operador | Función Principal |
| :--- | :--- |
| **Aritméticos** | Realizan operaciones matemáticas básicas. |
| **Relacionales** | Comparan valores (>, <, ==) y producen un resultado booleano. |
| **Lógicos** | Combinan o modifican valores booleanos (AND, OR, NOT). |

---

## 💡 Ejemplo de Código

Aquí se muestra un ejemplo sencillo en Python:

```python
nombre = input("Por Favor, Ingresa Tu Nombre: ")

print(f"¡Hola , {nombre}! Bienvenido. ")

print("¡Diste El Primer Paso!")
