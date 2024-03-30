# Demo-Markdown

**Autora: Laura Temin Rodríguez Murillo**

Es un lenguaje de marcas en el que podemos agregar formato a un texto plano utilizando una sintaxis parecida al HTML, es más, podemos combinar markdown con css y HTML de forma sencilla.
Markdown busca tener la máxima legibilidad y facilidad posible para facilitar su uso por lo que aunque no se tenga mucho conocimiento de ningún lenguaje de programación puedes utilizarlo sin mucha dificultad.

## Índice
1. [Sintaxis de Markdown](#id1)  
    1.1 [Encabezados](#id2)  
    1.2 [Saltos de línea](#id3)  
    1.3 [Dar formato a las palabras o frases](#id4)  
    1.4 [Citas](#id5)  
    1.5 [Listas](#id6)  
    1.6 [Link automáticos](#id7)  
    1.7 [Imágenes](#id8)  
    1.8 [Tablas](#id9)  
    1.9 [Código de diferentes lenguajes](#id10)  
    1.10 [Omitir Markdown](#id11)
2. [Combinación de Markdown con css y html](#id12)
3. [Conclusión](#id13)

## 1. Sintaxis de Markdown<a name="id1"></a>
Este lenguaje de marcas cuenta con su propia sintaxis, al estar pensado para ser un lenguaje sencillo de utilizar su sintaxis no es muy complicada. A continuación mostraremos algunos ejemplos de su sintaxis. 
<br>

### 1.1 Encabezados<a name="id2"></a>  

Para utilizar los encabezados utilizamos de 1 a 6 hash al comienzo de la línea dependiendo del nivel de encabezado que queramos utilizar. 
###### 1.1.1 Ejemplo código markdown

```markdown
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```

###### 1.1.2 Ejemplo de como se ve

# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
<br>

#### 1.2 Saltos de línea<a name="id3"></a>  
Para lograr un salto de línea podemos escribir br entre <> o terminar la línea con dos espacios y pulsar intro. 
###### 1.2.1 Ejemplo código markdown
```markdown
<br>
```
###### 1.2.2 Ejemplo de como se ve

Salto <br> de línea

Salto  
de linea
<br>
#### 1.3 Dar formato a las palabras o frases<a name="id4"></a> 
+ **Tachar un texto:** ponemos este carácter ~ dos veces al inicio de la palabra o frase y al final.
+ **Negrita:** escribirnos en la palabra entre asteriscos o entre guiones bajos
+ **Cursiva:** escribirnos en la palabra entre dos asteriscos o entre dos guiones bajos.
+ **Cursiva y negrita:** escribirnos en la palabra entre tres asteriscos o entre tres guiones bajos.
###### 1.3.1 Ejemplo código markdown
```markdown
~~Tachar texto~~
**Negrita**
*Cursiva*
***Cursiva y negrita***
```
###### 1.3.2 Ejemplo de como se ve
~~Tachar texto~~  
**Negrita**  
*Cursiva*  
***Cursiva y negrita***
<br>
#### 1.4 Citas<a name="id5"></a>
Las citas se generan utilizando el siguiente carácter: > 
+ **Citar en bloque:** esto se consigue añadiendo > al inicio de cada uno de ellos
+ **Anidar las citas:** esto se consigue agregando niveles adicionales del carácter > al inicio de cada cita que quieras anidar.

Las citas pueden incluir otros elementos como encabezados, listas y bloques de código.
###### 1.4.1 Ejemplo código markdown
```markdown
>Cita en bloque
>>Cita anidada
```
###### 1.4.2 Ejemplo de como se ve
>Cita en bloque
>>Cita anidada
<br>

#### 1.5 Listas<a name="id6"></a>
Markdown permite listas ordenadas (numeradas) y desordenadas (con viñetas)
+ **Listas ordenadas:** se pueden utilizar los asteriscos, símbolos de suma y guiones. Obtendremos el mismo resultado.

+ **Listas desordenadas:** se utilizan números seguidos de puntos.


+ **Anidar las listas:** hay que dejar cuatro espacios antes del carácter que vayamos a utilizar. Esto es aplicable tanto a las listas ordenadas como a las desordenadas.
###### 1.5.1 Ejemplo código markdown

```markdown
+ Lista ordanadas
* Lista ordenada
-  Lista ordenada

1. Lista desordenada
2. Lista desordenada

+ Lista anidada
    + Lista anidada
```
###### 1.5.2 Ejemplo de como se ve
+ Lista ordanadas
* Lista ordenada
-  Lista ordenada

1. Lista desordenada
2. Lista desordenada

+ Lista anidada
    + Lista anidada


<br>

#### 1.6 Link automáticos<a name="id7"></a>
Para añadir links automáticos ponemos entre corchetes angulares el título del link y entre paréntesis la URL o podemos optar por poner entre comillas simples y <> el título del link seguido de dos puntos y la URL entre <>. 

###### 1.6.1 Ejemplo código markdown

```markdown
[Link a gitHub](https://github.com/)
`<link>` : <https://github.com>
```
###### 1.6.2 Ejemplo de como se ve
[Link a gitHub](https://github.com/)  
`<link>` : <https://github.com>

<br>
#### 1.7 Imágenes<a name="id8"></a> 
Para insertar una imagen debemos añadir un signo de exclamación ! al inicio seguido del texto del atributo alt para la imagen metido entre corchetes y por último entre paréntesis ponemos la ruta de la imagen o la URL, también al lado de la ruta o URL de la imagen podemos añadirle un título alternativo escrito entre comillas. 

###### 1.7.1 Ejemplo código markdown

```markdown
![](https://plugins.jetbrains.com/files/18897/166369/icon/pluginIcon.png)
![](./img/logo.png)
```
###### 1.7.2 Ejemplo de como se ve
![](https://plugins.jetbrains.com/files/18897/166369/icon/pluginIcon.png)
![](./img/logo.png)

<br>

#### 1.8 Tablas<a name="id9"></a>
Para crear las tablas utilizamos una barra vertical | para separar las celdas y un guion - para hacer una línea de encabezado.
+ **Sin cabecera:** como es obligatorio poner un encabezado, lo que incluiremos será un comentario vacío de HTML <!-- —>

+ **Alineación:** utilizamos los dos punto : dependiendo de dónde los coloquemos se alineará a la izquierda, derecha o centrará 
###### 1.8.1 Ejemplo código markdown

```markdown
######1.8.1.1 Tabla

| Columna 1 | Columna 2 | Columna 3 |
|----------|----------|----------|
| Celda 1    | Celda 2   | Celda 3   |

###### 1.8.1.2 Alineación
| Alineación a la izquierda  | Centrado  | Alineación a la derecha |
|:------------- |:---------------:| -------------:|
| Celda 1         | Celda 2          | Celda 3        |

###### 1.8.1.3 Sin cabecera
| <!-- -->      | <!-- -->        | <!-- -->      |
|:-------------:|:---------------:|:-------------:|
| Celda 1         | Celda 2       | Celda 3        |
```
###### 1.8.2 Ejemplo de como se ve
###### 1.8.2.1 Tabla

| Columna 1 | Columna 2 | Columna 3 |
|----------|----------|----------|
| Celda 1    | Celda 2   | Celda 3   |

###### 1.8.2.2 Alineación
| Alineación a la izquierda  | Centrado  | Alineación a la derecha |
|:------------- |:---------------:| -------------:|
| Celda 1         | Celda 2          | Celda 3        |

###### 1.8.2.3 Sin cabecera
| <!-- -->      | <!-- -->        | <!-- -->      |
|:-------------:|:---------------:|:-------------:|
| Celda 1         | Celda 2       | Celda 3        |
<br>

#### 1.9 Código de diferentes lenguajes<a name="id10"></a> 
Se utiliza tres acentos graves seguidos \`\`\` tanto en el inicio del código como en el final y corchetes para identificar el lenguaje de programación.  

###### 1.9.1 Ejemplo código markdown


\`\`\`markdown
codigo
\`\`\`  
\`\`\`Java
System.out.println(codigo);
\`\`\`
###### 1.9.2 Ejemplo de como se ve
```markdown
codigo
```
```Java
System.out.println(codigo);
```

<br>

#### 1.10 Omitir Markdown<a name="id11"></a>
Para mostrar los caracteres que aplica el markdown tenemos que poner \ justo antes de dicho carácter. 

###### 1.10.1 Ejemplo código markdown

```markdown
\# Omitir
```
###### 1.10.2 Ejemplo de como se ve
\# Omitir
<br>

## 2. Combinación de Markdown con css y html<a name="id12"></a>
Markdown nos permite utilizar css y HTML sin ningún problema pero los comandos de Markdown no podrán ser utilizados en HTML o css ya que no serían procesados. 

## 3. Conclusión<a name="id13"></a>
Markdown cuenta con una extensa sintaxis, acabamos de ver lo más básico de este lenguaje por lo que podemos deducir que se pueden hacer cosas más elaboradas como por ejemplo diagramadas de flujo o secuenciales, fórmulas matemáticas, hacer un índice etc. 
Aunque es un buen lenguaje de marcas tiene algunas limitaciones como no poder para especificar las dimensiones de una imagen, la mayoría de este tipo de carencias se pueden solventar gracias a que podemos convinar este lenguaje con HTML y css. 

