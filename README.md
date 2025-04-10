# APUNTES

## **_GITHUB_**
## 1. Git y GitHub

### 1.1 Comandos básicos

- `git init` → Inicializa (reinicia) un repositorio
- `git branch` → Crea ramas de desarrollo
- `git add` → Añade contenido al área de ensayo
- `git commit -m "mensaje"` → Guarda cambios con un mensaje
- `git push origin main` → Sube cambios al repositorio remoto
- `git remote add origin "url"` → Vincula el repo local con el remoto
- `git pull` → Trae cambios del repo remoto al local

---

## 2. Sintaxis Markdown

### 2.1 Encabezados

Markdown permite distintos niveles de encabezado usando `#`. Cuantos más `#`, más pequeño el encabezado.

```markdown
# Encabezado de primer nivel
## Encabezado de segundo nivel
### Encabezado de tercer nivel
#### Encabezado de cuarto nivel
##### Encabezado de quinto nivel
###### Encabezado de sexto nivel
```

2.2 Estilos de letra
Itálica → *texto* o _texto_

Negrita → **texto**

Tachado → ~~texto~~

Estilo anidado: **palabra1 _palabra2_** → palabra1 palabra2

2.3 Listas
2.3.1 Lista ordenada
1. Primer punto
2. Segundo punto
3. Tercer punto

2.3.2 Lista con subpuntos
1. Punto principal
   1. Subpunto con número
   * Subpunto con asterisco
   - Subpunto con guion
   + Subpunto con más

2.3.3 Lista desordenada
* Punto con asterisco
- Punto con guion
+ Punto con más

2.4 Enlaces
[Texto del enlace](URL "Título opcional")

2.5 Imágenes
Para insertar una imagen, esta debe estar subida al repositorio o disponible por URL. La sintaxis es:
![Texto alternativo](URL "Título opcional")

2.6 Tablas
| Titulo 1 | Titulo 2   | Titulo 3 |
|----------|:----------:|---------:|
| SMX2     | Curso 2324 |       25 |
| ASIX1    | Curso 2425 |       33 |
| DAW2     | Curso 2425 |       32 |


# 3. Apartado HTML

## 3.1 Definición HTML

HTML **(Hypertext Markup Language)** es el lenguaje de marcas estándar para crear páginas web. Fue creado por Tim Berners-Lee.  
Es el lenguaje más importante de Internet, ya que sin él no se podría visualizar nada en el navegador.

- **HTML:** Define la estructura y contenido de las páginas web (imágenes, listas, enlaces, etc.). Es muy adaptable, tiene una estructura lógica y es fácil de entender.  
- Los elementos HTML son bloques de construcción de las páginas web.  
- Están delimitados por etiquetas como `<body>`, `<p>`, `<img>`, etc.  
- **Hypertext:** Texto que enlaza con otros contenidos.  
- **Markup:** Las páginas están construidas en base a etiquetas.  
- **Lenguaje:** Aunque se llama lenguaje, **HTML no es un lenguaje de programación**, ya que no contiene estructuras como bucles, condiciones o funciones.

---

## 3.1.2 Etiquetas en HTML

No todas las etiquetas de HTML se **abren** y **cierran**, algunas son etiquetas vacías como:
- `<img>`
- `<br>`
- `<input>`

Estructura básica:
- Etiqueta de apertura: `<etiqueta>`
- Etiqueta de cierre: `</etiqueta>`
- Contenido: Texto o elementos dentro de la etiqueta (si aplica)

---

## 3.1.3 Atributos en HTML

Los atributos se colocan en la etiqueta de apertura y proporcionan información adicional sobre el elemento.  
Se escriben con un **nombre**, seguido de un signo igual `=`, y entre comillas el **valor**.

**Ejemplo:**

```html
<a href="URL">Texto opcional</a>

```
3.2 Estructura básica de un HTML
Una página HTML básica incluye:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>

</body>
</html>
```
Explicación:
<!DOCTYPE html>: Declara el tipo de documento.

<html lang="en">: Elemento raíz del documento, especifica el idioma.

<head>: Contiene metadatos (no visibles en la web).

<meta charset="UTF-8">: Codificación para caracteres especiales.

<title>: Título que aparece en la pestaña del navegador.

<body>: Contenido visible de la página.

Los elementos de cierre (</html>, </head>, </body>) son necesarios.

3.3 Elementos de bloque y de línea
3.3.1 Elementos de bloque:
Son estructuras grandes que contienen otros elementos o texto.

Ejemplos:
```
<h1> hasta <h6>

<p>

<br>

<hr>

<div>
```
3.3.2 Elementos de línea:
Son elementos más pequeños que aparecen en línea con el texto.

Ejemplos:
```
<strong>

<span>

<a>

<img>
```
3.4 Etiquetas básicas de HTML
Encabezados (<h1> a <h6>): Títulos o subtítulos.

Párrafos (<p>): Para texto normal.

Salto de línea (<br>): Para separar líneas.

Separador de línea (<hr>): Línea horizontal.

Énfasis (<strong>): Texto importante o destacado.

Contenedor en línea (<span>): Agrupa texto en línea sin romper el flujo.


3.4.1 Listas
Listas desordenadas (<ul>): No tienen orden específico.
```
<ul type="disc">
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```
Listas ordenadas (<ol>): Tienen un orden numérico o alfabético.
```
<ol type="1">
  <li>Primero</li>
  <li>Segundo</li>
