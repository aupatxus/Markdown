
![Data Science con IA](https://raw.githubusercontent.com/aupatxus/ONLINE_DS_THEBRIDGE_GitHub/refs/heads/main/Vital%20LANBIDE.png)

# Introducción a Git y GitHub: Guía Teórica Completa

Este repositorio contiene los fundamentos teóricos y prácticos de **Git** y **GitHub**, diseñado para servir como referencia rápida y documentación estructurada para proyectos de desarrollo de software y ciencia de datos.

---

## 1. Fundamentos de Git

### ¿Qué es Git?
**Git es un sistema de control de versiones distribuido**, gratuito y de código abierto. Está diseñado para gestionar desde proyectos pequeños hasta desarrollos de gran envergadura con alta velocidad y eficiencia operativa. 

Fue creado en 2005 por **Linus Torvalds** (creador de Linux) con el propósito inicial de rastrear los cambios en el código fuente durante el desarrollo del kernel de Linux. Actualmente, es el estándar de la industria y la herramienta de control de versiones más popular del mundo.

### ¿Por qué es Necesario?
El desarrollo de proyectos modernos va más allá de la escritura de código lineal. Git resuelve problemáticas críticas mediante:
*   **Historial y rastreo:** Registro meticuloso de cada modificación realizada en los archivos.
*   **Colaboración:** Permite que múltiples desarrolladores trabajen en el mismo proyecto simultáneamente sin pisar el trabajo ajeno.
*   **Experimentación segura:** Facilita la creación de ramas para probar nuevas características o realizar pruebas sin alterar el código de producción.
*   **Reversibilidad:** Capacidad de deshacer cambios o regresar a versiones anteriores de forma inmediata si se detectan errores.
*   **Utilidad en Data Science:** Es ampliamente adoptado por científicos y analistas de datos para el seguimiento de datasets, modelos de aprendizaje automático y notebooks de Jupyter.

### ¿Cómo Funciona Git internamente?
A diferencia de otros sistemas que guardan diferencias de archivos, **Git funciona mediante instantáneas (snapshots)**. 
*   Cada vez que se confirma un cambio (commit), Git toma una foto del estado de todos los archivos en ese momento exacto y guarda una referencia a ella.
*   Para optimizar el espacio, si un archivo no ha sufrido modificaciones, Git no vuelve a almacenar el archivo completo; simplemente crea un enlace o puntero hacia la versión idéntica anterior que ya tiene registrada.

---

## 2. Conceptos Estructurales de Git

Para dominar Git, es fundamental entender sus cuatro pilares o áreas de trabajo:

*   **Repositorio:** Es el contenedor o directorio del proyecto que Git está rastreando. Almacena todos los archivos del código junto con el historial completo de modificaciones y metadatos.
*   **Staging Area (Área de preparación):** Es un espacio virtual o zona intermedia donde se agrupan y preparan los archivos modificados antes de ser incluidos formalmente en el historial.
*   **Commit:** Es una instantánea o "versión guardada" de los archivos en un momento dado. Cada commit posee un identificador único y un mensaje descriptivo.
*   **Branch (Rama):** Es una línea de tiempo o versión paralela del repositorio. Permite desarrollar funcionalidades de forma aislada y trabajar en diferentes tareas simultáneamente antes de fusionarlas con la línea principal.

---

## 3. Configuración Inicial y Comandos Esenciales

### Configuración Global
Antes de realizar cualquier operación, se deben establecer la identidad del usuario, ya que Git asocia cada commit a un autor de manera inmutable:

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@ejemplo.com"
```

### Tabla de Comandos Principales

| Comando | Descripción |
| :--- | :--- |
| `git init` | Inicializa un nuevo repositorio de Git en el directorio actual. |
| `git clone <url>` | Descarga y copia un repositorio remoto existente en la máquina local. |
| `git status` | Muestra el estado actual del directorio de trabajo (archivos modificados, sin rastrear o en staging). |
| `git add <archivo>` | Añade un archivo específico al *Staging Area*. (Usa `git add .` para añadir todo). |
| `git commit -m "<mensaje>"` | Consolida los cambios del *Staging Area* creando una instantánea con un mensaje descriptivo. |
| `git log` | Despliega el historial completo de commits realizados en la rama actual. |
| `git branch <nombre>` | Crea una nueva rama paralela con el nombre especificado. |
| `git checkout <nombre>` | Cambia el entorno de trabajo a la rama especificada. |
| `git merge <nombre>` | Fusiona e integra los cambios de la rama especificada dentro de la rama actual. |
| `git pull` | Trae y descarga las actualizaciones del repositorio remoto directamente a la rama local. |
| `git push` | Sube y publica los commits locales en el repositorio remoto. |

---

## 4. El Ecosistema de GitHub

### ¿Qué es GitHub y cómo funciona?
**GitHub es una plataforma de alojamiento en la nube para repositorios de Git**. Mientras Git es la herramienta de software local que gestiona las versiones, GitHub funciona como el servidor centralizado remoto que conecta a la comunidad. 

Permite almacenar proyectos de manera segura fuera de la computadora local, sirviendo como **copia de seguridad** y ofreciendo una interfaz gráfica web intuitiva con herramientas colaborativas avanzadas para proyectos públicos (código abierto) y privados.

### Flujo de Trabajo Colaborativo (Local a Remoto)
El ciclo estándar para trabajar con GitHub consiste en los siguientes pasos lógicos:

1.  **Creación de Cuenta:** Registro básico en la plataforma web de GitHub.
2.  **Creación del Repositorio Remoto:** Configuración del nuevo contenedor en GitHub, definiendo visibilidad (pública/privada) e inicializaciones como el archivo `README`.
3.  **Clonación:** Descarga del repositorio remoto a la computadora de trabajo mediante `git clone <URL>`.
4.  **Flujo Local de Trabajo:** 
    *   Modificación de archivos.
    *   Preparación de los cambios: `git add .`
    *   Confirmación de la instantánea local: `git commit -m "mensaje"`
5.  **Publicación:** Envío de las versiones locales a la nube a través de `git push origin <nombre_de_rama>` (por ejemplo, `git push origin main` para la rama principal).

---

## 5. Recursos y Documentación Oficial

Para profundizar y expandir los conocimientos sobre estas herramientas, se recomiendan los siguientes enlaces de referencia:
*   [Documentación Oficial de Git](https://git-scm.com) — Manuales y guías de comandos exhaustivas.
*   [Guía de GitHub para Principiantes](https://github.com) — Introducción oficial a la interfaz web.
*   [Tutorial Interactivo de Git](https://js.org) — Plataforma web visual para practicar el manejo de ramas y fusiones.



<hr>



# Guía de Markdown 

Este repositorio contiene la sintaxis de **Markdown** optimizada para GitHub (**GitHub Flavored Markdown - GFM**). Está diseñada para servir como plantilla y referencia técnica para la creación de documentación profesional, estructurada y visualmente atractiva en archivos `README.md`.

---

## 1. Estructura de Texto y Títulos

Los títulos se generan utilizando el carácter almohadilla (`#`). El número de almohadillas determina el nivel de jerarquía (del 1 al 6). Es fundamental incluir un espacio en blanco después de los caracteres `#`.

```markdown
# Título de Nivel 1 (Generalmente para el nombre del proyecto)
## Título de Nivel 2 (Secciones principales)
### Título de Nivel 3 (Subsecciones)
#### Título de Nivel 4
##### Título de Nivel 5
###### Título de Nivel 6
```

Para separar secciones visualmente, se pueden crear **líneas divisorias** utilizando tres o más asteriscos (`***`), guiones (`---`) o guiones bajos (`___`) en una línea aislada:

---

## 2. Énfasis y Formato de Fuente

Puedes modificar el estilo del texto para resaltar palabras clave o dar formato a las descripciones del proyecto:

*   **Negrita:** Envuelve el texto con dos asteriscos `**texto**` o dos guiones bajos `__texto__`. Ejemplo: **Este texto está en negrita**.
*   *Cursiva:* Envuelve el texto con un asterisco `*texto*` o un guión bajo `_texto_`. Ejemplo: *Este texto está en cursiva*.
*   ***Negrita y Cursiva:*** Envuelve el texto con tres asteriscos `***texto***`. Ejemplo: ***Este texto combina ambos***.
*   ~~Tachado:~~ Envuelve el texto con dos virgulillas `~~texto~~`. Ejemplo: ~~Este texto está tachado~~.

---

## 3. Listas (Ordenadas, No Ordenadas y de Tareas)

### Listas No Ordenadas (Viñetas)
Se crean utilizando asteriscos (`*`), guiones (`-`) o signos de suma (`+`) seguidos de un espacio:
*   Elemento principal A
    *   Subelemento anidado (requiere 4 espacios de sangría)
*   Elemento principal B

### Listas Ordenadas (Numeradas)
Se crean utilizando números seguidos de un punto y un espacio. El motor de Markdown indexará los números automáticamente de forma secuencial aunque uses el mismo número:
1.  Primer paso del despliegue.
2.  Segundo paso de la configuración.
3.  Tercer paso de la ejecución.

### Listas de Tareas (Checklists)
Ideales para hojas de ruta (*roadmaps*) del proyecto. Usa un guión, un espacio y corchetes `[ ]` para tareas pendientes, o `[x]` para completadas:
- [x] Diseñar la arquitectura del backend.
- [x] Configurar la base de datos local.
- - [ ] Implementar la pasarela de pagos.
- [ ] Desplegar la aplicación en producción.

---

## 4. Bloques de Código y Resaltado de Sintaxis

Para dar formato al código o comandos de consola, se utilizan los acentos graves (backticks).

### Código en Línea
Para resaltar un comando o variable dentro de un párrafo, envuélvelo en un solo acento grave. Ejemplo: Usa el comando `git status` para revisar los cambios.

### Bloques de Código Complejos
Para bloques multifila, envuelve el código entre tres acentos graves (```) al inicio y al final. Para activar el **resaltado de sintaxis coloreado**, escribe el nombre del lenguaje inmediatamente después de los primeros tres acentos:

````markdown
```python
def saludar(nombre):
    print(f"Hola, {nombre}!")
    return True
```
````

```python
def saludar(nombre):
    print(f"Hola, {nombre}!")
    return True
```

````markdown
```json
{
  "proyecto": "Guía Markdown",
  "version": "1.0.0",
  "estado": "Completado"
}
```
````

```json
{
  "proyecto": "Guía Markdown",
  "version": "1.0.0",
  "estado": "Completado"
}
```

---

## 5. Enlaces, Imágenes y Emojis

### Enlaces (Links)
La sintaxis básica vincula un texto descriptivo entre corchetes seguido de la URL entre paréntesis:
`[Texto descriptivo](URL)`
*   Ejemplo: Visita la [Documentación Oficial de GitHub](https://github.com).

### Imágenes
La sintaxis es idéntica a la de los enlaces, pero se antepone un signo de exclamación `!`. El texto entre corchetes actúa como texto alternativo (*alt text*) para accesibilidad:
`![Texto alternativo](Ruta_o_URL_de_la_imagen)`
*   Ejemplo: ![Logo de GitHub](https://githubassets.com)

### Emojis
GitHub soporta el uso directo de emojis mediante su código corto entre dos puntos, lo cual añade valor visual a los encabezados del README:
*   `:warning:` de como resultado: :warning:
*   `:rocket:` da como resultado: :rocket:
*   `:sparkles:` da como resultado: :sparkles:

---

## 6. Citas y Bloques de Texto (Blockquotes)

Para resaltar notas importantes, advertencias o citas textuales, se utiliza el carácter mayor que (`>`) al inicio de la línea:

```markdown
> **NOTA IMPORTANTE:** Antes de ejecutar el entorno de desarrollo, asegúrate de haber configurado correctamente todas las variables de entorno en tu archivo `.env`.
```

> **NOTA IMPORTANTE:** Antes de ejecutar el entorno de desarrollo, asegúrate de haber configurado correctamente todas las variables de entorno en tu archivo `.env`.

---

## 7. Tablas de Datos

Las tablas se construyen utilizando barras verticales o pipes (`|`) para delimitar las columnas y guiones (`-`) para separar la fila de encabezado del contenido. Se puede alinear el texto mediante el uso estratégico de dos puntos (`:`):

```markdown

| Parámetro | Tipo | Descripción | Alineación Izq. | Alineación Centro | Alineación Der. |
| :--- | :---: | :--- | :--- | :---: | ---: |
| `id` | Integer | Identificador único | Texto | Texto | 100 |
| `token` | String | Clave de acceso seguro | Texto | Texto | 2500 |
```

| Parámetro | Tipo | Descripción | Alineación Izq. | Alineación Centro | Alineación Der. |
| :--- | :---: | :--- | :--- | :---: | ---: |
| `id` | Integer | Identificador único | Texto | Texto | 100 |
| `token` | String | Clave de acceso seguro | Texto | Texto | 2500 |

---

## 8. Funciones Avanzadas de GitHub (GFM)

### Bloques Desplegables (Collapse/Dropdown)
Permiten ocultar secciones de información técnica muy extensas (como logs o códigos de error) mediante etiquetas HTML nativas soportadas por GitHub:

```html
<details>
<summary><b>Haz clic aquí para ver los logs detallados del sistema</b></summary>

```bash
[INFO] 12:00:00 - Inicializando servidor...
[SUCCESS] 12:00:05 - Conexión con base de datos establecida correctamente.
[WARN] 12:01:10 - Tiempo de respuesta elevado en API externa.
```

</details>
```

<details>
<summary><b>Haz clic aquí para ver los logs detallados del sistema</b></summary>

```bash
[INFO] 12:00:00 - Inicializando servidor...
[SUCCESS] 12:00:05 - Conexión con base de datos establecida correctamente.
[WARN] 12:01:10 - Tiempo de respuesta elevado en API externa.
```

</details>

### Menciones y Referencias Automáticas
*   **Menciones:** Al escribir `@usuario`, GitHub generará automáticamente un enlace al perfil del desarrollador y le enviará una notificación.
*   **Issues y Pull Requests:** Escribir el símbolo hash seguido del número de ticket (ejemplo: `#42`) crea un hipervínculo interactivo directo a esa discusión dentro del repositorio.





<hr> 



# Markdown Syntax and Equivalent HTML Syntax


Markdown es un lenguaje de marcado ligero que permite aplicar formato a un texto utilizando caracteres sencillos de texto plano, desarrollado originalmente en 2004 por John Gruber y Aaron Swartz.  

Su gran ventaja radica en la portabilidad: cualquier archivo con la extensión .md se puede abrir y editar en cualquier lector de notas básico, y plataformas como GitHub, Notion o WordPress lo interpretan de manera nativa.


Las 4 grandes ventajas de Markdown:

* Legibilidad: El texto original se lee de forma limpia y natural, sin etiquetas complejas ni códigos raros.
* Velocidad: Escribes de manera continua. 
* Independencia (Portabilidad): Un archivo Markdown es simplemente texto plano (se guarda con la extensión .md). 
* Estándar en internet: Es el idioma oficial para documentar código en GitHub GitHub, organizar notas en Notion u Obsidian, y publicar contenido en plataformas modernas.




## TEXT EMPHASIS
```
**This is bold text**  
__This is bold text__ 
<strong>This is bold text</strong> 
*This is italic text*   
_This is italic text_  
<em>This is italic text</em>  
***Bold and Italic***   
___Bold and Italic___  
<strong><em> Bold and Italic </em></strong>  
~~Scratch this~~  
<del>Scratch this</del>  
```
**This is bold text**  
__This is bold text__  
<strong>This is bold text</strong>  
*This is italic text*  
_This is italic text_  
<em>This is italic text</em>  
***Bold and Italic***   
___Bold and Italic___  
<strong><em> Bold and Italic </em></strong>  
~~Scratch this~~  
<del>Scratch this</del>  

## PARAGRAPHS
```
<p>Hello World!</p>
<p>We are learning Markdown.</p>
Some text <br>
Some more text
```

## BLOCKQUOTES
```
> This is a blockquote
<blockquote>This is a blockquote</blockquote>
> some text
>> and then some more text
>>> and then some more

<blockquote>
<p>some text</p>
<blockquote>
<p>and then some more text</p>
<blockquote>
<p>and then some more</p>
</blockquote>
</blockquote>
</blockquote>
```
> This is a blockquote
<blockquote>This is a blockquote</blockquote>

> some text
>> and then some more text
>>> and then some more

<blockquote>
<p>some text</p>
<blockquote>
<p>and then some more text</p>
<blockquote>
<p>and then some more</p>
</blockquote>
</blockquote>
</blockquote>

## HORIZONTAL LINE
````
---
___
***
<hr>
````
---
___
***
<hr>

## ORDERED LIST
```
1. Cheese
2. Carrot
3. Coconut
<ol>
 <li>Cheese</li>
 <li>Carrot</li>
 <li>Coconut</li>
</ol>
```
1. Cheese
2. Carrot
3. Coconut
<ol>
 <li>Cheese</li>
 <li>Carrot</li>
 <li>Coconut</li>
</ol>

## UNORDERED LIST
```
- Cheese
- Carrot
- Coconut

*  Red
*  Green
*  Blue

+ Red
+ Green
+ Blue

- Red
- Green
- Blue

<ul>
 <li>Cheese</li>
 <li>Carrot</li>
 <li>Coconut</li>
 </ul>
```
- Cheese
- Carrot
- Coconut

*  Red
*  Green
*  Blue

+ Red
+ Green
+ Blue

- Red
- Green
- Blue

<ul>
 <li>Cheese</li>
 <li>Carrot</li>
 <li>Coconut</li>
 </ul>

## GRAPHICS
 ```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")

![](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)
![](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png "Python Logo")
<img src="https://www.python.org/static/community_logos/python-logo-master-v3-TM.png" title="Python Logo"/>
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")

![](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)
![](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png "Python Logo")
<img src="https://www.python.org/static/community_logos/python-logo-master-v3-TM.png" title="Python Logo"/>

## LINKS
```
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

My favorite search engine is [Duck Duck Go](https://duckduckgo.com)

<p>This is <a href="http://example.com/" title="Title">
an example</a> inline link.</p>

<p><a href="http://example.net/">This link</a> has no
title attribute.</p>

https://en.wikipedia.org
<a href="https://en.wikipedia.org">https://en.wikipedia.org</a>
[click me](https://en.wikipedia.org)
<a href="https://en.wikipedia.org">click me</a>
[click me](https://en.wikipedia.org "Wikipedia")
<a href="https://en.wikipedia.org" title=”Wikipedia”>click me</a>
```
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

My favorite search engine is [Duck Duck Go](https://duckduckgo.com)

<p>This is <a href="http://example.com/" title="Title">
an example</a> inline link.</p>

<p><a href="http://example.net/">This link</a> has no
title attribute.</p>

https://en.wikipedia.org  
<a href="https://en.wikipedia.org">https://en.wikipedia.org</a>  
[click me](https://en.wikipedia.org)  
<a href="https://en.wikipedia.org">click me</a>  
[click me](https://en.wikipedia.org "Wikipedia")  
<a href="https://en.wikipedia.org" title=”Wikipedia”>click me</a>  

## TASK LISTS
```
- [x] Some task
- [ ] Some more task
```
- [x] Some task  
- [ ] Some more task  


## HTML MARK TAG
```
Do not forget to buy <mark>milk</mark> today.
```
Do not forget to buy <mark>milk</mark> today.


## HEADINGS
```
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

<h1>Header 1</h1>
<h2>Header 2</h2>
<h3>Header 3</h3>
<h4>Header 4</h4>
<h5>Header 5</h5>
<h6>Header 6</h6>
```
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

<h1>Header 1</h1>
<h2>Header 2</h2>
<h3>Header 3</h3>
<h4>Header 4</h4>
<h5>Header 5</h5>
<h6>Header 6</h6>

## TEXT COLOR
```
<span style="color:blue">Text</span>
<span style="color:red">Text</span>
<span style="color:green">Text</span>
<span style="color:pink">Text</span>
<span style="color:yellow">Text</span>
```
<span style="color:blue">Text</span>
<span style="color:red">Text</span>
<span style="color:green">Text</span>
<span style="color:pink">Text</span>
<span style="color:yellow">Text</span>

## TEXT FONT FAMILY
```
<span style="font-family:Comic Sans MS">This is a text</span>
```
<span style="font-family:Comic Sans MS">This is a text</span>

## COLORED NOTE BOXES
```
<div class="alert alert-block alert-info">
<b>Tip:</b> Use blue boxes (alert-info) for tips and notes.</div>

<div class="alert alert-block alert-warning">
<b>Example:</b> Use yellow boxes for examples that are not inside code cells, or use for mathematical formulas if needed. Typically also used to display warning messages.
</div>

<div class="alert alert-block alert-success">
<b>Success:</b> This alert box indicates a successful or positive action.
</div>

<div class="alert alert-block alert-danger">
<b>Danger:</b> This alert box indicates a dangerous or potentially negative action.
</div>
```
<div class="alert alert-block alert-info">
<b>Tip:</b> Use blue boxes (alert-info) for tips and notes.</div>

<div class="alert alert-block alert-warning">
<b>Example:</b> Use yellow boxes for examples that are not inside code cells, or use for mathematical formulas if needed. Typically also used to display warning messages.
</div>

<div class="alert alert-block alert-success">
<b>Success:</b> This alert box indicates a successful or positive action.
</div>

<div class="alert alert-block alert-danger">
<b>Danger:</b> This alert box indicates a dangerous or potentially negative action.
</div>

## CELL BACKGROUND COLOR
```
<code style="background:yellow;color:black">Useful for highlighting to grab the attention of the reader towards certain points.</code>
<p style="background:black">
<code style="background:black;color:white">C:\Users\YOUR_USERNAME> pip3 install roughviz
</code>
</p>
```
<code style="background:yellow;color:black">Useful for highlighting to grab the attention of the reader towards certain points.</code>
<p style="background:black">
<code style="background:black;color:white">C:\Users\YOUR_USERNAME> pip3 install roughviz
</code>
</p>



![Data Science con IA](https://raw.githubusercontent.com/aupatxus/ONLINE_DS_THEBRIDGE_GitHub/refs/heads/main/Vital%20LANBIDE.png)

<hr>
https://medium.com/analytics-vidhya/the-ultimate-markdown-guide-for-jupyter-notebook-d5e5abf728fd  
<hr>
https://daringfireball.net/projects/markdown/syntax  
<hr>
https://www.markdownguide.org/basic-syntax/  
