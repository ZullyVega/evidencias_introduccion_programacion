<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


<!-- Su documentación aquí -->

## Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css

Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

### Index

```

<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8">
  <title>Propiedades CSS</title>
  <link rel="stylesheet" href="style.css">

</head>

<body>

  <h1>Actividad 11</h1>
  <div>
    <img src="Imagen.jpg" alt="Caminar" width="300" border-radius: 40px>
    <p>Adentrarse en la espesura de unes regalar a nuestros sentidos una mezcla de colores, aromas y
      texturas. Dependiendo de la época del año, la vegetación de esta pieza de arte puede variar su tonalidad y
      sus formas. El olor a musgo, a la resina de la madera recién cortada, a hierba húmeda o a los aromas
      florales que emanan dél son algunas de las esencias que lo identifican. Igual que su silencio, solo
      interrumpido por el crujir de las ramas, el viento, o el sonido de las especies que lo habitan.</p>
  </div>

  <div>
    <button type="submit" value="Boton">Botón</button>
  </div>

</body>

</html>
```
### Style

```

body {
    width: 100%;
    height: 100vh;
    font-family: sans-serif;
    font-size: 15px;
}

h1 {
    width: 50%;
    height: 100px;
    margin: 10px auto;
    padding: 20px;
    font-family: serif;
    font-size: 20px;
    font-weight: bold;
    text-align: center;
}

img {
    position: static;
    top: 90px;
    left: 90px;
    z-index: 20;
    background-color: rgb(163, 144, 238);
    padding: 10px;
    border-radius: 5px;
}

p {
    float: left;
    width: 50%;
    height: 100px;
    margin: 10px;
    padding: 10px;
    text-align: justify;
    background-color: white;
}

p:hover {
    background-color: gray;
}

button {
    cursor: pointer;
    background-color: gray;
}

button:active {
    background-color: rgb(221, 104, 236);
}

p::first-letter {
    font-weight: bold;
    color: rgb(163, 144, 238);
    font-size: 30px;
}

::selection {
    background-color: rgba(143, 242, 184, 0.716);
}
```



