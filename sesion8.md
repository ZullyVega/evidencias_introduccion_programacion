<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->

## Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado ``` <header> ```
- Tres párrafos ``` <p> ```
- Una imagen ``` <img> ```
- Un pie de página ``` <footer> ```

Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados ``` <h1> ```
- Color azul a los párrafos ``` <p> ```
- Borde grueso negro a la imagen ``` <img> ```

Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"

Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un ``` <div> ```
- Centrar el contenido de la sección ``` <section> ```

### Link

https://zullyvega.github.io/Actividad_8/

### Mi Plantilla

```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        footer {
            background-color: #29a610;
            color: black;
            padding: 15px;
            text-align: center;
        }
    </style>
</head>

<body>
    <section>
    <header>
        <h1 class="grande" id="sombra">Navidad</h1>
    </header>
</section>
    <div>
        <h2>¿Qué es Navidad?</h2>
        <p>La Navidad es una festividad cristiana en la que se conmemora el nacimiento de Jesucristo.
            A pesar de ser una fiesta cristiana, la Navidad es celebrada actualmente en gran parte del mundo también por
            no cristianos, desprovista de su contenido religioso, como una ocasión de reencuentro y reconciliación entre
            familiares y amigos cercanos.</p>
        </div>
    <section>
        <h2 id="principal">La Navidad está asociada a varias tradiciones: </h2>
        <h3 class="destacado">Árbol de Navidad</h3>
        <p>Se convirtió así en un símbolo del nacimiento de Jesús. En los hogares católicos, el
            árbol se prepara el 8 de diciembre, día en que se celebra la fiesta de la Inmaculada Concepción de la
            Virgen.</p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Arbol.jpg?alt=media&token=434582e9-f099-4054-8f92-b55934d00b6a&_gl=1*1momdce*_ga*NTczMzc2OTc0LjE2OTY4ODA1MDY.*_ga_CW55HF8NVT*MTY5Njg4NjMzNi4yLjEuMTY5Njg4NzI4Ny42MC4wLjA."
            width="300">
        </section>
    <div>
        <h3 class="destacado">El Pesebre</h3>
        <p>También llamados belenes o nacimientos, fueron popularizados por San Francisco de
            Asís. En la víspera de la Navidad de 1223, este santo montó un pesebre con personas y animales reales en una
            cueva en las afueras de la aldea de Greccio, en Italia.</p>
        </div>
    <section>
        <h3 class="destacado">Cena de Nochebuena</h3>
        <p>Durante la víspera de Navidad es habitual en muchos sitios que las familias se reúnan para compartir una cena
            abundante. Los platos varían de un país a otro, de acuerdo con la gastronomía propia de cada lugar </p>
        </section>
    <br>
    <br>
    <footer>
        Zully Vega
        <br>
        CESDE
        <br>
        &copy;2023
    </footer>
</body>
</html>
```

```

h1 {
    color: red;
}

p {
    color: blue
}

img {
    border: 15px solid #000;
}

.destacado {
    color: rgb(4, 205, 78);
}

.grande {
    font-size: 40px;
}

#principal {
    color: yellow;
}

#sombra {
    text-shadow: 3px 3px 0px #0a7316;
}

div p {
    color: gray;
}

section {
    text-align: center;
}
```


