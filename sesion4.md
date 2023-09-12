<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


**<summary>Crear una tabla HTML con información sobre productos.</summary>**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table</title>
</head>
<style>
    .back {
        background: black;
    }

    .texto {
        font-size: xx-large;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        text-align: center;
        color: rgb(65, 65, 65);
        background: linear-gradient(to bottom left,rgb(250, 250, 250), rgb(255, 229, 195));
        padding: 40px;

    }

    .borde {
        border-color: rgb(235, 235, 235);

    }

    .encabezado {
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        font-size: xx-large;
        color: rgb(255, 229, 195);

    }

    .columna01 {
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        ;
        color: rgb(0, 0, 0);

    }

    .columna02 {
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        ;
        color: rgb(8, 8, 8);

    }

    .columna03 {
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        ;
        color: rgb(0, 0, 0);

    }

    .negrita {
        font-weight: bold;
    }

    .price {
        font-weight: bold;
        color: rgb(255, 229, 195);
    }

    .colorfont {
        color: white;
    }

    .columna04 {
        color: rgb(0, 0, 0);
    }

    .foot {
        background: linear-gradient(to bottom left, rgb(255, 229, 195), rgb(255, 255, 255));
        color: rgb(7, 7, 7);
        padding: 20px;
        text-align: center;
        font-weight: bold;
    }

</style>

<body class="back">
    <h1 class="texto">
        Consolas de videojuegos mas utilizadas
    </h1>

    <table class="borde" border="2" cellpadding="5" cellspacing="5">
        <thead>
            <tr class="encabezado">
                <th>Código</th>
                <th>Nombre</th>
                <th>Descripción</th>
                <th>Precio</th>
                <th>Stock</th>
                <th>Fecha de creación</th>
            </tr>
        </thead>
        <tbody>
            <tr class="columna01">
                <td rowspan="2" class="negrita" class="colorfont" style="background-color: rgb(214, 214, 214);">0023</td>
                <td rowspan="2" class="negrita" style="background-color: rgb(255, 229, 195)">PlayStation 5</td>
                <td class="colorfont">El playStation 5 es una consola de videojuegos desarrollada por Sony. El PS5
                    presenta un hardware
                    potente que incluye una CPU y GPU de última generación, lo que permite gráficos de alta calidad y
                    tiempos de carga más rápidos.</td>
                <td class="price" class="colorfont">$3.800.000</td>
                <td class="colorfont">15</td>
                <td class="colorfont">12-22-2020</td>

            <tr class="columna001" class="colorfont">
                <td class="colorfont">Además, el PS5 es compatible con una amplia gama de títulos de PlayStation 4 y
                    presenta una
                    creciente
                    biblioteca de juegos exclusivos y multiplataforma. También admite resolución 4K y, en
                    algunos casos, hasta 8K, lo que permite una experiencia visual impresionante.</td>
                <td class="colorfont">100</td>

            </tr>
            </tr>

            <tr class="columna02" class="colorfont">
                <td rowspan="2" class="negrita" class="colorfont" style="background-color: rgb(214, 214, 214);">0014</td>
                <td rowspan="2" class="negrita" style="background-color: rgb(255, 229, 195)">Xbox Series X</td>
                <td class="colorfont">El Xbox Series X es una consola de videojuegos de última generación desarrollada por Microsoft.
                    Se destaca por su potencia y capacidad para ofrecer una experiencia de juego inmersiva. </td>
                <td class="price" class="colorfont">$2.999.000</td>
                <td class="colorfont">22</td>
                <td class="colorfont">10-11-2020</td>

            <tr class="columna002">
                <td class="colorfont">Cuenta con un hardware avanzado que incluye una CPU AMD Ryzen multicore y una GPU
                    personalizada
                    basada
                    en la arquitectura RDNA 2, lo que permite gráficos de alta calidad y un rendimiento fluido a
                    resoluciones de hasta 4K y 120 fps en muchos juegos. </td>
                <td class="colorfont">75</td>

            </tr>
            </tr>
            <tr class="columna03">
                <td rowspan="2" class="negrita" class="colorfont" style="background-color: rgb(214, 214, 214);">0037</td>
                <td rowspan="2" class="negrita" style="background-color: rgb(255, 229, 195)">Steam Deck</td>
                <td class="colorfont">La Steam Deck es una consola portátil de videojuegos desarrollada por Valve
                    Corporation, la misma
                    empresa detrás de la plataforma de distribución de videojuegos Steam. Fue diseñada para permitir a
                    los usuarios jugar una amplia variedad de juegos de PC en un formato portátil. </td>
                <td class="price" class="colorfont">$2.100.000</td>
                <td class="colorfont">7</td>
                <td class="colorfont">25-02-2022</td>

            <tr class="columna003" class="colorfont">
                <td class="colorfont">La Steam Deck cuenta con una pantalla táctil de alta resolución, controles
                    integrados similares a
                    los de un controlador de consola tradicional, un procesador personalizado AMD, opciones de
                    almacenamiento en diferentes capacidades y la capacidad de ejecutar sistemas operativos como SteamOS
                    o Windows, lo que brinda a los jugadores la flexibilidad de acceder a su biblioteca de juegos de
                    Steam y otras plataformas.</td>
                <td class="colorfont">75</td>
            </tr>

            <tr class="columna04">
                <td rowspan="3" class="negrita" class="colorfont" style="background-color: rgb(214, 214, 214);">0123</td>
                <td rowspan="3" class="negrita" style="background-color: rgb(255, 229, 195)">Nintendo 3DS</td>
                <td class="colorfont">El Nintendo 3DS es una consola de videojuegos portátil desarrollada por Nintendo.
                    Fue lanzada en
                    2011 como sucesora de la Nintendo DS. </td>
                <td class="price" class="colorfont">$1.476.000</td>
                <td class="colorfont">9</td>
                <td class="colorfont">26-02-2011</td>

            <tr class="columna004">
                <td class="colorfont">Una característica destacada del 3DS es su capacidad para mostrar efectos 3D sin
                    necesidad de gafas
                    especiales, lo que brinda una experiencia de juego más inmersiva. Además de los juegos
                    tradicionales, el 3DS también ofrece funciones como conectividad en línea, cámara integrada,
                    controles de movimiento y compatibilidad con juegos de la Nintendo DS. </td>
                <td rowspan="2" class="colorfont">100</td>
            </tr>

            <tr class="columna0004">
                <td class="colorfont">A lo largo de su ciclo de vida, el 3DS recibió una variedad de títulos populares y
                    se convirtió en
                    una plataforma icónica en el mundo de los juegos portátiles.</td>
            </tr>
            </tr>
        </tbody>
    </table><br /><br />
    <footer class="foot">
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






