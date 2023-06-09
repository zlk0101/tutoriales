
# Tutorial Básico de Python 

## Índice

1. [Introducción](#intro)
2. [Instalación de Python y Configuración del Entorno](#install)
3. [Primeros Pasos](#first_steps)
4. [Variables y Tipos de Datos](#variables)
5. [Operaciones Matemáticas Básicas](#math_operations)
6. [Control de Flujo](#flow_control)
7. [Funciones](#functions)
8. [Listas](#lists)
9. [Diccionarios](#dictionaries)
10. [Conclusiones](#conclusions)

<a name="intro"></a>
## 1. Introducción

Python es un lenguaje de programación de alto nivel, interpretado y de propósito general. Su diseño enfatiza la legibilidad del código, y su sintaxis permite a los programadores expresar conceptos en menos líneas de código de lo que sería posible en lenguajes como C++ o Java.

<a name="install"></a>
## 2. Instalación de Python y Configuración del Entorno

Para instalar Python y configurar el entorno, siga los siguientes pasos:

1. Visite la página oficial de Python en https://www.python.org/.
2. Descargue la última versión de Python.
3. Instale Python en su computadora siguiendo las instrucciones.
4. Verifique la instalación. Abra la línea de comandos y escriba `python --version`. Debería ver la versión de Python que acaba de instalar.

<a name="first_steps"></a>
## 3. Primeros Pasos

El primer programa que la mayoría de la gente aprende al comenzar con cualquier lenguaje de programación es cómo imprimir "¡Hola, Mundo!".

En Python, esto se logra con una sola línea de código:

```python
print("¡Hola, Mundo!")
```

Escriba esta línea en su editor de código, guárdelo con una extensión `.py` y ejecútelo con Python. Debería ver "¡Hola, Mundo!" impreso en su consola.

<a name="variables"></a>
## 4. Variables y Tipos de Datos

Python es dinámicamente tipado, lo que significa que no necesitas definir el tipo de dato de una variable al declararla.

```python
nombre = "John"  # Esto es un string
edad = 20  # Esto es un integer
altura = 1.80  # Esto es un float
```

<a name="math_operations"></a>
## 5. Operaciones Matemáticas Básicas

Python puede realizar todas las operaciones matemáticas básicas.

```python
suma = 7 + 3  # resultado: 10
resta = 7 - 3  # resultado: 4
multiplicacion = 7 * 3  # resultado: 21
division = 7 / 3  # resultado: 2.3333333333333335
modulo = 7 % 3  # resultado: 1
```

<a name="flow_control"></a>
## 6. Control de Flujo

Python soporta las declaraciones de control de flujo típicas.

```python
edad = 20

if edad >= 18:
    print("Eres un adulto.")
else:
    print("Eres un menor.")
```

<a name="functions"></a>
## 7. Funciones

Las funciones en Python se definen con la palabra clave `def`, seguida del nombre de la función y un par de paréntesis `()`.

```python
def saludo(nombre):
    print("¡Hola, " + nombre + "!")

saludo("John")  # Esto imprimirá: ¡Hola, John!
```

<a name="lists"></a>
## 8. Listas

Las listas son una estructura de datos muy utilizada en Python que puede contener múltiples elementos y tipos de datos.

```python
lista = ["manzana", "banana", "cereza"]
print(lista[1])  # Esto imprimirá: banana
```

<a name="dictionaries"></a>
## 9. Diccionarios

Los diccionarios en Python son una estructura de datos que almacena pares de claves y valores.

```python
mi_diccionario = {
    "nombre": "John",
    "edad": 30,
    "altura": 1.80
}

print(mi_diccionario["nombre"])  # Esto imprimirá: John
```

<a name="conclusions"></a>
## 10. Conclusiones

Este tutorial proporciona una breve introducción a algunos de los conceptos básicos de Python. Python es un lenguaje muy versátil y potente, que es ampliamente utilizado en muchas áreas de la programación, desde la programación web hasta la ciencia de datos, el aprendizaje automático y más.

Para continuar aprendiendo Python, se recomienda practicar con proyectos pequeños y expandir sus conocimientos con tutoriales más avanzados y documentación de Python. ¡Feliz codificación!
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTEzNjE4MTI1Nl19
-->