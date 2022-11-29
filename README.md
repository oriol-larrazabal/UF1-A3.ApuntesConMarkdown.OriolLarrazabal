##### UF1-A3.ApuntesConMarkdown.OriolLarrazabal
# Quién soy?

Hola a todos! Soy Oriol Larrazábal, alumno de ASIX 1. A continuación os presento mis apuntes con Markdown del módulo lenguaje de marcas! Espero que os gusten!

[Oriol Larrazábal](https://github.com/oriol-larrazabal "Perfil GitHub")

# Apuntes con Markdown!

### Primeros pasos

Los primeros pasos que hemos llevado a cabo han sido la instalación de GIT, Visual Code Studio y la creación de nuestra cuenta en GitHub.

### Instalación de GIT

>Git es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente.

Para descargarlo hemos accedido a la página web de GIT, y nos hemos descargado la versión de 64 bits. 
[GIT](https://git-scm.com/ "GIT")

![capt 1 - apmd](https://user-images.githubusercontent.com/113420705/193620980-203cf5a4-61b5-445f-8c5d-75ff68831667.png)

### Instalación de Visual Studio Code

>Visual Studio Code es un editor de código fuente desarrollado por Microsoft para Windows, Linux, macOS y Web. Incluye soporte para la depuración, control integrado de Git, resaltado de sintaxis, finalización inteligente de código, fragmentos y refactorización de código.

Para descargarlo hemos accedido a la página web de Visual Studio code, y nos hemos descargado la versión de 64 bits.
[Visual Studio Code](https://code.visualstudio.com/ "Visual Studio Code")

![capt 3 - apmd](https://user-images.githubusercontent.com/113420705/193621791-a3392f9d-3b37-498b-8779-588fe4213c6b.png)

### GitHub
>GitHub es una forja para alojar proyectos utilizando el sistema de control de versiones Git. Se utiliza principalmente para la creación de código fuente de programas de ordenador. El software que opera GitHub fue escrito en Ruby on Rails. Desde enero de 2010, GitHub opera bajo el nombre de GitHub, Inc.

Esta web nos permitirá crear y almacenar los diferentes repositorios que vayamos haciendo en clase. Además, a través del CMD de nuestro ordenador podemos crear una cópia local para trabajar y una vez finalizada, o modificada, resubirlo a la rama que nos interese en GitHub. Los diferentes comando que utilizaremos en el CMD serán estos: [Lista de comandos GITHUB-CMD](https://gist.github.com/dasdo/9ff71c5c0efa037441b6 "Lista de comandos GITHUB-CMD")

Sobretodo, uno de los grandes problemas que hemos tenido al crear la cuenta ha sido al configurarlo con nuestro PC. Así que recomiendo que se preste mucha atención a los dos primeros puntos del enlace.

![capt 2 - apmd](https://user-images.githubusercontent.com/113420705/193621834-9c9c9615-4b03-42ac-b57d-84d30e6e71dd.png)

Además, dejo este manual introductorio por si existen dudas : [Manual GITHUB](https://www.uco.es/aulasoftwarelibre/wp-content/uploads/2015/11/git-cosfera-dia-1.pdf "Manual GITHUB")


### MARKDOWN!

El primer lenguaje de marcas que hemos visto en clase es Markdown. Es más, es el que estoy escribiendo ahora y el que me servirá de guía para mis apuntes. Pero como definiríamos a Markdown. Pues bien, Markdown es: 
>Un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial. En principio, fue pensado para elaborar textos cuyo destino iba a ser la web con más rapidez y sencillez que si estuviésemos empleando directamente HTML. Y si bien ese suele ser el mejor uso que podemos darle, también podemos emplearlo para cualquier tipo de texto, independientemente de cual vaya a ser su destino.

>John Gruber creó el lenguaje Markdown en 2004, con una ayuda importante de Aaron Swartz en la sintaxis. Gruber tenía la meta de hacer que la gente «pudiera escribir usando un formato de texto llano fácil de leer, fácil de escribir y con la posibilidad de convertir su documento en HTML válido». La clave del diseño de Markdown es la facilidad de su lectura, que hace que el lenguaje sea fácilmente interpretado, sin lucir como si hubiera sido marcado con etiquetas o instrucciones de estilo, como RTF o HTML, los cuales tienen etiquetas que hacen más difícil su lectura e interpretación. Por ello, su inspiración más importante son las convenciones existentes para formatear texto llano en los mensajes electrónicos, aunque también toma características de lenguajes anteriores, como setext, atx (por Aaron Swartz), Textile, reStructuredText, Grutatext, y EtText).

![john-gruber-and-aaron-swartz-photo-from-wiki](https://user-images.githubusercontent.com/113420705/194956175-05b28618-81ff-4a7b-8fbf-782e9122e5e0.jpg)

De Markdown hemos visto:

a) Los diferentes encabezados

En Markdown podemos utilizar hasta 6 diferentes encabezados, que van de mayor a menor tamaño. Para introducir un encabezado sólo tenemos que introducir una almohadilla o hashtag al principio de nuestro párrafo. Según el número de almohadillas que introduzcamos el encabezado será mayor o menor. 

Así se verán nuestros encabezados:
# Encabezado1
## Encabezado2
### Encabezado3
#### Encabezado4
##### Encabezado5
###### Encabezado6

b) Cómo introducir cursiva/negrita

Para resaltar una palabra o poner enfásis en una frase, Markdown nos permite utilizar negritas o cursivas, incluso combinarlas. Por un lado, para remarcarlo con negrita introduciremos dos barras bajas al principio y al final, como por ejemplo __HOLA__. Por otro lado, si queremos utilizar cursivas lo marcaremos con un astérisco al principio y al final de la palabra o frase, como por ejemplo *hola*. Si queremos combinar ambos códigos, como sería el siguiente ejemplo. __*HOLA MUNDO*__

c) Cómo crear listas 

Otra característica del lenguaje Markdown es que podemos crear listas, tanto ordenadas como desordenadas. En primer lugar, para crear una lista ordenada tendremos que introducir un asterísco o un guión. 


d) Cómo introducir imágenes

A su vez, Markdown nos permite introducir imágenes. Para introducir una imágen debemos poner un signo de exclamación y escribir el texto alternativo de la imagen entre corchetes y el URL que dirige a la imagen entre paréntesis.

Como por ejemplo:
![google](https://user-images.githubusercontent.com/113420705/191205772-9891401d-f84d-4d89-bf7a-7c4130f8d378.png)

e) Cómo introducir hipervínculos

Para crear un hipervínculo sólo tenemos que poner entre corchetes el texto del enlace seguido de la URL entre paréntesis.

Por ejemplo: [Enlace a wikipedia](https://es.wikipedia.org "Haciendo click vas a la WIKIPEDIA")

f) Cómo crear tablas

Para finalizar, tambien nos permite crear tablas. Para crar una tabla tenemos que introducir "|" el texto y en la segunda línea el como queremos alinear el texto, podemos verlo
- ----------: --> centrado
- :----------- --> alineado a la izquierda 
- -----------: --> alineado a la derecha

La siguiente tabla nos servirá de ejemplo:

| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| :----------- | :----------: | -----------: |
| Item1        | Bolígrafos   | 20           |
| Item2        | Lápices      | 50           |
| Item3        | Grapadoras   | 80           |

En el siguiente enlace os dejó un vídeo de introducción a Markdown: [Tutorial introductorio a Markdown](https://www.youtube.com/watch?v=oxaH9CFpeEE&ab_channel=FaztCode "Haciendo click vas al videtutorial.")

### HTML

>El origen de HTML se remonta a 1980, cuando el físico Tim Berners-Lee, trabajador del CERN (Organización Europea para la Investigación Nuclear) propuso un nuevo sistema de "hipertexto" para compartir documentos.

![1366_2000](https://user-images.githubusercontent.com/113420705/194956474-92d66862-8fa8-4580-bbc0-a1df77ac4c3a.jpg)


>HTML (Lenguaje de Marcas de Hipertexto, del inglés HyperText Markup Language) es el componente más básico de la Web. Define el significado y la estructura del contenido web. Además de HTML, generalmente se utilizan otras tecnologías para describir la apariencia/presentación de una página web (CSS) o la funcionalidad/comportamiento (JavaScript).

HTML es el segundo lenguaje de marcas que hemos visto. HTML se define como un lenguaje de marcas estándard para crear páginas web y su código es:
Este será siempre el primer paso de nuestro trabajo.

```HTML
  
<!DOCTYPE html>
<html lang= "en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <title>Document</title>
</head>
<body>
  
</body>
</html>

```
El _HEAD_ es la cabecera de nuestro ficero HTML. Esta parte no se ve cuando la carga nuestro navegador y en ella esta la información como el título, que lo ubicaremos dentro del <title>, enlaces al CSS, si queremos aplicar estilo a nuestro código HTML, personalizar el favicon, cambiar el charset, para que nuestro código HTML entienda determinados carácteres, como acentos, podemos activar scripts, como por ejemplo, cuando agregamos el código .js personal que nos otorga *Font Awesome* para introducir diferentes *favicons*.

En el _BODY_ podemos editar el cuerpo de nuestro archivo. En el podemos:
  - Introducir párrafos a través del comando ``<p> texto </p>``
  - Crear hipervínculos de páginas web gracias al comando: ``<a href="https://google.es" Ejemplo de URL </a>``
  - Introducir imágenes gracias al comando: ``<img src="https://user-images.githubusercontent.com/113420705/193840496-f97e6ad7-8d93-470b-8967-9ea393c5f659.png"> alt="Ejemplo de IMG">``
  - Crear listas ordenadas, con el comando ``<ol>``, y poniendo ``<li>``en cada elemento. 
  - Crear listas desordenadas, con el comando ``<ul>``, y poniendo ``<li>`` en cada elemento.
  
### Ejemplo de código HTML aplicando todos los conceptos:
  
  Adjunto este código creado por mi mismo aplicando todos los diferentes conceptos que hemos visto en HTML hasta el momento.
  
  [Ejemplo de código HTML](https://mega.nz/file/aRhyQYTT#nck7OZgis6_b1-4NV4IzjsvBsRW1qhQ58MWm52J55fk "Ejemplo de código HTML")
  
### CSS
  
  >CSS es el lenguaje de estilos utilizado para describir la presentación de documentos HTML o XML (en-US) (incluyendo varios languages basados en XML como SVG, MathML o XHTML). CSS describe como debe ser renderizado el elemento estructurado en la pantalla, en papel, en el habla o en otros medios. En resumen, CSS nos permite personalizar a nuestro gusto como se verá nuestro documento, es la parte que se encarga más del diseño.
 
 ![aprender-css](https://user-images.githubusercontent.com/113420705/194956966-8df737b7-7dfe-418d-a9fa-22514201687a.jpg)
  
  >La propuesta CHSS fue realizada por Håkon Wium Lie y SSP fue propuesto por Bert Bos. Entre finales de 1994 y 1995 Lie y Bos se unieron para definir un nuevo lenguaje que tomaba lo mejor de cada propuesta y lo llamaron CSS (Cascading Style Sheets).
  
 ![maxresdefault](https://user-images.githubusercontent.com/113420705/194956900-4ba6ede9-845b-4628-838c-5e6827ad484e.jpg)
  
 Los detalles que hemos visto hasta el momento más importantes son:
 - Selector de elementos - Corresponde con todos los elementos de este nombre en la página.
 - Selector de clase - Corresponde con todos los elementos que tengan el atributo class con el valor especificado.
 - Selector de id -Corresponde a todos los elementos HTML que tienen un atributo id con el valor especificado.
 - Selectores universales - Sirven para seleccionar todos los elementos de la página. En el  ejemplo, todos los elementos han de tener un borde solido negro de un pixel:
 - Selectores de atributos - Permiten seleccionar elementos en función de los atributos que contienen.
 - Selectores de hijos - Para seleccionar elementos concretos que son hijos DIRECTOS de otros elementos concretos.
 - Selectores de descendientes - Similar al selector de hijos pero, a diferencia de ellos, que solo seleccionan elementos descendientes DIRECTOS, los selectores de descendientes seleccionan los elementos pertinentes EN CUALQUIER PUNTO de la jerarquía del elemento.
 - Pseudoclases - Se utilizan para definir estilos, no para los elementos sino para los diversos estados de los elementos.
 - Pseudoelementos - Como las pseudoclases no afectan a todo el elemento sino que permiten añadir estilos a UNA PARTE CONCRETA del documento.
 - Composición - Muchos elementos HTML como <div> o los títulos se representan por defecto de forma que ocupen todo el ancho del navegador y fuercen un salto de línea terminal. El control del espacio en blanco en las hojas de estilo predeterminadas en los navegadores no es adecuado en la mayoría de los casos con lo que los especialistas en estilos acostumbran a usar a menudo los margenes (margin), bordes (border) y relleno (padding) y otras propiedades CSS que ayudan a componer el documento de forma adecuada.

 - Margen (margin) Representan el área transparente que rodea la caja. Es decir, el espacio que la separará de los elementos contiguos. La propiedad margen se puede desplegar a su vez en cuatro propiedades además del valor “margin” como propiedad global: top, bottom, right, left. Las 4 propiedas son píxeles, porcentaje, automático, como referencia del valor del font-size del elemento actual o del html.
 - Bordes (border). Representan el estilo que tendrán los bordes del elemento: border: [border-width || border-style || border-color | inherit] ;
 - Relleno (padding). Espacio entre el borde del elemento y su contenido. De la propiedad “padding” se derivan al igual que las otras propiedades anteriores en cuatro propiedades específicas a los cuatro lados, padding-top, padding-right, padding-bottom y padding-left.
 - Google Fonts - Podemos editar la fuente de nuestro documento a partir de Google Fonts. Una herramienta de Google que nos permite utilizar una gran variedad de fuentes, sin necesidad de descargarnoslas en nuestro ordenador. Un ejemplo sería:
  
  ``<!doctype html>
<html>
    <head>
        <!-- Inserción de origen de fontawesome-->
        <script src="https://kit.fontawesome.com/09f87768b9.js" crossorigin="anonymous"></script>
        <!-- Opción 1 para insertar Google Fonts -->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
         <link href="https://fonts.googleapis.com/css2?family=Edu+VIC+WA+NT+Beginner:wght@400;500&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
        <!-- Opción 2 para insertar Google Fonts, el @import se puede poner en un archivo css externo -->
        <style>
            @import url('https://fonts.googleapis.com/css2?family=Edu+VIC+WA+NT+Beginner:wght@400;500&family=Roboto:wght@400;500&display=swap');
        </style>
     </head>
    <body>
        <!-- Elemento de Fontawesome-->
        <i class="fa-solid fa-arrow-right-to-bracket fa-2xl"></i> 
        <!-- Insertar estilo de Google Fonts-->
        <p style="font-family: 'Edu VIC WA NT Beginner', cursive; font-size:30px" >chess game</p>
    </body>
</html>``

  
 En los dos próximos links os dejo, por un lado una web que me ha ayudado mucho con CSS, y, por otro, un tutorial de introducción a CSS como repaso.
  
[Foro Códigos más importantes CSS](https://www.eniun.com/que-es-css-cascading-style-sheets "CSS")
[Vídeo tutorial introducción a CSS](https://www.youtube.com/watch?v=24gNhTcy6pw&ab_channel=FalconMasters "Vídeo tutorial introducción CSS")
  
 Además, incluyo este código

### Responsive
  
  >El diseño web responsive o adaptativo es una técnica de diseño web que busca la correcta visualización de una misma página en distintos dispositivos. Desde ordenadores de escritorio a tablets y móviles. Se trata de redimensionar y colocar los elementos de la web de forma que se adapten al ancho de cada dispositivo permitiendo una correcta visualización y una mejor experiencia de usuario. Se caracteriza porque los layouts (contenidos) e imágenes son fluidos y se usa código media-queries de CSS3.
  
[Vídeo tutorial introducción a Responsive](https://www.youtube.com/watch?v=OPo3-mQ8wdY&ab_channel=KODOTI "Vídeo tutorial introducción a Responsive")

### Prácticas 
  
  En el siguiente apartado voy a enlazar todas las prácticas para tenerlas a mano a la hora de repasar o estudiar. Así haremos unos apuntes que sean prácticos a la vez.
  
  + Práctica 1 - Repaso GitHub
  
   [Enlace a Práctica 1](https://github.com/oriol-larrazabal/RepasoGitHub "Enlace a práctica 1")
  
  + Práctica 2 - Mi primer HTML
  
   [Enlace a Práctica 2](https://github.com/oriol-larrazabal/ASIX1_M4UF1A4_primer_HTML_LarrazabalOriol "Enlace a práctica 2")
  
  + Práctica 3 - UF1-A2.DocumentarConMarkdown.OriolLarrazabal
  
   [Enlace a Práctica 3](https://github.com/oriol-larrazabal/UF1-A2.DocumentarConMarkdown.OriolLarrazabal "Enlace a práctica 3")
  
  + Práctica 4 - UF1A4_OriolLarrazabal_menusaludable
  
   [Enlace a Práctica 4](https://github.com/oriol-larrazabal/UF1A4_OriolLarrazabal_menusaludable "Enlace a práctica 4")
  
  + Práctica 5 - UF1A5_OriolLarrazabal_evaluable
  
   [Enlace a Práctica 5](https://github.com/oriol-larrazabal/ASIX1_M4UF1_A6_LarrazabalOriol- "Enlace a práctica 5")
  
  + Práctica 6 - ASIX1_M4UF1A6_Selectores_CSS_OriolLarrazabal
  
   [Enlace a Práctica 6](https://github.com/oriol-larrazabal/ASIX1_M4UF1A6_Selectores_CSS_OriolLarrazabal "Enlace a práctica 6")
  
  + Práctica 7 - ASIX1_M4UF1A7_DoItYourself_OriolLarrazabal
  
   [Enlace a Práctica 7](https://github.com/oriol-larrazabal/ASIX1_M4UF1A7_DoItYourself_OriolLarrazabal "Enlace a práctica 7")
   
  + Práctica 8 y 9 - Clones de Do it Yourself
  
  [Enlace a Práctica 8](https://github.com/oriol-larrazabal/https-github.com-ChristianMonrabal-ASIX1_M4UF1_Do-it-yourself_CLON4_ORIOLLARRAZABALgit "Enlace a práctica 8")
  
  [Enlace a Práctica 9](https://github.com/oriol-larrazabal/https-github.com-JoanBecerril-ASIX1_M4UF1_DoItYourself_CLON3_OriolLarrazabal "Enlace a práctica 9")
  
  ### PROYECTO
  
  Cómo proyecto, estoy realizando con algunos compañeros una página web que englobe todos los apuntes de las diferentes asignaturas. Espero que os guste :P
  
  ![capt5-apmd](https://user-images.githubusercontent.com/113420705/203294370-ef7c2681-c0fe-48bd-86ad-3e78d092c697.png)

  [Enlace a WEB PROYECTO](https://github.com/oriol-larrazabal/Apuntes_Asix1 "ENLACE A WEB PROYECTO")
