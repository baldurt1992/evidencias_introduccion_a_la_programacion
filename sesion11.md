<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 

### Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css

Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

* [Link página](https://baldurt1992.github.io/eucalyptoAccesorios/)

#### Index

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style-index.css">
    <title>Document</title>
</head>

<body>
    <div class="position">
        <a href="index.html"><img class="logon"
                src="https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/LETRAS.png?alt=media&token=158988c6-dea3-4243-a523-b61916f491b3&_gl=1*15xzfnu*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTk0MjAxMC4xMS4xLjE2OTU5NDQ1NTIuNDIuMC4w"
                alt="logo"></a>
    </div><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

    <h1 class="font">

        <div class="back">
            <a href="tienda.html" class="menu-item">
                <div class="menu-item-image tienda"></div>
                <h4>Tienda</h4>
            </a>
            <a href="contacto.html" class="menu-item">
                <div class="menu-item-image contacto"></div>
                <h4>Contacto</h4>
            </a>
            <a href="sobrenosotros.html" class="menu-item">
                <div class="menu-item-image nosotros"></div>
                <h4>Sobre nosotros</h4>
            </a>
        </div> <br><br><br><br>

        <footer>
            Eucalypto Colombia
            <br />
            <br />
            Medellín-Antioquia
            <br />
            <br />
            &copy;2023
        </footer>



</body>

</html>
```
### Contacto

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto</title>
    <link rel="stylesheet" href="style-index.css">
</head>

<body>
    <div class="position">
        <a href="index.html"><img class="logon"
                src="https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/LETRAS-EU.png?alt=media&token=987379d1-7ab6-4185-982e-fe51cc761376&_gl=1*5q82ki*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTkxOTQzNy42LjEuMTY5NTkxOTQ3OS4xOC4wLjA."
                alt="logo"></a>
    </div>

    <h1 class="font">
        <div class="back">
            <u><a href="tienda.html">
                    <h4>Tienda</h4>
                </a></u> <br />
            <u><a href="contacto.html">
                    <h4>Contacto</h4>
                </a></u> <br />
            <u><a href="sobrenosotros.html">
                    <h4>Sobre nosotros</h4></u></a>
        </div>

        <main>
            <form class="aline">
                <label for="nombre">Nombre: </label>
                <input type="text" id="nombre"><br>
                <label for="email">Email: </label>
                <input type="email" id="email"><br>
                <label for="mensaje">Mensaje:</label>
                <textarea class="fijar" id="mensaje" rows="4" cols="50"></textarea>
            </form>
        </main>
        <br><br><br>
        <footer>
            Eucalypto Colombia
            <br />
            <br />
            Medellín-Antioquia
            <br />
            <br />
            &copy;2023
        </footer>
</body>

</html>
```

### Tienda

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style-index.css">
    <title>Document</title>
</head>

<body>
    <div class="position">
        <a href="index.html"><img class="logon"
                src="https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/LETRAS-EU.png?alt=media&token=987379d1-7ab6-4185-982e-fe51cc761376&_gl=1*5q82ki*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTkxOTQzNy42LjEuMTY5NTkxOTQ3OS4xOC4wLjA."
                alt="logo"></a>
    </div>

    <h1 class="font">

        <div class="back">
            <u><a href="tienda.html">
                    <h4>Tienda</h4>
                </a></u> <br />
            <u><a href="contacto.html">
                    <h4>Contacto</h4>
                </a></u> <br />
            <u><a href="sobrenosotros.html">
                    <h4>Sobre nosotros</h4></u></a>
        </div>

        <div class="gallery">
            <div class="row">
                <div class="column">
                    <img class="tamaño img-zoom"
                        src="https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/Eucalypto%20info%2FIMG_20230522_151124.jpg?alt=media&token=53f665b8-32b5-45cf-8ca8-9ae4f82ce604&_gl=1*1uuecyw*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTkzNTY0Mi4xMC4wLjE2OTU5MzU2NDIuNjAuMC4w"
                        alt="aretas 1">
                    <p>Aretas 1</p>
                </div>
                <div class="column">
                    <img class="tamaño img-zoom"
                        src="https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/Eucalypto%20info%2FIMG_20230522_151908.jpg?alt=media&token=43305f1d-52d4-4228-8e3c-917bf756e891&_gl=1*8sdx9n*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTkzNTY0Mi4xMC4xLjE2OTU5MzU2NTkuNDMuMC4w"
                        alt="aretas 2">
                    <p>Aretas 2</p>
                </div>
                <div class="column">
                    <img class="tamaño img-zoom"
                        src="https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/Eucalypto%20info%2FIMG_20230522_152204.jpg?alt=media&token=50585ae5-db5c-4fe5-9d77-b566b413af94&_gl=1*37rfc*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTkzNTY0Mi4xMC4xLjE2OTU5MzU2NzEuMzEuMC4w"
                        alt="aretas 3">
                    <p>Aretas 3</p>
                </div>
                <div class="column">
                    <img class="tamaño img-zoom"
                        src="https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/Eucalypto%20info%2FIMG_20230522_153335.jpg?alt=media&token=ee36fc88-dbb8-4216-96c4-da4a26428dbf&_gl=1*174awja*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTkzNTY0Mi4xMC4xLjE2OTU5MzU4NjguNjAuMC4w"
                        alt="aretas 3">
                    <p>Aretas 4</p>
                </div>
            </div>
        </div>

        <div class="gallery">
            <div class="row">
                <div class="column">
                    <img class="tamaño img-zoom"
                        src="https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/Eucalypto%20info%2FIMG_20230522_152512.jpg?alt=media&token=e83cfe04-a9b2-4f27-ab6b-248ca941ec47&_gl=1*1arld9x*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTkzNTY0Mi4xMC4xLjE2OTU5MzU3ODQuNjAuMC4w"
                        alt="aretas 1">
                    <p>Aretas 5</p>
                </div>
                <div class="column">
                    <img class="tamaño img-zoom"
                        src="https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/Eucalypto%20info%2FIMG_20230522_152659.jpg?alt=media&token=15f1b667-e2fd-444d-8f6d-65f59494fb9d&_gl=1*z2w1dv*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTkzNTY0Mi4xMC4xLjE2OTU5MzU3OTkuNDUuMC4w"
                        alt="aretas 2">
                    <p>Aretas 6</p>
                </div>
                <div class="column">
                    <img class="tamaño img-zoom"
                        src="https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/Eucalypto%20info%2FIMG_20230522_152859.jpg?alt=media&token=185dab12-5eaf-4e3d-a745-42ccd04b6ddd&_gl=1*1elqzsg*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTkzNTY0Mi4xMC4xLjE2OTU5MzU4MTUuMjkuMC4w"
                        alt="aretas 3">
                    <p>Aretas 7</p>
                </div>
                <div class="column">
                    <img class="tamaño img-zoom"
                        src="https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/Eucalypto%20info%2FIMG_20230522_161037.jpg?alt=media&token=bc2d314a-70b4-464d-8316-875204029e8c&_gl=1*910ppe*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTkzNTY0Mi4xMC4xLjE2OTU5MzU4ODUuNDMuMC4w"
                        alt="aretas 3">
                    <p>Anillos 1</p>
                </div>
            </div>
        </div> <br><br><br>

        <footer>
            Eucalypto Colombia
            <br />
            <br />
            Medellín-Antioquia
            <br />
            <br />
            &copy;2023
        </footer><br>



</body>

</html>
```

### Estilos

```css
.position {
    text-align: center;
    margin: -140px;
}

.logon {
    width: 450px;
    height: 450px;
    padding: 0px;
    position: relative;
}

h1.font {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    color: rgb(43, 91, 71);
    text-align: center;
    margin: -200px;
    position: relative;
}

.back {
    display: flex;
    justify-content: center;
    text-align: center;
    flex-wrap: wrap;
}

.back a {
    text-decoration: none;
}


.back h4 {
    padding: 15px;
    font-size: 17px;
    color: rgb(43, 91, 71);
    margin: 20px;
    line-height: 45px;
    transition: background-color 0.3s ease;
}

.back h4:hover {
    background-color: rgba(43, 91, 71, 0.137);
    cursor: pointer;
}

.tamaño {
    width: 200px;
    height: 200px;
}

.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 60px;
    margin: 3px;
}

