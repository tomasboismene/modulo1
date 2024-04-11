# Módulo 1 -- Producción de textos e hipertextos

## Mock Up Languages

> **Abstract.** En este documento analizamos lo que hemos visto en clase
> de Técnicas y Herramientas Modernas en la facultad de Ingeniería
> Universidad Nacional de Cuyo, sobre diferentes herramientas como es
> conocer sobre html, saber usar Github, codear en R usando PosIT y el uso de Latex con Overleaf.
>
> **Keywords.** Tecnologías emergentes, hipertexto, html, inteligencia artificial

1. **Introducción**

El miércoles 6 de marzo de 2024, durante la clase, con los profesores exploramos los temas relacionados con el módulo 1 del curso, titulado Producción de Textos e Hipertextos. En esta sesión, discutimos varias herramientas que describiremos a continuación.

2. **El lenguaje html**

   1. **Sitio W3Schools**

Aquí aprendimos distintos tags para utilizar en la creación de la
página, con su nombre y su descripción.

<https://www.w3.org/TR/html4/index/elements.html>

![enter image description here](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTGuHDvvUcqzzk1SFHYqlDdfvsFkYDJfBavLS7wyPzLUw&s)

**Fig. 1.Captura de Pantalla de w3.org**
Arrancamos con etiquetas de html4 pero luego avanzamos con algunas de html5

2. **Nuestro primer ejemplo de una página html**

Varios miembros del grupo ya sabían codear en html, pero otros no, asi que entre todos creamos este sitio web, apoyando a los que no conocían.

Aprendimos los comandos `<head>`, `<body>`, y sus respectivos cierres
(`</head>`, `</body>`), y en una etapa posterior aprendimos h1, h2, hr,
strong. Luego vimos etiquetas tambien de Html5.

``` <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ingeniería Industrial</title>
</head>
<body>
    <header>
        <h1>Bienvenido a la página sobre Ingeniería Industrial</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#introduccion">Introducción</a></li>
            <li><a href="#campos">Campos de acción</a></li>
            <li><a href="#importancia">Importancia</a></li>
        </ul>
    </nav>
    <section id="introduccion">
        <h2>Introducción</h2>
        <p>La Ingeniería Industrial es una rama de la ingeniería que se ocupa de la optimización de procesos complejos, sistemas o organizaciones. Este campo trata de eliminar el desperdicio de tiempo, dinero, materiales, energía y otros recursos.</p>
    </section>
    <section id="campos">
        <h2>Campos de acción</h2>
        <p>Los ingenieros industriales trabajan en sectores tan diversos como manufactura, salud, consultoría, diseño, logística, y operaciones. Ayudan a las empresas a mejorar su eficiencia mediante el análisis de los flujos de trabajo y los sistemas establecidos.</p>
    </section>
    <section id="importancia">
        <h2>Importancia</h2>
        <p>La Ingeniería Industrial es crucial porque ayuda a mejorar la calidad y la eficiencia de la producción. En el contexto actual de globalización y competencia intensa, estos ingenieros aportan soluciones innovadoras para hacer más con menos.</p>
    </section>
    <footer>
        <p>© 2024 Ingeniería Industrial. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

```
## Forma de navegar Segura
También vimos en clase una forma segura de navegar por nuestros
archivos a través del comando llamado file:///c:/ soportado por algunos
navegadores como por ej: Google Chrome, Firefox y Microsoft Edge. Esta
dirección URL cuenta con la capacidad de que si la escribimos en la
barra de navegación de Internet nos proporcionará el listado de carpetas
y archivos de la unidad de memoria a la cual hace referencia (C: en
nuestro caso).

![enter image description here](https://i.stack.imgur.com/NntHe.png)
**Fig. 2. Captura de Pantalla de
[file:///c:/]{.mark}**

### Sitio de GitHub
Este sitio será el lugar donde subiremos todos nuestros trabajos. GitHub es un servicio en la nube que ofrece un sistema de control de versiones llamado Git. Este sistema documenta los cambios en archivos o conjuntos de archivos a lo largo del tiempo, lo que facilita la colaboración entre desarrolladores en proyectos compartidos y permite el seguimiento de los avances realizados.

![enter image description here](https://docs.github.com/assets/cb-137715/images/help/repository/os-repo-with-topics.png)

Así se ve un repositorio de Github. Nosotros compartimos el link de los dos repositorios del MODULO 1 Y MODULO 2 al final de este documento

### Plantillas de la cátedra en Word

Este documento de Word contiene enlaces para acceder a diversas plantillas de Word. Estas plantillas son especialmente útiles para crear encabezados como "H1", "H2", entre otros. Debido a que Docs tiende a volverse inestable con las imágenes en documentos de más de 30 páginas, optamos por usar LaTeX, que está diseñado para manejar documentos extensos de entre 1000 y 5000 páginas de manera eficiente.

## Desarrollo del sitio web final
Luego de haber aprendido Html y usando CSS gracias a nuestros compañeros de equipo que conocían al respecto, llegamos a este resultado de sitio web.
[https://tomasboismene.github.io/modulo1/](https://tomasboismene.github.io/modulo1/)
![enter image description here](https://i.ibb.co/3cr7P1C/Captura-de-pantalla-2024-04-11-a-la-s-10-01-17-a-m.png)
![enter image description here](https://i.ibb.co/WxRBGQb/Captura-de-pantalla-2024-04-11-a-la-s-10-01-28-a-m.png)
![enter image description here](https://i.ibb.co/bd2Xj5S/Captura-de-pantalla-2024-04-11-a-la-s-10-01-32-a-m.png)

# Módulo 2 -- Introducción a lenguajes de programación de alto nivel ( paradigma de objetos)

> **Abstract.** En este documento analizamos lo que hemos visto en clase
> de Técnicas y Herramientas Modernas de la facultad de Ingeniería
> Universidad Nacional de Cuyo, sobre diferentes herramientas como es
>
> **Keywords.** Programación, lenguajes, objetos, alto nivel.

1. **Introducción**

Luego con el profesor Ricardo Palma nos adentramos en los temas inherentes al
módulo 2 de la materia denominado "Introducción a lenguajes de
programación de alto nivel"

Primero aprendimos como crear una página web propia en github.

Click en el gato, luego crear repositorio nuevo con el nombre de
ENTREGAS, agregamos un archivo readme (es una opción que sale). Entramos
en ese repositorio, vamos a settings, luego a pages y bajamos a fuente y
la cambiamos a main. Posteriormente le damos a save y nos aparecerá el
link de nuestra propia pagina web.

Luego de esto, nos metemos en el repositorio y agregamos un archivo
llamado index.html y pegamos nuestra primer página de html que hicimos
en el módulo 1-Entrega 1, le damos a commit.

Luego usamos el link de nuestra página web y lo pegamos en el buscador
de google. Listo, tienes tu página

Este es el link de nuestra primer pagina:
[https://tomasboismene.github.io/modulo1/](https://tomasboismene.github.io/modulo1/)

Luego procedimos a agregar los integrantes del grupo al archivo html
para que así salieran en la pagina web.

Posteriormente aprendimos a agregar un link a nuestra pagina web con el
comando `<a href=link> Link a facultad de ingenieria </a>` es
importante que no olvidemos cerrar el comando.


[LINK GITHUB MÓDULO UNO](https://github.com/tomasboismene/modulo1)

[LINK GITHUB MÓDULO DOS](https://github.com/AIRodriguezz/modulo-2)


2. **Acerca de los lenguajes de programación**
3. **La ilusión del programador full stack** 
4. **Repaso de conceptos de programación en Ingeniería (matlab)**
5. **El entorno de programación en R**
