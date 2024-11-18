# APUNTES

## **_GITHUB_**
### Github es una página web que es capaz de almacenar toda la información que tu quieras en la nube, todo esto a través de reporitorios que vas actualizando a medida que cambias cosas en el archivo o documento que hayas subido a la nube.
### Para enlazar un repositorio con nuestro archivo tenemos que seguir unos pasos:
1. Tener el repositorio en el disco local C
2. Copiar el link del repositorio
3. Abrir el terminal desde la ubicación del archivo
4. Para clonar el repositorio en la nube debemos poner "git clone "dirección del repositorio""
5. Una vez tenemos el repositorio clonado en la nube podemos hacer nuestro primer commit, al cual se le guarda la fecha, el nombre que querramos ponerle, y lo que se ha editado, para esto abrimos el terminal y ponemos "git init"
6. Escribimos "git add ." para que se guarden los cambios
7. Para ponerle nombre al commit "git commit -m "cambios que hayas realizado en el repositorio"
8. Finalmente ponemos el comando "git push origin main" y abrimos el github para comprobar que se ha guardad correctamente


## **_MARKDOWN_**
Estos son mis apuntes del *0373* del ciclo de _ASIX_ o **DAW** del curso __2425__.

Las etiquetas en **_markdown_** y HTML pueden añidarse.

1. Primer punto de la lista
    1. Primer elemento de la sublista 1
    2. Segundo elemento de la sublista 1
2. Segundo punto de la lista
    * Primer elemento de la sublista 2
    * Segundo elemento de la sublista 2
3. Tercer punto de la lista

* Primer punto de lista desordenanda
* Segundo punto de lista desordenanda
* Tercer punto de lista desordenanda

Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500, cuando un impresor (N. del T. persona que se dedica a la imprenta) desconocido usó una galería de textos y los mezcló de tal manera que logró hacer un libro de textos especimen. No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original. Fue popularizado en los 60s con la creación de las hojas "Letraset", las cuales contenian pasajes de Lorem Ipsum, y más recientemente con software de autoedición, como por ejemplo Aldus PageMaker, el cual incluye versiones de Lorem Ipsum.

**Como mostrar codigo en un repositorio**


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

### Como hacer un enlace

[enlace](URL "Titulo opcional")

[Página web de Jesuites Bellvitge](https://www.fje.edu/ca/jesuites-bellvitge "Título opcional")

### Como poner una imagen

![Foto del GOAT](https://github.com/enricvenanci/ASIX1-AprendizajeMarkdown/blob/main/messi.jpg "Messi")

| Titulo 1 | Titulo 2 | Titulo 3 |
|:----------------------:|:----------------------------:|:----------------------------------------:|
|SMX2|curso2324|200$|
|**ASIX1**|curso2425|33|
|DAW2|curso2425|32|


## **_HTML_**

### Estructura básica de un fichero HTML
#### Esta estructura se escribe sola si en el fichero HTML ponemos "html: 5"

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

#### <meta> Añade la metainformación a la página, se pueden añadir varias de estas ya que dan información no visible del documento
#### El título de la página se pone entre <title>, y es el nombre que aparece en el buscador.
#### Para añadir un icono en la página hay que usar la etiqueta "<link rel="icon">", este icono se llama favicon y es el que aparece junto al título, este es de 16x16 píxeles.
#### <head> es donde pondremos información de la página
#### Dentro de <body> es donde ira todo el código de la página para hacer nuestra página.

#### Para crear una lista debemos usar la etiqueta <li> y si la queremos ordenada por puntos debemos poner <ul> dentro de esta, aunque si queremos que esté ordenada por números debemos usar el <ol>.
