<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


*Creando mi primer sitio web.**

**Index:**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Primera web</title>
</head>

<body>
    <center>
        <header>
            <hr>
            <u>
                <p>Bienvenido a la página web de</p>
                <h1><span style="color:rgb(72, 131, 219);">Andrés Baldur </span></h1>
                <hr>
            </u>
        </header>

        <nav>
            <strong>

                <p><a href="about.html">Acerca | </a>
                    <a href="contact.html">contacto</a>
                </p>

            </strong>


        </nav>
        <main>
            <p>
                Bienvenido a mi primer sitio web. <br>Aquí encontrarás un poco de información sobre mi.
            </p>
        </main>
        <footer>
            <i>
                <P>
                    Copyright 2023 - Baldur tamayo
                </P>
                <p>
                    Andresbaldur92@gmail.com
                </p>
            </i>
        </footer>
    </center>

</body>

</html>
```

**About:**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre nosotros</title>
</head>

<body>
    <center>
        <header>
            <h1>
                <span style= "color: rgb(72, 131, 219);">Sobre nosotros</span>
            </h1>
        </header>
        <hr>
        <section>
            <h2>
                Historia
            </h2>
            
            <p>
                Andrés Baldur Tamayo Marín, de 31 años, ama la tecnología y quiere ser un gran programador. Desde joven,
                se divierte con las computadoras y le encanta resolver problemas mediante la programación. <br>
                Quiere hacer aplicaciones útiles y fáciles de usar para la gente. Está decidido a aprender y mejorar
                constantemente para lograr su objetivo. Su meta no es solo destacar en la programación, sino también
                <br>
                hacer cosas que ayuden a muchas personas.
                <hr>





            </p>

            <article>
                <h3>
                    Misión y Visión
                </h3>
                <p>
                    <strong>Misión:</strong> Crear soluciones tecnológicas innovadoras y accesibles que mejoren la vida
                    de las personas a través de la programación inteligente y la resolución de problemas. <br><br>

                    <strong>Visión:</strong> Ser reconocido como un líder en el mundo de la programación, transformando
                    ideas en aplicaciones impactantes y user-friendly que contribuyan positivamente
                    a la sociedad y faciliten la <br> interacción con la tecnología.
                </p>
                <hr>
            </article>
        </section>
        <nav>
            <a href="index.html">Inicio | </a>
            <a href="contact.html">Contacto</a>
        </nav>
    </center>

</body>

</html>
```

**Contact:**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contacto</title>
</head>

<body>
    <center>
    <header>
        <hr>
        <h1>
            <span style= "color: rgb(72, 131, 219)">Contacto</span>
        </h1>
        <hr>
    </header>
    <nav><br><br>
        <a href="index.html">Inicio | </a>
        <a href="about.html">Acerca</a> <br><br><br>
    </nav>

    <main>
        <form>
            <label for="nombre">Nombre: </label>
            <input type="text" id="nombre"><br>
            <label for="email">Email: </label>
            <input type="email" id="email"><br>                
            <label for="mensaje">mensaje:</label>
            <textarea id="mensaje"></textarea><br>                
        </form>
    </main>
    <footer>
        <p>
            <i>
            Copyright 2023 - Baldur Tamayo
        </i>
        </p>
    </footer>
</center>

</body>

</html>
```






