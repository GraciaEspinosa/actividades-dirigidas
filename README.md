# Documentación del proyecto web Actividades dirigidas

## Estructura del documento

  - Introducción y enfoque
  - Herramientas utilizadas
  - Desarrollo del proyecto:
    * Fase 1: Puesta en marcha
    * Fase 2: Desarrollo
    * Fase 3: Entrega
  - Conclusiones


## Introducción y enfoque

Se pedía construir una página web que recogiera todas las actividades de la asignatura periodismo II. 
El objeto no era sólo mostrar dichas actividades, si no la capacidad de construir un sitio web utilizando los conocimientos adquiridos en la parte transversal de la asignatura orientada a este fin.
Acojo el proyecto como una oportunidad para poner en práctica el uso de tecnologías relacionadas con la parte más digital del periodismo tan utilizadas en la actualidad.


## Herramientas utilizadas

  - Visual Studio Code (editor de texto) para escribir el código.
  - Github (controlador de versiones) alojar el repositorio con el código, también como proveedor de hosting y dominio para la web.
  - Bootstrap (framework css) para dar estilos a la página.
  - Open refine y Excel, limpieza de datos para crear gráficas
  - Datawrapper, herramienta online para dibujar gráficos a partir de datos.


## Desarrollo del proyecto

### Fase 1: Puesta en marcha
En esta primera fase hice una recopilación de todo lo necesario para empezar:
  - creación de una cuenta de github.
  - Descarga de Visual Studio Code (vs).
  - Descarga de datos para la actividad 3 del repositorio proporcionado por el profesor.
  - Recopilación de datos previamente obtenidos en la asignatura periodismo de datos I, para la actividad 4.
  - Descarga de Open Refine, limpieza de los datos recopilados en los puntos anteriores.
  - Creación de diferentes gráficas con Datawrapper.

### Fase 2: Desarrollo
  1. En vs code, creación de carpeta con la estructura de ficheros típica para un proyecto de esta naturaleza:

    (folder)Actividades Dirigidas
      (file)index.html
      (file)readme.md
      (folder)images
        (file)image.png

  2. En el fichero index.html, creación de la estructura básica de un documento HTML.

  3. Instalación de bootstrap mediante CDN, siguiendo las indicaciones de la documentación de bootstrap:
     dentro de la etiqueta `<head>` pegar el cdn de bootstrap:

     `<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>`
  
  4. Descarga de la plantilla de bootstrap propuesta para la actividad, e implementación en el proyecto.

  5. Implementación de las actividades utilizando las estructuras y etiquetas de marcado apropiadas para cada tipo de elemento: texto, imágenes, enlaces, encabezados, iframes (gráficas datawraper)...

  6. Afinación de estilos con un poco de css integrado dentro de la etiqueta `<head>` de index.html (colores, márgenes, etc.)

### Fase 3: Entrega

1. Para adjuntar el enlace de la página web fue necesario crear un repositorio.

3. Fue necesario dirigirme a `settings - page - save (root)`.

2. Una vez creado, lo único que tuve que hacer es seleccionar `upload files` y arrastrar la carpeta generada por el vs con mi código de html y css.


## Conclusiones

A pesar de que el trabajo final parecía difícil, reconozco que hacer la página web ha sido más fácil de lo que me esperaba. No obstante, modificar la plantilla inicial del Bootstrap sí que me ha llevado tiempo; puesto que el documento base estaba muy desorganizado (muchos elementos del css se encontraban incorporados en el código HTML y no en la hoja de estilos).  
