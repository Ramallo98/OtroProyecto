# Sintaxis de escritura con markdown en archivos README.md 

## Indice
1. [Archivo README](#archivo-readme)

2. [Sintaxis Básica](#sintaxis-básica)
  - [Encabezados](#encabezados)

  - [Estilo de texto](#estilo-de-texto)

  - [Citado de texto](#citado-de-texto)
  
  - [Código de cita](#código-de-cita)
  
  - [Modelos de color compatibles](#modelos-de-color-compatibles)
  
  - [Vínculos](#vínculos)
  
  - [Enlaces de sección](#enlaces-de-sección)
  
  - [Vínculos relativos](#vínculos-relativos)
  
  - [Imágenes](#imágenes)
    -[Especificar un tema en el que se muestra una imágen](#especificar-un-tema-en-el-que-se-muestra-una-imágen) 

  - [Listas](#listas)
    - [Listas anidadas](listas-anidadas)
      
  - [Listas de tareas](listas-de-tareas)
  
  - [Mencionar personas y equipos](#mencionar-personas-y-equipos)
  
  - [Hacer referencia a propuestas y solicitudes de extracción](#hacer-referencia-a-propuestas-y-solicitudes-de-extracción)
  
  - [Hacer referencia a recursos externos](#hacer-referencia-a-recursos-externos)
  
  - [Cargar activos](#cargar-activos)
  
  - [Usar emojis](#usar-emojis)
  
  - [Párrafos](#párrafos)
  
  - [Notas al pie](#notas-al-pie)
  
  - [Alertas](#alertas)
  
  - [Ocultar el contenido con comentarios](#ocultar-el-contenido-con-comentarios)
  
  - [Ignorar formato de Markdown](#ignorar-formato-de-markdown)
  
  - [Inhabilitar la representación del lenguaje de marcado](#inhabilitar-la-representación-del-lenguaje-de-marcado)

3. [Sintaxis avanzada](#sintaxis-avanzada)

## [Creación de una tabla](#creación-de-una-tabla)

## [Formatear el contenido dentro de tu tabla](#formatear-el-contenido-dentro-de-tu-tabla)

## [Creación de una sección contraída](#creación-de-una-sección-contraída)

## [Crear y resaltar bloques de código](#crear-y-resaltar-bloques-de-código)

## [Bloques de código delimitados](#bloques-de-código-delimitados)

## [Resaltado de sintaxis](#resaltado-de-sintaxis)

## [Crear diagramas](#crear-diagramas)

## [Crear diagramas de Mermaid](#crear-diagramas-de-mermaid)
Cómo crear diagramas utilizando la sintaxis de Mermaid.

## [Escritura de expresiones matemáticas](#escritura-de-expresiones-matemáticas)

## [Referencias y direcciones URL autovinculadas](#referencias-y-direcciones-url-autovinculadas)

## [Adjuntar archivos](#adjuntar-archivos)


# Archivo README

Un archivo README es un documento que generalmente se encuentra en un proyecto de software o en un repositorio de código fuente. Este archivo suele contener información importante sobre el proyecto, como instrucciones de instalación, configuración, uso y contribución. Además, puede incluir detalles sobre la licencia del software, la estructura del proyecto, los requisitos del sistema, la documentación adicional y cualquier otra información relevante para los usuarios y desarrolladores que trabajan con el proyecto. El README es una herramienta fundamental para proporcionar orientación y contexto a quienes interactúan con el proyecto.

# Sintaxis Básica


## Encabezados
Para crear un encabezado, agrega entre uno y seis símbolos # antes del encabezado del texto. El número de # que utilices determinará el nivel jerárquico y el tamaño tipográfico del encabezado.

# Encabezado de primer nivel
## Encabezado de segundo nivel
### Encabezado de tercer nivel
#### Encabezado de cuarto nivel
##### Encabezado de quinto nivel

## Estilo de texto
Puedes indicar énfasis con texto en negrita, cursiva, tachado, o de subíndice o superíndice en los campos de comentarios y archivos .md.

##### El estilo Bold
El estilo bold usa esta sinxasis `** ** o __ __` pero tambien tiene métodos abreviados de teclado como pueden ser `Command + B en MAC y Ctrl + B para Windows y Linux`, **este texto está en negrita** y __este también pero con otra sintaxis__.

##### El estilo Cursiva
El estilo cursiva usa esta sinxasis `* * o _ _`, y tambien tiene métodos abreviados de teclado como pueden ser `Command + I en MAC y Ctrl + I para Windows y Linux`, *este texto está en cursiva* y _este también pero con otra sintaxis_.

##### El estilo Tachado
El estilo tachado usa esta sinxasis `~~ ~~`, y no tiene métodos abreviados de teclado, ~~este texto está tachado~~.

##### El estilo Cursiva en negrita y anidada
El estilo cursiva en negrita y anidada usa esta sinxasis `** ** y _ _`, y no tiene métodos abreviados de teclado, **este texto está en _cursiva y negrita anidada_**.

##### El estilo Todo en negrita y cursiva
El estilo todo en negrita y cursiva usa esta sinxasis `*** ***`, y no tiene métodos abreviados de teclado, ***este texto está en todo negrita y cursiva***.

##### El estilo Subscript
El estilo todo Subscript y cursiva usa esta sinxasis `<sub> </sub>`, y no tiene métodos abreviados de teclado, Este tipo de estilo se utiliza para poner <sub>subíndices</sub>.

##### El estilo Superscript
El estilo todo Superscript usa esta sinxasis `<sup> </sup>`, y no tiene métodos abreviados de teclado, Este tipo de estilo se utiliza para poner <sup>superíndices</sup>.


## Citado de texto
Para citar texto utilizamos el símbolo `>` .

> Esta actividad es un trabajo para la asignatura de Contornos del ciclo superior de Desarrollo de Aplicaciones Multiplaforma de 1º Curso.

## Código de cita
Puede indicar un código o un comando dentro de un enunciado con `comillas simples`. El texto dentro de las comillas simples no será formateado. También puedes presionar el método abreviado de teclado `Comando+E (Mac) o Ctrl+E (Windows o Linux)` para insertar las comillas simples de bloque de código en una línea de Markdown.

`Esta actividad es un trabajo para la asignatura de Contornos del ciclo superior de Desarrollo de Aplicaciones Multiplaforma de 1º Curso.`

Para formatear código o texto en su propio bloque distintivo, se utilizan `comillas triples`.

```
Comandos simples de git: 
git status
git add
git commit
```

## Modelos de color compatibles
Para resaltar los colores dentro de una oración usamos `comillas invertidas`. Un modelo de color admitido dentro de comillas invertidas mostrará una visualización del color.
Un modelo de color admitido no puede tener espacios iniciales o finales dentro de las comillas invertidas.
La visualización del color solo se admite en issues, pull request y discusiones por lo tanto en este archivo no funciona: `#000000`.

## Vínculos
Se puede crear un vínculo en línea colocando el texto del vínculo entre `corchetes []` y luego envolviendo la URL entre `paréntesis()`, y también se puede usar el metodo abreviado del teclado `Command+ K` para crear un enlace. 

También se puede crear un hipervínculo Markdown resaltando el texto y usando el método abreviado de teclado `Command+ V`. Si se desea reemplazar el texto con el enlace, use el método abreviado de teclado `Command+ Shift+ V`.

[Este es un enlace a mi Github](https://github.com/Ramallo98)


## Enlaces de sección
Se puede vincular directamente a una sección en un archivo representado si se desliza el puntero sobre el encabezado de la sección para exponer 🔗.

## Vínculos relativos
Los vínculos que comienzan por `/` serán relativos a la raíz del repositorio. Se pueden utilizar todos los operandos de vínculo relativos.

[Esto es un enlace relativo a un documento de mi repositorio](/archivo1.txt)

## Imágenes
Se puede mostrar una imagen agregando `!` y la informacion de la imagen en `[ ]`.  Luego, se escribe el vínculo de la imagen entre paréntesis `()`. GitHub tambien admite la inserción de imágenes en incidencias, solicitudes de incorporación de cambios, debates, comentarios y archivos .md.

![Ciclo superior DAM](https://www.monlau.com/formacio-professional/wp-content/uploads/sites/3/2020/03/gs-dam-es.jpg)
### Especificar un tema en el que se muestra una imágen
Se puede especificar el tema para el que se muestra una imagen en Markdown mediante el elemento `<picture>` de HTML en combinación con la característica de elementos multimedia `prefers-color-scheme`. Distinguimos entre modos de color oscuro y claro.

<picture>
<source srcset="https://img.freepik.com/vector-gratis/ilustracion-noche-verano-acuarela-columpio-arbol_23-2149459683.jpg?w=826&t=st=1714302182~exp=1714302782~hmac=d6b5d3cb0f27a1de5627bad6d482863d3fb5c4151e4abd24c7ff4cbcb547e2fb" media="(prefer-color-scheme: dark)">
<img src="https://img.freepik.com/vector-premium/dia-soleado-campo_104785-344.jpg?w=996" alt="Imagen Modo Claro">
</picture>

## Listas
Se pueden crear listas desordenadas o listas ordenadas.

Para crear una lista sin ordenar. Utilizaremos `-, * o +` antes del texto.

- Java
* Python
+ PHP

Para ordenar tu lista, antecede cada línea con un número.

1. Java
2. Python
3. PHP

### Listas anidadas
Se puede crear una lista anidada al dejar sangría en uno o más elementos de la lista debajo de otro elemento.
Escribe los caracteres con espacio frente al elemento de la lista anidada hasta que el carácter del marcador de lista `(- o *)` se encuentre directamente debajo del primer carácter del texto en el elemento que se encuentra debajo.
1. Java
  - Lenguaje Orientado a Objetos
    - Herencia, cohesión, abstracción, polimorfismo, acoplamiento y encapsulamiento

## Listas de tareas
Para crear una lista de tareas, hay que añadir como prefijo un guion y espacio, seguido de `[ ]` a los elementos de la lista. Para marcar una tarea como completada, use `[x]`.
- [x] Aprender Java
- [ ] Aprender Python
- [ ] Aprender PHP
  
## Mencionar personas y equipos


## Hacer referencia a propuestas y solicitudes de extracción


## Hacer referencia a recursos externos


## Cargar activos


## Usar emojis


## Párrafos


## Notas al pie


## Alertas


## Ocultar el contenido con comentarios


## Ignorar formato de Markdown


## Inhabilitar la representación del lenguaje de marcado


## Sintaxis avanzada


## Creación de una tabla


## Formatear el contenido dentro de tu tabla


## Creación de una sección contraída


## Crear y resaltar bloques de código

## Bloques de código delimitados

## Resaltado de sintaxis

## Crear diagramas

## Crear diagramas de Mermaid

## Escritura de expresiones matemáticas

## Referencias y direcciones URL autovinculadas

## Adjuntar archivos







Algunos comandos basicos en git son:
```
git status
git add 
git commit
```

The background color is `#ffffff` for light mode and `#000000` for dark mode.
