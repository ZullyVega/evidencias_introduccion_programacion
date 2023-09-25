<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->

## Actividad: Diseñar un formulario de pedido de un producto
Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1- Crear un nuevo documento HTML.

2- Crear un formulario con los siguientes campos:
- Nombre del producto
- Cantidad
- Precio unitario
- Precio total
- Dirección de envío
- Información de contacto (nombre, correo electrónico, número de teléfono)

3- Agregar los siguientes campos relacionados al formulario:
- Método de pago
- Fecha de entrega
- Comentarios

4- Utilizar las etiquetas HTML apropiados para cada campo.

### Mi Formulario

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=initial-scale=1.0">
    <title>Document</title>
    <style>
        footer {
            background-color: #f7c6f7;
            color: black;
            padding: 10px;
            text-align: center;
        }
    </style>
</head>

<body>
    <form action="">
        <h1>Formulario Pedido de Producto</h1>
        <div>
            <h3>Compra de Producto</h3>
        </div>
        <div>
            <label for="idproducto">Nombre del Producto </label>
            <input type="text" id="idproducto">
        </div>
        <br>
        <div>
            <label for="idcantidad">Cantidad </label>
            <input type="number" id="idcantidad" min="1" max="10">
        </div>
        <br>
        <div>
            <label for="idpreciou">Precio Unitario </label>
            <input type="number" id="idpreciou" placeholder="$">

        </div>
        <br>
        <div>
            <label for="idpreciot">Precio Total </label>
            <input type="number" id="idpreciot" placeholder="$">
        </div>
        <br>
        <div>
            <label for="iddireccion">Dirección </label>
            <input type="text" id="iddireccion">
        </div>
        <br>
        <div>
            <h3>Información de Contacto</h3>
        </div>
        <div>
            <label for="idnombre">Nombre Completo </label>
            <input type="text" id="idnombre">
        </div>
        <br>
        <div>
            <label for="idcorreo">Correo Electrónico </label>
            <input type="email" id="idcorreo">
        </div>
        <br>
        <div>
            <label for="idteléfono">Teléfono </label>
            <input type="tel" id="idteléfono">
        </div>
        <br>
        <div>
            <h3>Método de Pago</h3>
        </div>
        <div>
            <select name="idpago" id="idpago">
                <option value="Credito">Tarjeta Crédito</option>
                <option value="Debito">Tarejta Débito</option>
                <option value="Entrega">Contra Entrega</option>
            </select>
        </div>
        <br>
        <div>
            <label for="idfecha">Fecha de entrega </label>
            <input type="date" id="idfecha">
        </div>
        <br>
        <textarea name="comentarios" id="comentarios" placeholder="Ingrese aquí sus comentarios" rows="8"
            cols="40"></textarea>
        <br>
        <div>
            <label for="idterminos">Acepta Términos y Condiciones</label>
            <input type="checkbox" name="idterminos" value="terminos">
        </div>
        <br>
        <br>
        <div>
            <input type="submit" value="Enviar Pedido" id="enviar">
        </div>
        <br>
        <br>
        <footer>
            Zully Vega
            <br>
            CESDE
            <br>
            &copy;2023
        </footer>
    </form>
</body>

</html>

```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=initial-scale=1.0">
    <title>Document</title>
    <style>
        footer {
            background-color: #f7c6f7;
            color: black;
            padding: 10px;
            text-align: center;
        }
    </style>
</head>

<body>
    <form action="">
        <h1>Formulario Pedido de Producto</h1>
        <div>
            <h3>Compra de Producto</h3>
        </div>
        <div>
            <label for="idproducto">Nombre del Producto </label>
            <input type="text" id="idproducto">
        </div>
        <br>
        <div>
            <label for="idcantidad">Cantidad </label>
            <input type="number" id="idcantidad" min="1" max="10">
        </div>
        <br>
        <div>
            <label for="idpreciou">Precio Unitario </label>
            <input type="number" id="idpreciou" placeholder="$">

        </div>
        <br>
        <div>
            <label for="idpreciot">Precio Total </label>
            <input type="number" id="idpreciot" placeholder="$">
        </div>
        <br>
        <div>
            <label for="iddireccion">Dirección </label>
            <input type="text" id="iddireccion">
        </div>
        <br>
        <div>
            <h3>Información de Contacto</h3>
        </div>
        <div>
            <label for="idnombre">Nombre Completo </label>
            <input type="text" id="idnombre">
        </div>
        <br>
        <div>
            <label for="idcorreo">Correo Electrónico </label>
            <input type="email" id="idcorreo">
        </div>
        <br>
        <div>
            <label for="idteléfono">Teléfono </label>
            <input type="tel" id="idteléfono">
        </div>
        <br>
        <div>
            <h3>Método de Pago</h3>
        </div>
        <div>
            <select name="idpago" id="idpago">
                <option value="Credito">Tarjeta Crédito</option>
                <option value="Debito">Tarejta Débito</option>
                <option value="Entrega">Contra Entrega</option>
            </select>
        </div>
        <br>
        <div>
            <label for="idfecha">Fecha de entrega </label>
            <input type="date" id="idfecha">
        </div>
        <br>
        <textarea name="comentarios" id="comentarios" placeholder="Ingrese aquí sus comentarios" rows="8"
            cols="40"></textarea>
        <br>
        <div>
            <label for="idterminos">Acepta Términos y Condiciones</label>
            <input type="checkbox" name="idterminos" value="terminos">
        </div>
        <br>
        <br>
        <div>
            <input type="submit" value="Enviar Pedido" id="enviar">
        </div>
        <br>
        <br>
        <footer>
            Zully Vega
            <br>
            CESDE
            <br>
            &copy;2023
        </footer>
    </form>
</body>

</html>
```
