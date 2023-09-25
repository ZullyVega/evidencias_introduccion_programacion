<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->

## Actividad: Crear una tabla HTML con información sobre productos.
Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan.

### Mi Tabla HTML

```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>

    <table border="1" cellpadding="5" cellspacing="10">
        <header>
            <tr>
                <th>Código</th>
                <th>Nombre</th>
                <th colspan="1">Descripción</th>
                <th>Precio</th>
                <th>Stock</th>
                <th>Fecha de creación</th>
            </tr>
        </header>
        <tbody>
            <tr>
                <td rowspan="2">413E008</td>
                <td rowspan="2">Camisa Style</td>
                <td>Camisa cuello redondo. Manga sisa. Abertura en espalda. Detalles desagujados. Pretina con
                    diseño asimetrico. Tela fluida</td>
                <td>99.900COP</td>
                <td>10</td>
                <td>08-2023</td>
            </tr>
            <tr>
                <td>Blanca, Verde, Azul y Negra</td>
                <td>24USD</td>
            </tr>
            <tr>
                <td>519D320</td>
                <td>Camisa Animal Print</td>
                <td>Camisa clásica manga larga. Con transparencia. Silueta holgada.</td>
                <td>111.000COP</td>
                <td>15</td>
                <td>02-2023</td>
            </tr>
            <tr>
                <td rowspan="2">433E301</td>
                <td rowspan="2">Pantalón Straight fit tipo cuero</td>
                <td>Pantalon tiro alto. Tipo cuero. Straight fit. Cinco bolsillos.</td>
                <td>200.000COP</td>
                <td>8</td>
                <td>05-2023</td>
            </tr>
            <tr>
                <td>Negro</td>
                <td>48.6USD</td>
            </tr>
            <tr>
                <td rowspan="2">539D321</td>
                <td rowspan="2">Pantalón Recto</td>
                <td>Pantalón. Tiro alto. Ajuste con cierre y botón. Recto. Botones decorativos.</td>
                <td>132.000COP</td>
                <td>12</td>
                <td>03-2023</td>
            </tr>
            <tr>
                <td>Beige, Azul, Gris</td>
                <td>-</td>
            </tr>
            <tr>
                <td rowspan="2">423E009</td>
                <td rowspan="2">Chaqueta con cuello</td>
                <td>Chaqueta con cierre diagonal. Cuello de solapa con broches. Bolsillos diagonales con cierre.</td>
                <td>349.000COP</td>
                <td>5</td>
                <td>05-2023</td>
            </tr>
            <tr>
                <td>Azul, Negro</td>
                <td>85USD</td>
            </tr>
            <tr>
                <td rowspan="2">529D004</td>
                <td rowspan="2">Chaqueta con capucha</td>
                <td>Chaqueta con cuello clásico. Diseño oversized. Bolsillos funcionales de parche frontales.</td>
                <td>191.000COP</td>
                <td>3</td>
                <td>02-2023</td>
            </tr>
            <tr>
                <td>Café</td>
                <td>46USD</td>
            </tr>
            <tr>
                <td rowspan="2">572E317</td>
                <td rowspan="2">Vestido Corto</td>
                <td>Vestido con escote en V. Manga larga amplia. Puños enresortados. Tiras para anudar en cintura.</td>
                <td>219.000COP</td>
                <td>20</td>
                <td>07-2023</td>
            </tr>
            <tr>
                <td>Naranja</td>
                <td>53USD</td>
            </tr>
            <tr>
                <td rowspan="2">479D316</td>
                <td rowspan="2">Vestido Largo</td>
                <td>Cortes delanteros. Abertura en la parte trasera. Cuello de tiras cruzadas.</td>
                <td>181.000COP</td>
                <td>8</td>
                <td>04-2023</td>
            </tr>
            <tr>
                <td>Morado, Estampado</td>
                <td>44USD</td>
            </tr>
            <tr>
                <td rowspan="2">361E001</td>
                <td rowspan="2">Tenis de suela alta</td>
                <td>Ajuste con cordones. Suela alta. Aplique trasero.</td>
                <td>199.900COP</td>
                <td rowspan="2">12</td>
                <td rowspan="2">03-2023</td>
            </tr>
            <tr>
                <td>Blanco, Negro</td>
                <td>49USD</td>
            </tr>
            <tr>
                <td>332E012</td>
                <td>Cadena delgada con Dije</td>
                <td>Cadena delgada. Dije con apliques de color en el centro. Un toque sofisticado y moderno para
                    cualquier outfit.</td>
                <td>59.900COP</td>
                <td>3</td>
                <td>06-2023</td>
            </tr>
    </table>

</body>

</html>
```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>

    <table border="1" cellpadding="5" cellspacing="10">
        <header>
            <tr>
                <th>Código</th>
                <th>Nombre</th>
                <th colspan="1">Descripción</th>
                <th>Precio</th>
                <th>Stock</th>
                <th>Fecha de creación</th>
            </tr>
        </header>
        <tbody>
            <tr>
                <td rowspan="2">413E008</td>
                <td rowspan="2">Camisa Style</td>
                <td>Camisa cuello redondo. Manga sisa. Abertura en espalda. Detalles desagujados. Pretina con
                    diseño asimetrico. Tela fluida</td>
                <td>99.900COP</td>
                <td>10</td>
                <td>08-2023</td>
            </tr>
            <tr>
                <td>Blanca, Verde, Azul y Negra</td>
                <td>24USD</td>
            </tr>
            <tr>
                <td>519D320</td>
                <td>Camisa Animal Print</td>
                <td>Camisa clásica manga larga. Con transparencia. Silueta holgada.</td>
                <td>111.000COP</td>
                <td>15</td>
                <td>02-2023</td>
            </tr>
            <tr>
                <td rowspan="2">433E301</td>
                <td rowspan="2">Pantalón Straight fit tipo cuero</td>
                <td>Pantalon tiro alto. Tipo cuero. Straight fit. Cinco bolsillos.</td>
                <td>200.000COP</td>
                <td>8</td>
                <td>05-2023</td>
            </tr>
            <tr>
                <td>Negro</td>
                <td>48.6USD</td>
            </tr>
            <tr>
                <td rowspan="2">539D321</td>
                <td rowspan="2">Pantalón Recto</td>
                <td>Pantalón. Tiro alto. Ajuste con cierre y botón. Recto. Botones decorativos.</td>
                <td>132.000COP</td>
                <td>12</td>
                <td>03-2023</td>
            </tr>
            <tr>
                <td>Beige, Azul, Gris</td>
                <td>-</td>
            </tr>
            <tr>
                <td rowspan="2">423E009</td>
                <td rowspan="2">Chaqueta con cuello</td>
                <td>Chaqueta con cierre diagonal. Cuello de solapa con broches. Bolsillos diagonales con cierre.</td>
                <td>349.000COP</td>
                <td>5</td>
                <td>05-2023</td>
            </tr>
            <tr>
                <td>Azul, Negro</td>
                <td>85USD</td>
            </tr>
            <tr>
                <td rowspan="2">529D004</td>
                <td rowspan="2">Chaqueta con capucha</td>
                <td>Chaqueta con cuello clásico. Diseño oversized. Bolsillos funcionales de parche frontales.</td>
                <td>191.000COP</td>
                <td>3</td>
                <td>02-2023</td>
            </tr>
            <tr>
                <td>Café</td>
                <td>46USD</td>
            </tr>
            <tr>
                <td rowspan="2">572E317</td>
                <td rowspan="2">Vestido Corto</td>
                <td>Vestido con escote en V. Manga larga amplia. Puños enresortados. Tiras para anudar en cintura.</td>
                <td>219.000COP</td>
                <td>20</td>
                <td>07-2023</td>
            </tr>
            <tr>
                <td>Naranja</td>
                <td>53USD</td>
            </tr>
            <tr>
                <td rowspan="2">479D316</td>
                <td rowspan="2">Vestido Largo</td>
                <td>Cortes delanteros. Abertura en la parte trasera. Cuello de tiras cruzadas.</td>
                <td>181.000COP</td>
                <td>8</td>
                <td>04-2023</td>
            </tr>
            <tr>
                <td>Morado, Estampado</td>
                <td>44USD</td>
            </tr>
            <tr>
                <td rowspan="2">361E001</td>
                <td rowspan="2">Tenis de suela alta</td>
                <td>Ajuste con cordones. Suela alta. Aplique trasero.</td>
                <td>199.900COP</td>
                <td rowspan="2">12</td>
                <td rowspan="2">03-2023</td>
            </tr>
            <tr>
                <td>Blanco, Negro</td>
                <td>49USD</td>
            </tr>
            <tr>
                <td>332E012</td>
                <td>Cadena delgada con Dije</td>
                <td>Cadena delgada. Dije con apliques de color en el centro. Un toque sofisticado y moderno para
                    cualquier outfit.</td>
                <td>59.900COP</td>
                <td>3</td>
                <td>06-2023</td>
            </tr>
    </table>

</body>

</html>


