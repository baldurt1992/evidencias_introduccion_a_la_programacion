<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


### Actividad: Propiedades de posicionamiento de CSS

**Objetivo:**

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

**Instrucciones:**

Crea un nuevo archivo HTML y CSS.
En el archivo HTML, crea una estructura básica de página web con dos elementos div.

En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style-index.css">
</head>

<body>

  <div class="div1">
    <div class="div2">
    </div>
    <div class="div3" style="background-color: rgb(158, 129, 94); ">
    </div>
    <div class="div4" style="background-color: rgb(102, 82, 52);">
    </div>
    <div class="div5" style="background-color: rgb(102, 82, 52);">
    </div>
    <div class="div6" style="background-color: rgb(167, 118, 46);">
    </div>
    <div class="div7" style="background-color: rgb(214, 139, 25);">
    </div>
    <div class="div8" style="background-color: rgb(255, 174, 54);">
    </div>
    <div class="div9" style="background-color: rgb(255, 212, 148);">
    </div>
    <div class="div10" style="background-color: rgb(255, 255, 255);">
    </div>


  </div>
  <script src="nuevo.js"></script>

</body>

</html>
```

```css
.div1{
    background-color: rgb(179, 132, 72);
    height: 400px;
    width: 800px;
    top: 200px;
    left: 200px;
    z-index: 0;
}

.div2{
    background-color: antiquewhite;
    height: 100px;
    width: 100px;
    position: relative;
    top: 20px;
    left: 20px;
}
.div3{
    height: 100px;
    width: 100px;
    position: absolute;
    top: 50px;
    left: 50px;
}
.div4{
    height: 100px;
    width: 100px;
    position: absolute;
    top: 80px;
    left: 60px;
}
.div5{
    height: 100px;
    width: 100px;
    top: 20px;
    left: 20px;
   position: relative;
   display: block;
   left: 35%;
   top: -80px;
   
}
.div6{
    height: 100px;
    width: 100px;
    top: 20px;
    left: 20px;
   position: relative;
   display: block;
   left: 35%;
   top: -80px;
   
}
.div7{
    height: 100px;
    width: 100px;
    top: 20px;
    left: 20px;
   position: relative;
   display: block;
   left: 35%;
   top: -80px;
   
}
.div8{
    height: 100px;
    width: 100px;
    top: 20px;
    left: 20px;
   position: relative;
   display: inline-block;
   left: 60%;
   top: -380px;
   
}
.div9{
    height: 100px;
    width: 100px;
    top: 20px;
    left: 20px;
   position: relative;
   display: inline-block;
   left: 60%;
   top: -380px;
   
}
.div10{
    height: 100px;
    width: 100px;
    top: 20px;
    left: 20px;
   position: relative;
   display: inline-block;
   left: 60%;
   top: -380px;
   
}
```

**Preguntas:**

* ¿Cuál es la diferencia entre los valores position: absolute y position: relative?

Diferencia entre position: absolute y position: relative:

position: absolute elimina el elemento del flujo normal y se posiciona en relación con un ancestro posicionado.
position: relative mantiene el elemento en el flujo normal y permite ajustes de posición sin afectar a otros elementos.

* ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?

Uso de z-index para controlar el orden de apilamiento:

z-index se utiliza para definir la posición vertical de elementos superpuestos.
Un valor más alto de z-index coloca un elemento encima de otros con un valor menor.

* ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

La propiedad display en CSS no solo determina dónde se va a situar un elemento, también define cómo se va a comportar a nivel de bloque o línea, e incluso si se va a ver o no. Para entender este comportamiento primero debemos saber qué es el nivel de bloque y de línea.

Cada elemento de HTML tiene un valor display CSS por defecto. Los elementos de tipo div, encabezados, formularios, secciones o párrafos son elementos que tienen por defecto el valor block. Por otro lado, los elementos como span, cursiva, negrita, enlace e imagen tienen por defecto el valor inline. Estos valores afectarán la forma en la que se comporta el elemento en relación al viewport y a la línea de texto.

Además de estos valores, la propiedad display en CSS tiene muchas opciones. A continuación te presentamos las cuatro tipos de display css u opciones más importantes de esta propiedad: block (como un bloque), inline (en línea con el texto), inline-block y none (oculto).









