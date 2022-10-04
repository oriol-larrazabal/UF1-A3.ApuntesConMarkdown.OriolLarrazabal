##### UF1-A3.ApuntesConMarkdown.OriolLarrazabal
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


### MARKDOWN!

El primer lenguaje de marcas que hemos visto en clase es Markdown. Es más, es el que estoy escribiendo ahora y el que me servirá de guía para mis apuntes. Pero como definiríamos a Markdown. Pues bien, Markdown es: 
>Un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial. En principio, fue pensado para elaborar textos cuyo destino iba a ser la web con más rapidez y sencillez que si estuviésemos empleando directamente HTML. Y si bien ese suele ser el mejor uso que podemos darle, también podemos emplearlo para cualquier tipo de texto, independientemente de cual vaya a ser su destino.

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

Otra característica del lenguaje Markdown es que podemos crear listas, tanto ordenadas como desordenadas. En primer lugar, para crear una lista ordenada tendremos que introducir un asterísco y un guión. Como por ejemplo:


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

### HTML
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
  - Introducir párrafos a través del comando <p> texto </p>
  - Crear hipervínculos de páginas web gracias al comando: <a href="https://google.es" Ejemplo de URL </a>
  - Introducir imágenes gracias al comando: <img src="/img/ejemplo"> alt="Ejemplo de IMG">
  - Crar listas ordenadas, con el comando <ol>, y poniendo <li> en cada elemento. Un ejemplo sería: 
  <ol>
  <li>Elemento1</li>
  <li>Elemento2</li>
  ...
  <li>ElementoN</li>
</ol>
  - Crear listas desordenadas, como por ejemplo
  <ul>
  <li>Camisetas</li>
  <li>Gorras</li>
  <li>Sudaderas</li>
</ul>

