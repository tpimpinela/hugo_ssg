---
title: "Markdown"
date: 2023-11-04T18:17:32+01:00
draft: false
weight: 100
---

Markdown es un lenguaje de marcado ligero que se utiliza para formatear texto de una manera sencilla y legible. Permite a los usuarios agregar formato básico a su texto, como encabezados, listas, enlaces e énfasis, utilizando una sintaxis fácil de recordar y escribir. Markdown se convierte fácilmente en HTML y se utiliza comúnmente en plataformas web, como blogs y foros, para crear contenido con formato de manera rápida y sencilla sin necesidad de conocimientos avanzados de codificación HTML.

# Elementos de bloque

## Parrafos

Puedes generar diversos parrafos dejando una línea en blanco entre ellos.

```
Parrafo 1

Parrafo 2
```

Resultado:

Parrafo 1

Parrafo 2

## Saltos de línea

Para escribir un salto de línea hay que poner dos espacios antes de insertar un salto de línea.

```
Contenido
Contenido tras salto de línea
```

Resultado:

Contenido  
Contenido tras salto de línea

## Encabezados

Para escribir encabezados hay que insertar una almohadilla por nivel de encabezado (soporta de 1 hasta 6) y un espacio y el texto del encabezado.

```
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```

Resultado:

# Encabezado 1

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

---

## Citas

Las citas se generan utilizando el carácter mayor que (>) al comienzo del bloque de texto. Si la cita tiene varios parrafos hay que añadir el mismo símbolo al comienzo de cada parrafo:

```
> Cita - Parrafo 1
> Cita - Parrafo 2
```

Resultado:

> Cita - Parrafo 1  
> Cita - Parrafo 2

## Listas

### Desordenadas

Para generar listas ordenadas se utilizan \* astericos, - guiones, o + símbolo de suma. Se pueden generar listas anidadas añadiendo cuatro espacios en blanco antes del siguiente símbolo.

```
- Elemento de lista 1
- Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
```

Resultado:

- Elemento de lista 1
- Elemento de lista 2
  - Elemento de lista 3
  - Elemento de lista 4

### Ordenadas

Para generar listas ordenadas se utilizan los números como símbolo.

```
1. Elemento de lista 1
2.  Elemento de lista 2
```

Resultado:

1. Elemento de lista 1
2. Elemento de lista 2

## Bloques de código

Para crear bloques de código tenemos que introducir "```" al principio y al final del bloque de código. Puedes añadir el nombre del lenguaje utilizado en el bloque de código al final del símbolo de inicio para obtener resaltado de la sintáxis del lenguaje.

````
```php
<?php echo "Hello, World!"; ?>
```
````

Resultado:

```php
<?php echo "Hello, World!"; ?>
```

## Reglas horizontales o separadores

Para crear separadores tienes que introducir uno de los siguientes símbolos:

```
***
---
___
```

Resultado:

---

---

---

# Elementos de línea

## Énfasis

Para conseguir énfasis en palabras Markdown utiliza asteriscos o guiones bajos.

```
*cursiva*
_cursiva_
**negrita**
__negrita__
***cursiva y negrita***
___cursiva y negrita___
```

Resultado:

_cursiva_  
_cursiva_  
**negrita**  
**negrita**  
**_cursiva y negrita_**  
**_cursiva y negrita_**

## Links o enlaces

Para crear links o enlaces hay que escribir el texto entre corchetes y el enlace en cuestión entre paréntesis.

```
[Texto de enlace](http://www.google.com)
```

Resultado:

[Texto de enlace](http://www.google.com)

## Código

Para representar una línea de código suelta tenemos que envolver la línea entre backticks (`).

```
`<?php echo 1 + 1; ?>`
```

Resultado:

`<?php echo 1 + 1; ?>`

## Imágenes

Insertar imágenes en Markdown es similar a insertar enlaces, sólo que en este caso hay que añadir una exclamación ! al principio y el enlace será la ubicación de la imágen.

```
![Texto alternativo si no carga la imágen](https://miro.medium.com/v2/resize:fit:1400/1*29NeeIGT0BElEBNfzE_VlQ.jpeg)
```

Resultado:

![Texto alternativo si no carga la imágen](https://miro.medium.com/v2/resize:fit:1400/1*29NeeIGT0BElEBNfzE_VlQ.jpeg)
