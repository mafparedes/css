# 🧱 Aprendiendo HTML – Estructura de texto

Este README contiene la teoría completa de la **estructura de un documento y las etiquetas semánticas en HTML**, con ejemplos prácticos y un **ejemplo integrador** basado en una receta real que usa todas las etiquetas aprendidas.

El objetivo es describir qué hace nuestro proyecto, cómo funciona y qué tecnologías utiliza. Además, aplicamos **Markdown (.md)**, una versión mejorada de texto que organiza y da formato al contenido de manera más sencilla y legible para plataformas como GitHub.

> [!NOTE]
> Todo el código HTML de los ejemplos está dentro de bloques de código para que puedas copiarlo y probarlo directamente en tu propio editor de texto.

---

## 📝 Conceptos Básicos y Estructura en HTML

### 🔹 ¿Qué es HTML?

HTML es un lenguaje de marcado de texto. Es la parte que nos permite estructurar nuestra página web, funcionando como el esqueleto de una aplicación. Su principal objetivo es darle formato semántico a la información mediante el uso de elementos HTML.

Un elemento HTML estándar está conformado por:

* Etiqueta de apertura
* Contenido
* Etiqueta de cierre

**Ejemplo visual:**

```html
<div>Hola Mundo</div>

```

| Parte | Descripción |
| --- | --- |
| `<div>` | Etiqueta de apertura |
| `Hola Mundo` | Contenido o texto del elemento |
| `</div>` | Etiqueta de cierre |

> [!TIP]
> **Elementos huérfanos:** En algunos casos encontraremos elementos vacíos o huérfanos. Estos solo están conformados por una sola etiqueta (no tienen cierre ni contenido de texto) y normalmente contienen atributos útiles.
> **Ejemplos:**
> ```html
> <img src="imagen.jpg" alt="imagen">
> <br>
> <hr>
> 
> ```
> 
> 

---

### 🔹 Estructura Fundamental del Documento HTML

Todo archivo HTML requiere una estructura jerárquica mínima obligatoria para que el navegador lo interprete de forma correcta:

#### `<!DOCTYPE html>`

Declaramos el tipo de documento. Este elemento huérfano indica al navegador que el documento que se está trabajando debe renderizarse bajo el estándar moderno de **HTML5**.

> [!WARNING]
> **Regla de oro:** Siempre debe estar ubicado en la primera línea del archivo. Si pones cualquier otra etiqueta antes de esta directiva, puedes romper el modo de visualización correcto en navegadores antiguos.

#### `<html></html>`

Es el elemento raíz. Envuelve todo el contenido de la página HTML y contiene los elementos principales.

> [!TIP]
> Por buenas prácticas de accesibilidad y SEO, se acostumbra definir siempre el idioma principal de tu sitio web usando el atributo `lang`:
> ```html
> <html lang="es">
> 
> ```
> 
> 

#### `<head></head>`

Elemento de configuración. Contiene información importante y metadatos del documento que no se ven directamente en la pantalla:

* Título de la pestaña
* Enlaces a archivos CSS externos
* Codificación de caracteres (Metadatos)
* Información para motores de búsqueda (SEO)

```html
<head>
    <meta charset="UTF-8">
    <title>Mi Página</title>
</head>

```

#### `<title></title>`

Elemento de título de página. Es hijo directo de `<head>` y define el nombre oficial que aparecerá en la pestaña del navegador.

```html
<title>Mi Página Web</title>

```

#### `<body></body>`

Contiene todo el contenido visible de la página web (textos, estructuras, imágenes, listas y formularios).

```html
<body>
    <h1>Hola Mundo</h1>
</body>

```

---

## 📝 Estructura de Texto y Etiquetas Comunes

A continuación se detallan las etiquetas semánticas de uso diario para estructurar textos dentro del `<body>`:

### 🔹 Jerarquía de encabezados

Los encabezados van del `<h1>` (el más importante) al `<h6>` (el menos importante) para definir la importancia y el orden de los títulos.

> [!IMPORTANT]
> **Control semántico:** Solo debe haber un único `<h1>` por cada página web. Usar más de uno confunde a los lectores de pantalla y perjudica gravemente el posicionamiento en Google (SEO).

