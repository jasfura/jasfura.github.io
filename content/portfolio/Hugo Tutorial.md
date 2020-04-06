+++
image = "img/portfolio/hugo.png"
showonlyimage = false
date = "30/03/2020"
title = "Hugo Website tutorial"
draft = false
weight = 7
+++

En este post podrán aprender cómo hacer una página web cómo la que ven aquí.

1. Primero descargar la extención Hombrew de Hugo que nos servirá para realizar nuestra página web https://formulae.brew.sh/formula/hugo.
![1](/img/hugo/1.jpg)
2. Desde el terminal de tu computador ingresar a la carpeta documentos con el comando ``cd documents´´de esta forma estaremos dentro para crear nuestra carpeta del sitio web

3. Luego debemos utilizar el comando ``hugo new site (X) `` escribiendo el nombre de nuestro sitio que queremos crear.

![2](/img/hugo/2.jpg)

4. Para descargar un template iremos a la página de hugo, https://themes.gohugo.io/ en donde descargaremos un zip con los archivos que nos servirán para nuestro sitio. Para descargar poner ´´Download Zip``
![3](/img/hugo/3.jpg)

5. Mover todas las carpetas del zip a la carpeta (X) Eliminando la extensión master. Mover también del example site el config.toml

![4](/img/hugo/4.jpg)

6. Luego desde el terminal utilizamos el comando ``hugo server´´ que nos entregará la URL interna de nuestro sitio. Es aquí en donde podemos ver una previsualización de los cambios que iremos generando.
![5](/img/hugo/5.jpg)

7. Desde el programa Visual Studio Code podremos editar los textos y las imágenes que se verán en nuestra página. Aquí debemos abrir la carpeta que hemos creado (X) y que hemos introducido el template.

8. Desde Visual si queremos ver el código más fácilmente con colores debemos descargar desde el mismo programa ´´Better toml`.
En las carpetas que muestra el programa estarán las partes a editar, cómo el título, texto e imágenes.
![6](/img/hugo/6.jpg)

9. Para ver los cambios realizados y asegurar que estén bien enlazados desde el terminal utilizamos el comando ``hugo server´´para revisar el URL.

Cuando ya logramos tener nuestra página y ya queremos ponerla en línea para que otros la puedan ver seguimos los siguientes pasos: 

10. Desde la pagina Github web crearemos un nuevo repositorio con el nombre igual al owner para luego publicar y crear el repositorio.

11. Luego descargaremos el programa Github Desktop en donde iniciaremos sesión y utilizaremos el clone or download desde la web para llevarlo a este nuevo programa. Luego apretar ´´pull origin´´. Se creará una carpeta dentro de documentos/Github en donde se encuentra nuestro repositorio.

12. Desde el terminal utilizando el comando ``cd``ingresamos a la carpeta en donde tenemos nuestros archivos y revisamos con ``hugo server``antes de publicar.
Desde visual editar en config.toml el Baseurl que debe estar así ``/``
Editaremos el nombre y los datos desde ahí.

13. Desde el terminal, pondremos el comando ``hugo´´que crea una carpeta public en finder en donde debemos copiar y pegar todos los archivos de nuestra carpeta (X) y moverlos a documents/Github en donde habrá un README.

14. Finalmente, desde Guithub Desktop poner Commit to master y poner un resumen de los cambios que se han hecho y presionar Push Origin.

15. En current repository se encontrará la URL de la página.

**Recordemos:**
- cd: ingresar a una carpeta
- ls: ver donde estamos
- Donde encontrar el template: https://themes.gohugo.io/

- Tema usado en esta página web: https://github.com/kishaningithub/hugo-creative-portfolio-theme

- Código para subir una publicación desde Instagran: 

~~~
{ {< instagram_simple B3joOJ0pwon showcaption >} }
~~~

- Código para subir un video de Youtube:
~~~
{ {< youtube número único >} }
~~~

- Código para subir un Twitter:
~~~
{ {< twitter_simple número único >} }
~~~

- Código para subir un Vimeo:
~~~
{ {< vimeo_simple número único  >} }
~~~



 