</ol>
```

3.5 Rutas en HTML
3.5.1 Ruta absoluta
Especifica la ubicación exacta de un archivo.
```
<img src="https://ejemplo.com/imagen.png" alt="Ejemplo">
```
3.5.2 Ruta relativa
Especifica la ubicación relativa a la ubicación del archivo actual.
```
<img src="imagen/foto.jpg" alt="Foto">
```

3.6 Imágenes en HTML
Se usa la etiqueta <img>, con atributos:

src: ruta de la imagen

alt: texto alternativo

width y height: dimensiones


3.7 Enlaces en HTML
Se usa la etiqueta <a>, con el atributo href para la URL.

Ejemplo:
```
<a href="https://login.net.fje.edu/">Enlace a la net</a>
```

3.8 Validador de HTML
Puedes validar tu código HTML en:

https://validator.w3.org/

3.9 Etiquetas comunes para <body>
<p>: Párrafos

<h1>: Título principal

<h2>: Subtítulo

<br>: Salto de línea

<hr>: Línea divisora

Comentarios en HTML
```
<!-- Comentario -->
```

Etiquetas <section> y <article>
<section>: Agrupa contenido relacionado

<article>: Contenido independiente

Ejemplo:
```
<section>
  <article>
    <p>Texto del artículo</p>
  </article>
  <article>
    <img src="img/ejemplo.png" alt="Imagen ejemplo">
  </article>
</section>
```

4. Etiquetas de Tablas en HTML
Estructura general de una tabla
Etiqueta	Función	Atributos comunes
Ejemplo
```
<table>	Inicia la tabla	border, width	<table border="1" width="100%">
<thead>	Encabezado	—	—
<tbody>	Cuerpo de la tabla	—	—
<tfoot>	Pie de tabla	—	—
```
Filas y celdas
```
Etiqueta	Función	Atributos comunes	Ejemplo
<tr>	Fila	align, bgcolor, valign	<tr align="center" bgcolor="#f0f0f0">
<th>	Celda de encabezado	colspan, rowspan	<th colspan="2">Título</th>
<td>	Celda de datos	colspan, rowspan, align	<td align="right">Dato</td>
```
Resumen
Usa <thead>, <tbody>, <tfoot> para organizar el contenido.

Usa colspan y rowspan para fusionar celdas.

Las etiquetas <th> y <td> aceptan los mismos atributos.

5. Elementos de Formularios
<form>
Define un formulario interactivo.

Atributos:

action: URL donde se envían los datos.

method: Método de envío (GET o POST).

enctype: Tipo de codificación.

target: Dónde mostrar la respuesta.

<input>
Crea campos de entrada.

Atributos comunes:

type: Tipo de dato (text, radio, checkbox, etc.).

id: Identificador único.

name: Nombre del campo (clave).

value: Valor por defecto.

placeholder: Texto de guía.

required: Campo obligatorio.

disabled: Campo deshabilitado.

readonly: Solo lectura.

<textarea>
Área para introducir texto largo.

Atributos:

name, id: Identificación del campo.

rows, cols: Tamaño del área.

placeholder, required, readonly, disabled: Igual que en <input>.

<select> y <option>
Menú desplegable.
<select> define el menú, <option> las opciones.

<fieldset> y <legend>
Agrupa campos relacionados y les da un título.

<button>
Botón que puede enviar, resetear o ejecutar acciones personalizadas.

6. CSS - Hojas de Estilo en Cascada
6.1 ¿Qué es CSS?
CSS (Cascading Style Sheets) es un lenguaje que define el estilo visual de elementos HTML: colores, tamaños, márgenes, posiciones, etc.

6.2 Formas de aplicar CSS
En línea (inline)
Dentro del atributo style:
```
<h1 style="color: yellow;">Hola</h1>
```

Interno
Dentro de una etiqueta <style> en el <head>:
```
<style>
  h1 {
    color: yellow;
  }
</style>
```

Externo
En un archivo .css vinculado:
```
<link rel="stylesheet" href="styles.css">
```

6.3 Selectores CSS
```
/* Universal */
* {
  margin: 0;
  padding: 0;
}

/* Por etiqueta */
h1 {
  color: blue;
}

/* Por clase */
.miClase {
  font-size: 18px;
}

/* Por ID */
#miId {
  text-align: center;
}

/* Descendiente */
div h1 {
  color: green;
}
```

Avanzados
Por atributos:
```
img[alt] {
  border: 1px solid #000;
}

input[type="text"]     /* Igual */
input[type^="tex"]     /* Comienza con */
input[type$="text"]    /* Termina en */
input[type*="ex"]      /* Contiene */
```

Relaciones y posición:
```
/* Hijo directo */
h3 > strong {
  color: blue;
}

/* Por posición */
.parent :nth-child(4) {
  color: red;
}
```

Ejemplo:

```
<div class="parent">
  <p>1</p>
  <div>2</div>
  <span>3</span>
  <div>4</div> <!-- Este será azul -->
  <p>5</p>
</div>
```

6.4 Propiedades Comunes
Colores y fondo:
```
color: red;
background-color: yellow;
```

Texto:
```
font-size: 16px;
font-family: Arial;
text-align: center;
font-weight: bold;
```

Caja y espaciado:
```
margin: 10px;
padding: 5px;
border: 1px solid black;
```

Display y posición:
```
display: flex;
position: relative;
```

6.5 Modelo de Caja (Box Model)
Define cómo se calcula el tamaño de los elementos:

Contenido: Texto o imagen.

Padding: Espacio interno.

Border: Borde alrededor del padding.

Margin: Espacio exterior.

```
.elemento {
  margin: 10px;
  padding: 15px;
  border: 1px solid black;
}
```

6.6 Jerarquía HTML y CSS
El CSS se basa en la jerarquía HTML para aplicar estilos.
```
<div> <!-- Padre -->
  <h1>Hola</h1> <!-- Hijo -->
</div>
```