```html
<h1>Receta de Quinua con Pollo y Verduras</h1>
<h2>Ingredientes</h2>
<h3>Consejo del Chef</h3>

```

### 🔹 Párrafos y énfasis

* `<p>`: define un párrafo de texto estándar.
* `<strong>`: aplica negrita para dar un énfasis fuerte o resaltar algo crucial.
* `<em>`: aplica cursiva para dar un énfasis suave o tono conversacional.

```html
<p>Esta receta es <strong>muy saludable</strong> y <em>perfecta</em> para un almuerzo completo.</p>

```

### 🔹 Listas

* `<ul>` + `<li>`: lista desordenada (genera viñetas/puntos independientes).
* `<ol>` + `<li>`: lista ordenada (genera números correlativos automáticos).

```html
<ul>
    <li>1 taza de quinua</li>
</ul>
<ol>
    <li>Lavar bien la quinua.</li>
</ol>

```

### 🔹 Citas y referencias

* `<blockquote>`: bloque de cita larga extraída de otra fuente (aplica sangría automática).
* `<cite>`: indica la fuente, obra o el autor original de la cita.

```html
<blockquote>
    <p>Para un sabor extra, puedes añadir un poco de cúrcuma al cocinar la quinua.</p>
    <cite>— Chef Gastón Acurio</cite>
</blockquote>

```

### 🔹 Código y texto técnico

* `<code>`: muestra fragmentos de código o términos técnicos con tipografía monoespaciada.
* `<pre>`: texto preformateado que respeta fielmente los espacios y saltos de línea tal cual se escriben en el editor.

```html
<p>Puedes añadir un poco de <code>cúrcuma</code>.</p>
<pre>
  Nota importante:
  Asegúrate de que el pollo esté bien cocido.
</pre>
```

### 🔹 Líneas y saltos

* `<hr>`: línea horizontal que actúa como un separador temático entre secciones.
* `<br>`: salto de línea inmediato dentro de un mismo bloque de texto sin abrir un párrafo nuevo.

```html
<p>Línea de texto 1<br>Línea de texto 2</p>
<hr>
```

### 🔹 CSS (cascading style sheet)

cascada de hojas de estilo, es el documento que nos permite darle estilo a nuestros elementos, posicionar, formato, escalar, color y transcisiones.

## como aplicar css a nuestro documento html

### 1. en linea

este manera de aplicar css es haciendo uso de los atributos de un elemento en este caso es especial usando el atributo `style`

```html

<p style="color:blue;size:23px">este es el texto </p>
```

> [!TIP] En el caso de los embebidos y los de archivos externo hay que entender sobre selectores: son manera de como yo identifico un elemento dentro de un documento html, selector por etiqueta, id y clase, en el diseño web se recomienda solo usar los selectores de tipo clase.

### 2. embebidos

este tipo de aplicar estilo nos permite hacer uso de la etiqueta style para poder estilar nuestros elemento, por convencio esta etiqueta al ser de configuracion se debe usar en `head`

### 3. archivo externo
Es la manera correcta y mas usada para aplicar estilo dentro de un documento `html`. para asociar un archivo externo lo tenemos que hacer 
en nuestro etiqueta de configuracion `head`, haciendo uso de la etiqueta `link` a travez de su atributo `href` en ete atributo le indicamos la ruta del 
archivo que se debe asociar.

> [!TIP]
> **Observación:** Una ruta absoluta es la dirección completa del archivo. Ejemplo: `C:\Users\USER\OneDrive\Desktop - copia\alvbarez\primera_clase`. Una ruta relativa es la dirección actual del proyecto. Ejemplo: `./`
> **Ejemplo:**
> Tenemos en nuestra carpeta del proyecto un archivo llamado `logo.png`. Para acceder al archivo usamos:
> **Ruta absoluta:**
> ```text
> C:\Users\ASUS\Documents\APSTI V\css - copia\alvbarez\primera_clase\logo.png
> ```
> **Ruta relativa:**
> ```text
> ./logo.png
> ```