.row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.column {
    text-align: center;
    margin-right: 130px;
    font-weight: lighter;
}

.gallery p {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 22px;
}

.img-zoom {
    transition: transform 0.3s ease;
}

.img-zoom:hover {
    transform: scale(1.2);
}

footer {
    text-align: center;
    font-size: 15px;
    font-weight: lighter;
}

body {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.aline {
    text-align: center;
}

.aline {
    margin: 0 auto;
    text-align: center;
    max-width: 400px;
    font-size: 25px;
}


.aline label,
.aline input,
.aline textarea {
    display: block;
    margin: 10px 0;
    width: 100%;
}

.fijar {
    width: 500px;
    height: 200px;
    resize: none;
}

.infocenter {
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 30vh;
    font-size: 20px;
    margin-inline: 400px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-weight: lighter;
    text-align: justify;
}

.menu-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    text-decoration: none;
    color: #333;
    font-size: 18px;
    margin: 10px;
    position: relative; 
}

.menu-item-image {
    width: 350px;
    height: 350px;
    background-size: cover;
}

.menu-item h4 {
    position: absolute; 
    bottom: 70px; 
    left: 0; 
    right: 0; 
    text-align: center;
    background-color: rgba(255, 255, 255, 0.8); 
    padding: 20px 30px; 
    font-weight: bold;
    border-radius: 5px; 
}

.tienda {
    background-image: url('https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/Eucalypto%20info%2FIMG_20230522_151124.jpg?alt=media&token=53f665b8-32b5-45cf-8ca8-9ae4f82ce604&_gl=1*18n707o*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTk0MjAxMC4xMS4wLjE2OTU5NDIwMTAuNjAuMC4w');
}

.contacto {
    background-image: url('https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/Eucalypto%20info%2FIMG_20230522_151908.jpg?alt=media&token=43305f1d-52d4-4228-8e3c-917bf756e891&_gl=1*4r48i7*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTk0MjAxMC4xMS4xLjE2OTU5NDIwMjUuNDUuMC4w');
}

.nosotros {
    background-image: url('https://firebasestorage.googleapis.com/v0/b/fotogit-b823c.appspot.com/o/Eucalypto%20info%2FIMG_20230522_152204.jpg?alt=media&token=50585ae5-db5c-4fe5-9d77-b566b413af94&_gl=1*d55ymc*_ga*MTY3NDMzNDI5NC4xNjk0NTQ2MzEz*_ga_CW55HF8NVT*MTY5NTk0MjAxMC4xMS4xLjE2OTU5NDIwMzMuMzcuMC4w');
}
```







