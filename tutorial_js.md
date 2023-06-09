# Tutorial Básico de JavaScript

## Índice

1. [Introducción](#intro)
2. [Configuración del Entorno](#setup)
3. [Primeros Pasos](#first_steps)
4. [Variables y Tipos de Datos](#variables)
5. [Operaciones Matemáticas Básicas](#math_operations)
6. [Control de Flujo](#flow_control)
7. [Funciones](#functions)
8. [Arrays](#arrays)
9. [Objetos](#objects)
10. [Conclusiones](#conclusions)

<a name="intro"></a>
## 1. Introducción

JavaScript es un lenguaje de programación de alto nivel, interpretado, de un solo hilo, basado en el concepto de prototipos. Originalmente fue diseñado como un lenguaje de script para proporcionar interactividad en las páginas web pero con el tiempo ha ganado mayor protagonismo y ahora se utiliza en muchas otras aplicaciones.

<a name="setup"></a>
## 2. Configuración del Entorno

El entorno más común para ejecutar JavaScript es el navegador web. Puedes escribir código JavaScript directamente en el HTML utilizando la etiqueta `<script>`. No hay necesidad de un entorno especial de desarrollo para comenzar.

<a name="first_steps"></a>
## 3. Primeros Pasos

Vamos a comenzar mostrando un mensaje simple. En JavaScript, esto se logra con una línea de código:

```javascript
console.log("¡Hola, Mundo!");
```

<a name="variables"></a>
## 4. Variables y Tipos de Datos

En JavaScript, puedes definir variables usando `var`, `let`, o `const`, siendo `let` y `const` introducidos en la versión ES6 de JavaScript.

```javascript
let nombre = "John";  // Esto es un string
let edad = 20;  // Esto es un número
let esAdulto = true;  // Esto es un boolean
```

<a name="math_operations"></a>
## 5. Operaciones Matemáticas Básicas

JavaScript puede realizar todas las operaciones matemáticas básicas.

```javascript
let suma = 7 + 3;  // resultado: 10
let resta = 7 - 3;  // resultado: 4
let multiplicacion = 7 * 3;  // resultado: 21
let division = 7 / 3;  // resultado: 2.3333333333333335
let modulo = 7 % 3;  // resultado: 1
```

<a name="flow_control"></a>
## 6. Control de Flujo

JavaScript soporta las declaraciones de control de flujo típicas.

```javascript
let edad = 20;

if (edad >= 18) {
    console.log("Eres un adulto.");
} else {
    console.log("Eres un menor.");
}
```

<a name="functions"></a>
## 7. Funciones

Las funciones en JavaScript se pueden definir de varias formas, la más tradicional es usando la palabra clave `function`.

```javascript
function saludo(nombre) {
    console.log("¡Hola, " + nombre + "!");
}

saludo("John");  // Esto imprimirá: ¡Hola, John!
```

<a name="arrays"></a>
## 8. Arrays

Los Arrays son una estructura de datos que puede contener múltiples elementos y tipos de datos.

```javascript
let lista = ["manzana", "banana", "cereza"];
console.log(lista[1]);  // Esto imprimirá: banana
```

<a name="objects"></a>
## 9. Objetos

Los objetos en JavaScript son una colección de propiedades, definidas como un par de clave-valor.

```javascript
let miObjeto = {
    nombre: "John",
    edad: 30,
    altura: 1.80
};

console.log(miObjeto.nombre);  // Esto imprimirá: John
```

<a name="conclusions"></a>
## 10. Conclusiones

Este tutorial proporciona una breve introducción a algunos de los conceptos básicos de JavaScript. JavaScript es un lenguaje muy versátil y potente, que es ampliamente utilizado en la programación web tanto del lado del cliente como del servidor.

Para seguir aprendiendo JavaScript, se recomienda practicar con pequeños proyectos y ampliar tus conocimientos con tutoriales más avanzados y documentación de JavaScript. ¡Feliz codificación!
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMTk2NTkwN119
-->