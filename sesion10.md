<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->

## Actividad: Propiedades de posicionamiento de CSS

Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

1- Crea un nuevo archivo HTML y CSS.

2- En el archivo HTML, crea una estructura básica de página web con dos elementos div.

3- En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

```

<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <title>Ejemplo de posicionamiento de CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>

<body>
    <div class="elemento-1">Este elemento está posicionado de forma absoluta.</div>
    <div class="elemento-2">Este elemento está posicionado de forma relativa.</div>
</body>

</html>
```
```

.elemento-1 {
    position: absolute;
    top: 100px;
    left: 100px;
    background-color: blueviolet;
  }

  .elemento-2 {
    position: relative;
    top: 200px;
    left: 200px;
    background-color: green;
  }
```

## Preguntas

- ¿Cuál es la diferencia entre los valores position: absolute y position: relative?

En la position absolute, el elemento se coloca en una posición específica en la página, independientemente del flujo normal del documento. Y en la position relative, el elemento se desplaza desde su posición original en el flujo normal del documento.

- ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?

Al darle un valor numérico mayor, el elemento se superpondrá sobre los elementos con valores z-index más bajos, controlando así el orden de apilamiento.

- ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

•	Block: El elemento se muestra como una caja de bloque, que ocupa toda la anchura de su contenedor y se muestra en una nueva línea.

•	Inline: El elemento se muestra como una caja de línea, que se muestra en la misma línea que el texto circundante.

•	Inline-block: El elemento se muestra como una caja de línea, pero puede tener una anchura y una altura definidas.

•	None: El elemento no se muestra en la página web.



