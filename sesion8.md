<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 

### Actividad: Aplicando estilos con selectores CSS

El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

* Encabezado ```<header>```
* Tres párrafos ```<p>```
* Una imagen ```<img>```
* Un pie de página ```<footer>```
* Aplica los siguientes estilos usando selectores de etiqueta:

* Color rojo a los encabezados ```<h1>```
* Color azul a los párrafos ```<p>```
* Borde grueso negro a la imagen ```<img>```

Aplica los siguientes estilos usando seleccionadores de clase:

* Color verde a los elementos con la clase ".destacado"
Tamaño de fuente grande a los elementos con la clase ".grande"
Aplica los siguientes estilos usando seleccionadores de ID:

* Color amarillo al elemento con ID "#principal"
* Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

* Color gris a los párrafos dentro de un ```<div>```
* Centrar el contenido de la sección ```<section>```

```java
<!DOCTYPE html>
<html>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<head>
    <title>Tecnologías actuales</title>
    <style>
        .texto {
            color: #b1b1b1;
            font-style: oblique;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            text-align: center;
            font-size: 1.08rem;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #2b2b2b;
        }

        header {
            background-image: url(fondotop.jpg);
            padding: 2;
            margin: 0;
            background-size: cover;
            background-position: center top;
            height: 27vh;
            background-repeat: no-repeat;
        }

        section {
            border: 1px solid #3da1a8;
            padding: 20px;
            margin-bottom: 20px;
        }

        h1 {
            color: #3da1a8;
        }

        footer {
            background-color: #0e1011;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .aline {
            vertical-align: middle;
        }

        .textsize {
            font-size: xx-large;
            color: white;
        }

        #textcontainer {
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 2.2rem;
        }

        .content {
            font-size: xx-large;
        }
    </style>
</head>

<body>
    <header>
        <div id="textcontainer">
            <h1>Tecnologías actuales</h1>
        </div>
        <div class="texto">
            <h5 class="texto">
                Aprende sobre algunas de las tecnologías más recientes
            </h5>
        </div>
    </header>
    <h1 class="content"><u>Contenido</u></h1>
    <section>
        <a href="tecnologias.html#ai"><video class="aline" src="video1.mp4" width="300" height="290" autoplay loop></video></a>
        <a class="textsize" href="tecnologias.html#ai"> AI </a><br />
    </section>
    <section>
        <a href="tecnologias.html#machine"><video class="aline" src="video2.mp4" width="300" height="290" autoplay loop></video></a>
            <a class="textsize"href="tecnologias.html#machine"> Machine Learning </a> <br />
    </section>
    <section>
        <a href="tecnologias.html#back"><video class="aline" src="video3.mp4" width="300" height="290" autoplay loop></video></a><a class="textsize"
href="tecnologias.html#back"> Backend </a><br />
    </section>
    <section>
        <a href="tecnologias.html#front"><video class="aline" src="video4.mp4" width="300" height="290" autoplay loop></video></a><a class="textsize"
            href="tecnologias.html#front"> Frontend </a> <br />
    </section>

    <footer>
        Andrés Baldur Tamayo Marín
        <br />
        <br />
        CESDE
        <br />
        <br />
        &copy;2023
    </footer>
</body>

</html>
```





