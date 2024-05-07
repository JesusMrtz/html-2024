# HTML5


## Introducción
**HTML** *(HyperText Markup Language)* es un lenguaje de marcado de hipertexto creado por *Tim Berners-Lee* que también creó el protocolo de comunicación HTTP que es fundamental para la comunicación de la World Wide Web, permitiendo la transferencia de información entre clientes (como navegadores web) y servidores web **(arquitectura cliente / servidor)** 



La **World Wide Web (WWW)**, comúnmente conocida como la web, es un sistema de información basado en internet que permite acceder a documentos vinculados entre sí a través de enlaces de hipertexto. Fue creado por Tim Berners-Lee en 1989 mientras trabajaba en el CERN, y se hizo público en 1991.

HTML es el lenguaje estándar utilizado para crear y diseñar páginas web. Se utiliza para estructurar el contenido de una página web mediante etiquetas y elementos que definen la jerarquía, el formato y los elementos interactivos de la página. HTML se compone de una serie de etiquetas que envuelven el contenido, como texto, imágenes, enlaces, formularios, etc. Estas etiquetas le dicen al navegador web cómo mostrar el contenido en la página. HTML trabaja en conjunto con otros lenguajes como CSS (Cascading Style Sheets) para definir el aspecto visual de la página, y JavaScript para agregar interactividad y dinamismo.


### Etiqueta `<head></head>`
en la etiqueta `<head></head>`van todos los datos que el navegador no muestra pero es importante para los buscadores como Google.

aqui normalmente se le agrega metadado que mayormente ayudan al posicionamiento SEO con la etiqueta `<meta>`, alguno que otro archivo css enlazado con la etiqueta `<link>`, etc.


la etiqueta `<meta charset="UTF-8">` habilita la codificación UTF-8 para que los caracteres especiales puedan ser vistos en la página web.


La etiqueta `<meta name="viewport" content="width=device-width, initial-scale=1.0">` fue creada por APPLE para que las páginas web puedan ser vistas en los dispositivos móviles y se adapten a ellos ya que el Iphone fue el primer teléfono con un navegador integrado.

La etiqueta `<title>Mi primera página web</title>` es el titulo de nuestra página web


### Etiquete `<body></body>`

En la etiqueta `<body></body>` va toda la información que se mostrará en el navegador web

### Atributos en las etiquetas
Los atributos son datos adicionales que contiene una etiqueta


## Mi primera página web

La web funciona con una arquitectura **cliente / servidor** donde el cliente es el navegador web que realiza peticiones y muestra la respuesta del servidor web, y el servidor despacha dichas peticiones.


### ¿Qué es el DOM?
El **DOM** son las siglas de *Document Object Model* y se refiere a toda la estructura de elementos de una página web.

### Tipos de elementos de HTML

#### Elementos de sección
`nav, aside, section, footer, etc.`

#### Elementos de agrupación
`figure, main, div`

#### Elementos de título
`h1, h2, h3, h4, h5, h6, hgroup`

#### Elementos de texto
`p, ul, ol, li, etc.`

#### Elementos incrustados (o embebidos)
`img, video, audio, etc.`

#### Elementos interactivos
`details`

#### Elementos de tablas
`table, td, th, etc.`

#### Elementos de formularios
`form, input, button`

#### Metadatos
`meta`


### Encabezados
Son las etiquetas `h1, h2, h3, h4, h5 y h6` son las encargadas de mostrar encabezados dentro de un documento HTML y se usan para marcar la estructura de una página web.

La etiqueta `<p></p>` solo sirve como bloque de texto.


### Etiquetas de sección
Son aquellas que agrupan como la etiqueta `header, main, footer, article, section, nav y aside`.


**La diferencia entre las etiquetas `article` y `section`** es que la etiqueta `article` agrupa un bloque de contenido independiente dentro de una página web.

Mientras que la etiqueta `section` es una división de un contenido mayor como si fueran capitulos.


`nav` es una etiqueta para agregar navegación (normalmente se usa dentro de la etiqueta header pero pueder ir donde sea dentro de una página web)

`aside` agrupa contenido secundario de una página web


### Elementos de bloque
Los elementos de bloque son todas las etiquetas que son capaces de usar todo el ancho de una página web **(aunque con CSS podemos manipular dicho comportamiento)**.

Dentro de los elementos de bloque van dentro las etiquetas de línea y nunca es de manera viceversa.

Los elementos de bloque por naturaliza son las etiquetas de encabezado, las etiquetas de sección, la etiqueta blockquote, la etiqueta pre, la etiqueta div.


`div` Es una etiqueta de bloque que no tiene semantica


