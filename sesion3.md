<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


**Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5.**

**Index:**

```html
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

        .textcontainer {
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
        <div class="textcontainer">
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
**Tecnologías:**

```html

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
            font-size: 1.3rem;
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

        .pfont {
            font-size: medium;
            color: rgb(255, 255, 255);

        }

        .ml {
            font-size: xx-large;
        }
        .colortitle{
            color: white;
        }

        .regresar {
            color: #ffffff;
        }

        .textcontainer {
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: xx-large;
            font-size: 2.2rem;
        }
    </style>
</head>

<body>
    <header>
        <div class="textcontainer">
            <h1 id="comienzo">Tecnologías actuales</h1>
        </div>
        <div class="texto">
            <h5>
                Aprende sobre algunas de las tecnologías más recientes
            </h5>
        </div>
    </header>
    <br>
    <nav class="regresar">
        <a class="regresar" href="index.html">Regresar</a>
    </nav> <br />
    <section>
        <u>
            <h1 id="ai" class="ml">AI <br> <br>
        </u>
        </h1> <iframe width="560" height="315" src="https://www.youtube.com/embed/NSf3o-wxtQ0"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        <h4 class="colortitle">
            Solo audio:
        </h4>
        <audio src="ai.mp3" controls>Audio explicativo</audio>
        <p class="pfont">
            La inteligencia artificial (IA) se refiere a la simulación de procesos de inteligencia humana por parte de
            sistemas informáticos, permitiéndoles realizar tareas como el aprendizaje, la toma de decisiones y el
            reconocimiento de patrones. La IA busca crear máquinas que puedan imitar la capacidad humana de pensar,
            razonar y resolver problemas de manera autónoma.
        </p>
    </section>

    <section>
        <u>
            <h1 id="machine" class="ml">Machine Learning <br> <br>
        </u>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/mCRtyA01nuw" title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        </h1>
        <h4 class="colortitle">
            Solo audio:
        </h4>
        <audio src="⚡ Cómo funciona el Machine Learning, explicado para programadores en 3 minutos.mp3" controls>Audio
            explicativo</audio>
        <p class="pfont">
            El aprendizaje automático (machine learning en inglés) es un enfoque de la inteligencia artificial que
            implica la capacitación de sistemas informáticos para aprender de datos y mejorar su rendimiento en tareas
            específicas sin ser programados explícitamente. Utiliza algoritmos y modelos para identificar patrones en
            los datos, lo que permite que las máquinas realicen predicciones, tomen decisiones y resuelvan problemas
            basados en la información aprendida.
        </p>
    </section>
    <section>
        <u>
            <h1 id="back" class="ml">Backend <br> <br>
        </u>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/9_Fd7QLr_ig" title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        </h1>
        <h4 class="colortitle">
            Solo audio:
        </h4>
        <audio src="Qué es el Back-End (Desarrollo Web).mp3" controls>Audio explicativo</audio>
        <p class="pfont">
            El backend se refiere a la parte de un sistema informático o una aplicación que está encargada de gestionar
            y procesar la lógica, la manipulación de datos y la comunicación con bases de datos y otros servicios. Es
            responsable de la funcionalidad que no es visible directamente para el usuario, como la administración de la
            base de datos, la autenticación y la lógica de negocio.
        </p>
    </section>
    <section>
        <u>
            <h1 id="front" class="ml">Frontend <br> <br>
        </u>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/e0NwBRUbE38" title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        </h1>
        <h4>
            Solo audio:
        </h4>
        <audio src="Qué es el desarrollo Front-End - Explicación rápida.mp3" controls>Audio explicativo</audio>
        <p class="pfont">
            El frontend se refiere a la parte visible y con la que interactúa el usuario en una aplicación o sitio web.
            Incluye la interfaz gráfica, la disposición de elementos, la navegación y la experiencia visual en general.
            El frontend se encarga de presentar la información de manera atractiva y funcional, permitiendo que los
            usuarios interactúen con la aplicación de manera intuitiva.
        </p> <br />
    </section>
    <nav class="regresar">
        <a class="regresar" href="tecnologias.html#comienzo">Ir al inicio de la página</a>
    </nav> <br />


    <footer>
        Andrés Baldur Tamayo Marín
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```





