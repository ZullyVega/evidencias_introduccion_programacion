<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->

## Actividad: Propiedades de espaciado y unidades de medida

Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

- Crea un nuevo archivo HTML y CSS.
- En el archivo HTML, agrega el siguiente código:

```

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```
- En el archivo CSS, agrega el siguiente código:

```

.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}
```
- Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.
- Practicar el uso de las propiedades de espaciado.

```

.elemento {
    margin: 40px;
    width: 100px;
    height: 100px;
}

.elemento {
    padding: 50px;
    margin: 40px;
    width: 100px;
    height: 100px;
}

.elemento {
    border: 10px solid rgb(232, 58, 235);
    padding: 50px;
    margin: 40px;
    width: 100px;
    height: 100px;
}

.elemento {
    border-radius: 20px;
    border: 10px solid rgb(232, 58, 235);
    padding: 50px;
    margin: 40px;
    width: 100px;
    height: 100px;
}

.elemento {
    border-radius: 20px;
    border: 10px solid rgb(232, 58, 235);
    margin: 80%;
    padding: 20%;
    width: 100px;
    height: 100px;
}
```
### Preguntas:

- ¿Qué es la propiedad margin?
La propiedad “margin” se utiliza para establecer márgenes alrededor de un elemento. 
La propiedad “margin” se puede establecer en un solo valor para establecer los márgenes en todas las direcciones, o en valores múltiples para establecer los márgenes en cada dirección individualmente.

- ¿Qué es la propiedad padding?
La propiedad “padding” es utilizada para establecer un espacio adicional alrededor del contenido de un elemento HTML. El padding se utiliza para crear distancia entre el borde del elemento y su contenido.
También es posible establecer el padding para cada lado individualmente (arriba, abajo, derecha, izquierda) utilizando las propiedades padding-top, padding-right, padding-bottom, y padding-left respectivamente.

- ¿Qué es la propiedad border?
La propiedad “border” se utiliza para establecer los bordes de un elemento HTML. Puedes especificar los valores de la propiedad “border” de varias maneras:
•	Utilizando la sintaxis abreviada: border: tamaño estilo color;
•	Utilizando las propiedades individuales: border-width, border-style y border-color.

- ¿Qué es la propiedad border-radius?
Permite especificar el redondeo de todas las esquinas de una caja CSS y definir la forma en que se debe hacer.

- ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

Unidades absolutas
•	in: pulgadas. Una pulgada equivale a 2.54 centímetros.
•	cm: centímetros.
•	mm: milímetros.
•	pt: puntos. Un punto equivale a 1 pulgada/72, es decir, unos 0.35 milímetros.
•	pc: picas. Una pica equivale a 12 puntos, es decir, unos 4.23 milímetros.

Unidades relativas
•	em: (no confundir con la etiqueta ``` <em> ``` de HTML) relativa respecto del tamaño de letra del elemento.
•	ex: relativa respecto de la altura de la letra x ("equis minúscula") del tipo y tamaño de letra del elemento.
•	px: (píxel) relativa respecto de la resolución de la pantalla del dispositivo en el que se visualiza la página HTML.

Porcentajes
El porcentaje también es una unidad de medida relativa, aunque por su importancia CSS la trata de forma separada a em, ex y px. Un porcentaje está formado por un valor numérico seguido del símbolo % y siempre está referenciado a otra medida. Cada una de las propiedades de CSS que permiten indicar como valor un porcentaje, define el valor al que hace referencia ese porcentaje.


