---
title: "Sintaxis Básica Markdown"
author: "Renzo Cáceres Rossi"
date: "2022/09/27"
output:
  html_document:
    code_download: yes
  pdf_document: default
  word_document: default
subtitle: "Markdown - RMarkdown"
---

<!-- Añadir comentarios a nuestro documento Markdown - HTML tags -->

<a name="abc"></a>

[**Fin Documento**](#def)

## Overview

**Markdown** es un lenguaje de marcado ligero (***Lightweight Markup Language***), siendo **RMarkdown**[^1] uno de sus dialectos, una de sus variantes, uno de sus sabores (**Markdown Flavours**).


## Encabezados - Títulos

# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

Título 1
=========

Título 2
---------

## Separaciones - Línea Horizontal

---

***

---

***

## Citas - Añadir citas a nuestro documento Markdown

>  “La tecnología no es nada. Lo importante es que tengas fe en la gente, que sean básicamente buenas e inteligentes, y si les das herramientas, harán cosas maravillosas con ellas.” - Steve Jobs 

> “Las grandes oportunidades nacen de haber sabido aprovechar las pequeñas.” - Bill Gates


## Negrita - Cursiva - Tachado - Subrayado

**Texto formateado como Negrita**

*Texto formateado como Cursiva*

***Texto formateado como Negrita y Cursiva***

~~Texto tachado~~

<u>Texto subrayado</u> <!--HTML Tags-->


## Superíndice - Subíndice

Superíndice^45^

Subíndice~45~


## Listas 

### Lista Viñetas - Lista Anidada

- Lista 1
- Lista 2
- Lista 3
- Lista 4
- Lista 5
  - Lista 5.1
  - Lista 5.2
  - Lista 5.3
- Lista 6
- Lista 7
- Lista 8

### Lista Numerada

1. Lista 1
2. Lista 2
3. Lista 3
4. Lista 4
5. Lista 5
6. Lista 6

### Lista ordenada alfabéticamente

a. Lista A
b. Lista B
c. Lista C
d. Lista D
e. Lista E
f. Lista F

### Casos - Ejemplos - Listas

- [ ] Lista A
- [ ] Lista B
- [ ] Lista C
- [ ] Lista D
- [ ] Lista E
- [ ] Lista F

---

- Lista 1
- Lista 2
- Lista 3
* Lista 4
* Lista 5
* Lista 6
+ Lista 7
+ Lista 8
+ Lista 9

---

1. Lista 1
3. Lista 2
5. Lista 3
7. Lista 4
9. Lista 5
11. Lista 6


## Enlaces - Añadir links a nuestro documento Markdown


<https://www.linkedin.com/company/ieee-computer-society-utec/>{target=_blank}

[IEEE CS UTEC](https://www.linkedin.com/company/ieee-computer-society-utec/){target=_blank}

[IEEE CS UTEC](https://www.linkedin.com/company/ieee-computer-society-utec/ "IEEE CS UTEC"){target=_blank}


## Imágenes - Añadir imágenes a nuestro documento Markdown

<center>

![**Logo R**](logo_r.png)


</center>


## Tablas - Añadir tablas a nuestro documento RMarkdown

|TABLA A|TABLA B|TABLA C|
|:-----:|:-----:|:-----:|
|A      |B      |C      |
|A      |B      |C      |
|A      |B      |C      |
|A      |B      |C      |
|A      |B      |C      |
|A      |B      |C      |
|A      |B      |C      |
|A      |B      |C      |


## Mapas - Añadir mapas a nuestro documento Markdown

<center>

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3900.6629226096697!2d-77.02432978561669!3d-12.135200146854892!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9105b7fcaea4a133%3A0xb86fbddb0dc89e2e!2sUniversidad%20de%20Ingenier%C3%ADa%20y%20Tecnolog%C3%ADa%20-%20UTEC!5e0!3m2!1ses!2spe!4v1664314181313!5m2!1ses!2spe" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" data-external=1></iframe>

</center>

<br>

## Vídeos - Añadir vídeos a nuestro documento Markdown

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/EkxRj02iaLk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen data-external=1></iframe>

</center>

<br>

## Código - Añadir código de distintos lenguajes de programación (R - Python - SQL)


    summary(mtcars)
    
La función `barplot()` nos permite crear diagramas de barras (**Bar Charts**) en el lenguaje de programación R.

```R
x <- table(mtcars$cyl)

colores <- c("orange","blue","purple")

barplot(x,xlab="Cilindros",ylab="Frecuencias",main="Número de Cilindros",col=colores)

```


```Python

import matplotlib.pyplot as plt
 

eje_x = ['Python', 'R', 'Node.js', 'PHP']
 

eje_y = [50,20,35,47]
 

plt.bar(eje_x, eje_y)
 

plt.ylabel('Cantidad de usuarios')
 

plt.xlabel('Lenguajes de programación')
 

plt.title('Usuarios de lenguajes de programación')
 

plt.show()


```

    SELECT id_usuario,usuario_nombre,usuario_apellidos FROM usuarios;
    
```sql

USE Northwind;

SELECT * FROM Products;


```

## Anular sintaxis Markdown


\**Texto que debería ser formateado como Negrita**


\*Texto que debería ser formateado como Cursiva*


\~~Texto que debería estar tachado~~


[^1]: **RMarkdown** es un paquete del lenguaje de programación R que nos permite crear documentos científicos y técnicos, en formatos tales como HTML,PDF,Word entre otros.



[**Inicio Documento**](#abc)

<a name="def"></a>



<div class="tocify-extend-page" data-unique="tocify-extend-page" style="height: 0;"></div>








