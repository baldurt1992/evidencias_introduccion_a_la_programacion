<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


**<summary>Diseñar un formulario de pedido de un producto.</summary>**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<style>
    label {
        display: inline-block;
        width: 80px;
        height: 10;
    }

    select {
        display: inline-block;
        width: 200px;
        text-align: center;
        height: 30px;;
    }
    h1{
        background: black;
        color: white;
        font-size: xx-large;
        padding: 25px;
    }
    body{
        background-color: antiquewhite;
    }
</style>

<body>
    <h1>Formulario</h1>
    <form action="example.php" method="post">
        <div>
            <label for="nombre del producto">Nombre del producto:</label>
            <input type="text" name="nombre" id="nombre">
        </div><br>

        <div>
            <label for="cantidad">Cantidad</label>
            <input type="text" name="nombre" id="nombre">
        </div><br>

        <div>
            <label for="precio unitario">Precio unitario</label>
            <input type="text" name="precio unitario" id="precio unitario">
        </div><br>

        <div>
            <label for="precio total">Precio total</label>
            <input type="text" name="precio total" id="precio total">
        </div><br>

        <div>
            <label for="dirección de envío">Dirección de envío</label>
            <input type="text" name="dirección de envío" id="dirección de envío">
        </div><br>
        <h2>Información de contacto</h2><br>

        <div>
            <label for="nombre">Nombre</label>
            <input type="text" name="nombre" id="nombre">
        </div><br>

        <div>

            <label for="correo_electrónico">Correo electrónico</label>
            <input type="email" name="correo_electrónico">
        </div><br>

        <div>
            <label for="numero de contácto">Número de contácto</label>
            <input type="text" name="nomero de contácto" id="numero de contácto">
        </div><br>
        <div> <br /> <br />
            <select>
                <option value="metodos de pago">Métodos de pago</option>
                <option value="efectivo">Efectivo</option>
                <option value="tarjeta">Tarjeta</option>
                <option value="crédito">Crédito</option>
            </select>
        </div><br>
        <div>
            <label for="fecha">Fecha</label>
            <input type="date" name="fecha">
        </div><br>

        <div>
            <textarea name="comentarios" id="comentarios" placeholder="Ingrese sus comentarios aquí" rows="10"
                cols="50"></textarea>

        </div><br>


        <div>
            <input type="submit" value="Enviar">
        </div>
    </form>
</body>
</html>
```






