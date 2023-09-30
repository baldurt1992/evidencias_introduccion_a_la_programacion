<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


**Objetivo:**

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

### Solución

**Index**

```java
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style-index.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```

**CSS**

```java
.contenedor {
    width: 300px;
    height: 300px;
    background-color: grey;
    display: flex;
    justify-content: center;
    align-items: center;
}

.elemento {
    width: 200px;
    height: 200px;
    background-color: rgb(136, 61, 61);
}

.elemento {
    margin: 10px;
    width: 10px;
    height: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.elemento {
    padding: 10px;
    margin: 10px;
    width: 100px;
    height: 100px;
  }

  .elemento {
    border: 5px solid rgba(49, 47, 47, 0.305);
    padding: 20px;
    margin: 10px;
    width: 100px;
    height: 100px;
  }

  .elemento {
    border-radius: 50px;
    border: 8px solid rgb(59, 57, 57);
    padding: 30px;
    margin: 50px;
    width: 100px;
    height: 100px;
  }

  .elemento {
    border-radius: 10px;
    border: 8px solid rgb(59, 57, 57);
    margin: -0.3%;
    padding: 30%;
    width: 50px;
    height: 50px;
  }
```

* ¿Qué es la propiedad margin?
  
La propiedad margin establece los márgenes de un elemento especificando entre uno y cuatro valores, donde cada valor es una longitud, un porcentaje o auto. Los valores en porcentaje se refieren al ancho del elemento padre. Se permiten márgenes negativos. Si se dan cuatro valores, se aplican a los márgenes superior, derecho, inferior e izquierdo, respectivamente. Si se da un valor, se aplica a todos los lados. Si se dan dos o tres valores, los valores faltantes se toman del lado opuesto.
Usando la propiedad margin se pueden establecer todos los márgenes; alternativamente, pueden usarse las propiedades margin-top, margin-bottom, margin-left y margin-right.


* ¿Qué es la propiedad padding?
  
La propiedad padding es una manera rápida de aplicar las propiedades padding-top, padding-right, padding-bottom y padding-left. El padding de un elemento es la cantidad de espacio entre el borde y el contenido del elemento. Se dan entre uno y cuatro valores, donde cada valor puede ser una longitud o un porcentaje. Los valores en porcentaje se refieren al ancho del elemento padre. No se permiten los valores negativos. Si se dan cuatro valores, se aplican a los rellenos superior, derecho, inferior e izquierdo, respectivamente. Si se da un valor, se aplica a todos los lados. Si se dan dos o tres valores, los valores faltantes se toman del lado opuesto.


* ¿Qué es la propiedad border?
  
La propiedad border es una forma rápida para establecer el ancho, estilo y el color del borde izquierdo de un elemento.
La propiedad border solo puede establecer todos los cuatro bordes; puede aplicar solo un ancho y estilo de borde. Para dar diferentes valores a los cuatro bordes de un elemento, se deben usar una o más de las propiedades border-top, border-right, border-bottom, border-left, border-color, border-width, border-style, border-top-width, border-right-width, border-bottom-width, o border-left-width.


* ¿Qué es la propiedad border-radius?
  
se utiliza para establecer esquinas redondeadas en los elementos HTML. Permite suavizar las esquinas de un elemento, creando un efecto de borde redondeado en lugar de esquinas afiladas. Esta propiedad acepta uno o más valores que determinan el radio de curvatura de las esquinas.


* ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?


Las unidades de medida que se pueden utilizar para las propiedades de espaciado en CSS (como margin y padding) son las siguientes:


1. Píxeles (px): Representa un solo píxel en la pantalla. Es una unidad de medida fija.
2. Porcentajes (%): Representa un porcentaje del tamaño del elemento contenedor.
3. Em (em): Es relativo al tamaño de la fuente del elemento. Por ejemplo, si el tamaño de fuente de un elemento es de 16 píxeles, 1em sería igual a 16 píxeles.
4. Rem (rem): Es similar a em, pero en lugar de estar basado en el tamaño de fuente del elemento padre, está basado en el tamaño de fuente del elemento raíz del documento (es decir, del elemento html).
5. Puntos (pt): Representa un punto de impresión, comúnmente utilizado para medidas de impresión.
6. Picas (pc): Representa una pica, que es una unidad de medida tipográfica. Una pica es igual a 12 puntos.
7. Centímetros (cm): Representa una medida en centímetros.
8. Milímetros (mm): Representa una medida en milímetros.
9. Pulgadas (in): Representa una medida en pulgadas.
10. Unidades de Vista (vw, vh, vmin, vmax): Son unidades de medida relacionadas con el tamaño de la ventana o viewport del navegador.


Estas unidades proporcionan flexibilidad para diseñar y ajustar elementos en una página web de acuerdo con las necesidades y preferencias de diseño. Cada una tiene sus propias características y casos de uso específicos.