### Elementos en linea
Los elementos de linea son todas las etiquetas que solo usan el ancho de una página web por el contenido que ellos tienen dentro.

las etiquetas inline van dentro de etiquetas de bloque y nunca van de manera viceversa.


`em` sirve para enfatizar un texto

`strong` sirve para indicar importancia

`time`

`kbd` sirve para indicar teclas del teclado

`sub` Muestra texto debajo

`sup` muestra text arriba de

`span` es una etiqueta en linea que no tiene semantica

`b` sirve para dar estilos en negrita

`i` Sirve para dar estilos de cursivas

`u` sirve para dar estilos de subrayado



## Enlaces y listas 

### Enlaces
`HTML` fue creado para enlazar documentos uno con otros y esos es gracias a los enlaces, esto es gracias con la etiqueta `<a href="detino del enlace">Contenido del enlace</a>`


### Atributos opcionales para los enlaces
* `target="_blank"`. Abre un enlace en una pestalla nueva *(Normalmente utilizado para los enlaces externos que no tienen nada que ver con tu página web)*
* `rel="nofollow"`. No le da SEO al destino del archivo
* `download`. Sirve para descargar archivos pero si el `href` el origien es dentro de nuestro servidor web.

#### Tipos de rutas

##### Rutas absolutas
Son las aquellas que inician con `https` ya que son únicas.

##### Rutas relativas
Son rutas dentro de nuestro servidor web que contiene nuestra página.


### Listas
En HTML hay dos tipos de listas:
* `ol`. Son listas ordenadas.
* `ul`. Son listas no ordenadas.
* `dl`. Son listas para definir termino

Para las listas de tipo `ol` o `li`, los items (es decir cada elemento de la lista ) se usa la etiqueta `li`


Para las listas `dl` que sirven para definir terminologías, para los items se necesitan las etiquetas `dt` *(Defination Term)* y `dd` *(Defination description)*
[Revisar el archivo de ejemplos de listas](04-ENLACES-LISTAS/listas/listas.html)


## Contenido Embebido
El aquel contenido que no es parte especificamente del código HTML, sino son recursos del exterior.


### Tipos de imágenes
En HTML soporta dos tipos de imagenes que son:

#### Vectoriales
Son matematicos ya que se crean con formulas y no tienen resolución ya que no se pixelean en ningún nivel de zoom.

Normalmente las imagenes vectoriales se usan en iconografias, logotipos, textos



#### De mapa de bits
Son millones de cuadrados de colores que juntos forman una imagen. A mas pixeles la imagen tendrá más calidad de la imagen. A cierto de nivel de zoom, la imagen se pixelea.

Normalmente las imagenes de mapa de bits se usan en las fotografías.

### Formato de imágenes.
* `SVG`. Es el formato vectorial para Web.
* `jpg, jpeg`. Para fotografías.
* `png`. Son para transparencias o colores planos.
* `gif`. Para imagenes con animaciones o videos muy cortos (menos de 10 segundos).
* `webp`. Combinan los mejor de jpg o png con menos pesos.
* `avif`. Tiene mejor compresión que `webp`
* `heif`. Es el formato de Apple para fotografías, pero no es recomendable para web.


### Insertar imagenes en HTML
PAra insertar una imagen se utiliza la etiqueta `<img src="direccionDeLaImagen" alt="DescripcionDeLaImagen">`


La etiqueta `<picture></picture>` inserta varias imagenes a la vez para que el navegador opte por mostrar el mas optimo para el navegador del dispositivo donde se está visualizando la página web.


La etiquete `<figure></figure>` sirve para mostrar cualquier elemento que rompa el flujo del contenido, puede ser:
* Un texto
* Una imagen
* Un pedazo de código
* Un video
* Etc.


### Audio
PAra insertar audio se utiliza la etiqueta `<audio></audio>`

### Video
Los videos que tienen mejor soporte en la web son los videos `.mp4`


### Embeber contenido


## Tablas
Es la forma de organizar la información en cuadriculas con la etiquete `<table></table>`.

Dentro de la etiqueta `table` va la etiqueta `<tr></tr>` *(table row)*.

Las celdas son las divisones de cada fila y se marcan con `<td></td>` *(table data)*.


SE usan los atributos **colspan=4** para agrupar las columnas y **rowspan=n** para agrupar columnas y en donde *n* es la cantidad de filas o columnas que se va a combinar o agrupar.


Para agrupar columans se utiliza e `<colgroup><col span=""><col></colgroup>`


## Formularios
Los formularios son elementos de HTML que nos permite recibir información de los usuarios