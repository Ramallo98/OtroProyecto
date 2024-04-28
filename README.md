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

  - [Creación de una tabla](#creación-de-una-tabla)

  - [Formatear el contenido dentro de tu tabla](#formatear-el-contenido-dentro-de-tu-tabla)

  - [Creación de una sección contraída](#creación-de-una-sección-contraída)
  
  - [Crear y resaltar bloques de código](#crear-y-resaltar-bloques-de-código)
    - [Bloques de código delimitados](#bloques-de-código-delimitados)
    - [Resaltado de sintaxis](#resaltado-de-sintaxis)
  
  - [Crear diagramas](#crear-diagramas)
  
  [Crear diagramas de Mermaid](#crear-diagramas-de-mermaid)
  Cómo crear diagramas utilizando la sintaxis de Mermaid.
  
  [Escritura de expresiones matemáticas](#escritura-de-expresiones-matemáticas)
  
  [Referencias y direcciones URL autovinculadas](#referencias-y-direcciones-url-autovinculadas)
  
   [Adjuntar archivos](#adjuntar-archivos)


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
Se puede mencionar a una persona o equipo en GitHub. Para ello, se escribe `@` junto con su nombre de usuario o equipo. Esto activará una notificación y llamará su atención hacia la conversación. Pero esto solo funciona si el usuario o equipo tiene acceso de lectura al repositorio y, si el repositorio pertenece a una organización, el usuario es miembro de la organización.

@github/samuelseoane Recuerda que la entrega del documento README es el 28/04/2024.


## Hacer referencia a propuestas y solicitudes de extracción
Para hacer referencia a una solicitud de extracción, se usa el número de identificación de la solicitud de extracción precedido por el signo de almohadilla `#`. 

## Hacer referencia a recursos externos
Si se configuran las referencias autovinculadas personalizadas para un repositorio, entonces las referencias a recursos externos, como un informe de problemas de JIRA o un ticket de Zendesk, se convertirán en vínculos acortados. 

Prefijo de referencia: `JIRA-`

URL de destino: `https://jira.example.com/issue?query=<num>`

Versión preliminar: `JIRA-123` se convierte en `https://jira.example.com/issue?query=123`

## Cargar activos
Se puede cargar activos como imágenes si las arrastras y sueltas, las seleccionas de un buscador de archivos o si las pegas. Se puede cargar recursos en las incidencias, solicitudes de incorporación de cambios, comentarios y archivos `.md` en el repositorio.

![1699535484187](https://github.com/Ramallo98/OtroProyecto/assets/151021729/7e31c84d-e95f-4e96-a4b4-fcfe27ccc0b0)


## Usar emojis
Puedes agregar emoji a la escritura escribiendo `:EMOJICODE:`, dos puntos seguidos del nombre del emoji.

Este trabajo es un poco llevadero :face_exhaling:, pero es una buena manera :ok_hand: de practicar markdown con Github, y con esto me despido de este apartado :wave:. 

## Párrafos
Se puede crear un nuevo párrafo si dejamos una línea en blanco entre las líneas de texto.

La hipótesis de que el mundo que percibimos (si no nuestra existencia misma) es una simulación digital es el punto de partida de las películas de la saga Matrix. No es de extrañar por tanto que uno de los libros en los que se defiende esta hipótesis lleve como título un aparente guiño a la saga, Reality Reloaded.

Su autor, el físico de la Universidad de Portsmouth Melvin M. Vopson, explicaba hace unos meses su defensa de esta hipótesis en un artículo en The Conversation. Vopson describe en este artículo esta hipótesis como “inherentemente especulativa”, a pesar de lo cual considera tener indicios de su veracidad.

Pero, ¿cómo encontrar pruebas de algo así? Si bien para muchos defensores de esta idea la clave está en la búsqueda de fallos que puedan revelarnos la naturaleza real del universo, para Vopson la clave está en las leyes de la física, así como en la materia y sus formas.

El autor defiende por ejemplo la información como forma de la materia. Es decir, igual que la materia no se crea ni se destruye pero puede transformarse entre distintas fases e incluso en energía, ésta podría, hipotéticamente, transformarse en algo aparentemente muy distinto: información.

Partiendo de esto y de disciplina conocida como teoría de la información, Vopson postula su segunda ley de la infodinámica. Esta trata de explicar la entropía de la información en paralelo a la entropía “física”, tal y como la comprendemos en la segunda ley de la termodinámica.

“En el corazón de la infodinámica está el concepto de entropía (una medida de desorden, que siempre crece en el tiempo en un sistema aislado).” La segunda ley postulada por Vopson habla de la entropía de la información. Esta, entendida como la cantidad promedio de información vinculada a un evento, “debe permanecer constante o decrecer a lo largo del tiempo”, al menos hasta alcanzar un valor de equilibrio.

Más que paralelas, las segundas leyes de la termodiámica e infodinámica podrían verse como simétricas: la energía y la materia tienden al desorden, la información, en cambio, tendería al orden.

Vopson pone la evolución como ejemplo de la disminución de la entropía informativa. Tras estudiar las mutaciones en el virus que causó la pandemia de Covid, el SARS-CoV-2, el físico llegó a la conclusión de que las mutaciones no ocurren, como indica el consenso científico, de forma aleatoria, sino que responderían a esta necesidad de ordenar.

Esto también explicaría una aparente incongruencia: que un universo en constante expansión en el que el calor ni aumenta ni desaparece, en ese sentido de entropía constante, pueda encajar como sistema aislado y por tanto de entropía creciente. Vopson explica esto añadiendo la información y su entropía decreciente a la ecuación, de forma que ambas se cancelan entre sí, dando lugar a la entropía universal constante.

Más allá de este modelo teórico, las pruebas son escasas. Inferir una entropía evolutiva negativa a partir de la evolución de organismos en la Tierra, un sistema abierto y no aislado plantea dudas evidentes.


## Notas al pie
Se pueden agregar notas al pie utilizando `^` y un número entre corchetes `[]`. La información de la nota se especifica de la misma forma agregando dos puntos `:`.

Trabajo de contornos[^1]

[^1]: Trabajo sobre formato de escritura en github.

## Alertas
Las alertas son una extensión Markdown basada en la sintaxis blockquote que puede utilizar para resaltar la información crítica. En GitHub, se muestran con colores e iconos distintivos para indicar la importancia del contenido.

Para agregar una alerta, debe usarse una línea blockquote especial que especifique el tipo de alerta, seguida de la información de alerta en un blockquote estándar. Existen cinco tipos de alertas.

> [!NOTE]
> Información útil que los usuarios deben conocer, incluso cuando hojean el contenido.

> [!TIP]
> Consejos útiles para hacer las cosas mejor o más fácilmente.

> [!IMPORTANT]
> Información clave que los usuarios necesitan saber para lograr su objetivo.

> [!WARNING]
> Información urgente que necesita atención inmediata del usuario para evitar problemas.

> [!CAUTION]
> Asesora sobre riesgos o resultados negativos de determinadas acciones.

## Ocultar el contenido con comentarios
Puedes decirle a GitHub que oculte el contenido del lenguaje de marcado interpretado colocando el contenido en un comentario de HTML `<!-- -->`.

Prueba para ocultar contenido: <!-- Primer curso DAM -->

## Ignorar formato de Markdown
Puede pedirle a GitHub que ignore (u omita) el formato de Markdown escribiendo `\` antes del carácter de Markdown.

**Esto obedece el Markdown**, \*pero ahora lo estamos ignorando\*

## Inhabilitar la representación del lenguaje de marcado
Cuando se ve un archivo de lenguaje de marcado, puede hacer clic en el Código en la parte superior de este para inhabilitar la representación de lenguaje de marcado y ver el código fuente del archivo.

# Sintaxis avanzada


## Creación de una tabla
Puede crear tablas con canalizaciones | y guiones -. Los guiones se usan para crear cada encabezado de columna, mientras que las barras verticales separan cada columna. Debes incluir una línea en blanco antes de tu tabla para que se representen correctamente.

| Asignaturas | Notas |
| ------------| ------ |
| Sistemas Informaticos | 5 |
| Contornos de desarrollo  | 5 |

## Formatear el contenido dentro de tu tabla
Se puede usar formatos, como vínculos, bloques de código insertados y estilos de texto en la tabla.

Tambien se puede alinear el texto a la izquierda, a la derecha o en el centro de una columna al incluir dos puntos `:` a la izquierda, a la derecha o a ambos lados de los guiones en la línea de encabezamiento.

| Asignaturas | Notas | Examenes |
| :---------- | :---: | -------: |
| `Sistemas Informaticos` | *5* | 2 |
| ***Contornos de desarrollo***  | **5** | 1 |

## Creación de una sección contraída
Cualquier Markdown dentro del bloque `<details>` se contraerá hasta que el lector haga clic para expandir los detalles.

Dentro del bloque `<details>`, usa la etiqueta `<summary>` para que los lectores sepan lo que hay dentro. 
<details>
<summary>La inteligencia artificial provocará un aumento en la demanda de PC</summary>

La moda de la inteligencia artificial (IA) apunta aumentar la demanda de PC en los próximos años. Esta posible tendencia queda reforzada por un informe publicado por la empresa de estudio de mercado Canalys, que ha pronosticado una la alta demanda derivada de la expansión de la inteligencia artificial.

Quienes sigan las tendencias del mercado sabrán que la principal excusa para renovar PC en los próximos años serán las unidades de procesamiento neuronal (NPU), las cuales están dedicadas expresamente para acelerar mediante hardware el procesamiento de inteligencia artificial. Según Canalys, el 19% de los PC que se enviarán en el presente año 2024 tendrán la capacidad de procesar inteligencia artificial, un porcentaje que subirá hasta el 60% para el año 2027.

La analista ve que tanto Microsoft como Apple están dando forma al mercado del PC con IA a través de estrategias híbridas que abarcan la propia inteligencia artificial y sus ecosistemas. Sin embargo, y a pesar de reconocer la revolución tecnológica que está a la vuelta de la esquina, Canalys también menciona aspectos como la resistencia de ciertos usuarios y ciertas preocupaciones éticas que han surgido en torno a la IA, que deben superarse si se quiere que esta transición logre ser un éxito.

Algunos aspectos que menciona la empresa de análisis en torno a la IA son la mejora de la experiencia de usuario y las consideraciones a nivel de privacidad, algo en lo que no ayuda el hecho de que Windows y macOS sean software privativo. Para que la expansión de la inteligencia artificial sea exitosa, la cantidad de aplicaciones que se apoyan en esta debe aumentar en un futuro para así incrementar la demanda.

Pese a las cuestiones planteadas, Canalys pronostica que más de la mitad de los PC con capacidades para IA enviados en 2025 irán dirigidos al mercado comercial, que para el 2027 terminaría por superar en demanda al de consumo. Este aumento de la demanda estaría impulsado principalmente a través de fabricantes de hardware como NVIDIA, AMD, Intel y Qualcomm, que sentarían la base del soporte; Windows y macOS como los dos principales sistemas operativos para escritorio, que incluirán los marcos, los controladores y las API necesarios para cubrir esa área; y por último estarían las aplicaciones, tanto las orientadas de empresa a empresa (B2B) como de empresa a consumidos (B2C), que exprimirían las bases anteriores por los dos anteriores.

No son pocas las voces que anuncian un aumento en la demanda de PC gracias a la inteligencia artificial. De hecho, los precios de los componentes ya están están subiendo, incluyendo los discos duros, que son una tecnología que está obsoleta desde hace años debido a que representa un acusado cuello de botella en los ordenadores modernos, si bien siguen siendo una opción más atractiva para muchos que necesitan tener una altísima capacidad de almacenamiento.

</details>

## Crear y resaltar bloques de código

### Bloques de código delimitados
Puede crear bloques de código delimitados colocando comillas simples triples ``` antes y después del bloque de código. Si se quiere mostrar las comillas triples  podemos encerrarlas entre comillas cuádruples ````.

### Resaltado de sintaxis
```

public class HolaMundo {
    public static void main(String[] args) {
        // Imprime "Hola Mundo" en la consola
        System.out.println("Hola Mundo");
    }
}

```

````
```
public class HolaMundo {
    public static void main(String[] args) {
        // Imprime "Hola Mundo" en la consola
        System.out.println("Hola Mundo");
    }
}
```
````

## Crear diagramas

## Crear diagramas de Mermaid

## Escritura de expresiones matemáticas

## Referencias y direcciones URL autovinculadas

## Adjuntar archivos





