<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->

## Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5
Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame

Utiliza encabezados para títulos en cada elemento  ``` (<h1>...<h6>).  ```

Crea una descripción para cada elemento utilizando párrafos ``` (<p>). ```

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

- Usa < strong > para resaltar texto importante.
- Utiliza < br > para insertar saltos de línea si es necesario.
- Agrega < span > para aplicar estilos específicos a porciones de texto.
- Emplea < i > para enfatizar o dar énfasis a palabras o frases.
- Utiliza < u > para subrayar texto cuando sea necesario.
- Considera el uso de < div > para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

### Plantilla Inicial

```

<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <p>Contenido sobre imágenes...</p>
    </section>

    <section>
        <h2>Videos</h2>
        <p>Contenido sobre videos...</p>
    </section>

    <section>
        <h2>Audios</h2>
        <p>Contenido sobre audios...</p>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Contenido sobre iframes...</p>
    </section>

    <footer>
        Nombre Completo
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```

### Mi Plantilla

```

<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #a0d4f5;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: black;
        }

        footer {
            background-color: #a0d4f5;
            color: black;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Planea tus próximas vacaciones</h1>
        <h3>Porque viajar es vivir</h3>
    </header>

    <section>
        <h3>¿A donde quieres ir?</h3>
        <p>El primer paso para planificar tu viaje es elegir un destino que se ajuste a tus intereses y te permita
            disfrutar de experiencias inolvidables.</p>
        <h3>¿Qué te gustaría?</h3>
        <ul>
            <li>Verano o Invierno</li>
            <li>Playas o Desiertos</li>
            <li>Aventuras o Relajarte</li>
            <li>Gastronomía, Culturas, Festivales</li>
        </ul>

    </section>

    <section>
        <h2>Imágenes</h2>
        <h3>Playas</h3>
        <p>Por su ubicación privilegiada, su variedad en colores y texturas de la arena natural de las
            <i>playas,</i> clima
            privilegiado todo el año y por la gran oferta de turismo complementaria como experiencias únicas de
            naturaleza son algunas de las razones por lo que son cada vez más apetecidas por turistas de países con
            estaciones. <a
                href="https://colombia.travel/es/blog/disfruta-tus-vacaciones-de-verano-en-destinos-de-sol-y-playa-en-colombia"
                target="_blank">Más Información</a>
        </p>
        <img src="Imagen1.jpg" alt="Playa" width="600">

        <h3>Desiertos</h3>
        <p>Los <i>desiertos</i> son espectaculares: paisajes lunares, dunas de colores imposibles, caravanas de
            renqueantes
            camellos, espejismos de brillo metálico y la eterna promesa de un oasis. <a
                href="https://www.traveler.es/naturaleza/galerias/los-desiertos-mas-espectaculares-del-planeta/738"
                target="_blank">Más Información</a></p>
        <img src="Imagen2.jpg" alt="Desierto" width="600">

        <h3>Clima Frío</h3>
        <p>Hay algunos lugares repartidos por la tierra que están considerados como los <i>lugares más fríos del
                mundo</i> ya que tienen temperaturas extremas en invierno. ¿Te atreves a pasar frío en los países más
            fríos del mundo y
            disfrutar de algunos de los paisajes más impresionantes que habrás visto en la vida? <a
                href="https://insolitviatges.com/blog/post/los-8-pa-ses-m-s-fr-os-pero-m-s-bonitos-del-mundo"
                target="_blank">Más Información</a></p>
        <img src="Imagen3.jpg" alt="Invierno" width="600" height="800">

        <h3>Bosques</h3>
        <p>Adentrarse en la espesura de un <i>bosque</i> es regalar a nuestros sentidos una mezcla de colores, aromas y
            texturas. Dependiendo de la época del año, la vegetación de esta pieza de arte puede variar su tonalidad y
            sus formas. El olor a musgo, a la resina de la madera recién cortada, a hierba húmeda o a los aromas
            florales que emanan dél son algunas de las esencias que lo identifican. Igual que su silencio, solo
            interrumpido por el crujir de las ramas, el viento, o el sonido de las especies que lo habitan. <a
                href="https://viajes.nationalgeographic.com.es/a/bosques-mas-bellos-mundo_8559" target="_blank">Más
                Información</a></p>
        <img src="Imagen4.jpg" alt="Bosque" width="600">


    </section>

    <section>
        <h2>Videos</h2>
        <h3>Cascadas</h3>
        <p>Disfruta de una experiencia única en los <strong>Pueblos Mágicos</strong> con cascadas que ofrecen saltos de
            agua increíbles y
            paisajes indescriptibles, perfectos para tus próximas vacaciones, así como para quienes aman hacer turismo
            de aventura.</p> <a
            href="https://topadventure.com/ecoturismo/Pueblos-Magicos-con-cascadas-impresionantes-20220703-0003.html"
            target="_blank">Más
            Información</a></p>
        <video src="Video1.mp4" controls width="800"></video>

        <h3>Ciudades</h3>
        <p>Cada año, el ranking <i>“World's Best Cities”</i> nos ofrece una lista de <strong>Las Mejores Ciudades del
                Mundo</strong> para
            viajar. Este ranking tiene en cuenta diversos aspectos, como el entorno natural, la arquitectura, la
            cultura, la gastronomía y la calidad de vida.</p> <a
            href="https://elcomercio.pe/vamos/mundo/las-10-mejores-ciudades-del-mundo-para-viajar-segun-el-ranking-worlds-best-cities-lista-viajes-internacionales-noticia/"
            target="_blank">Más
            Información</a></p>
        <video src="Video2.mp4" controls width="800"></video>


    </section>

    <section>
        <h2>Audios</h2>
        <p>Para escoger un buen destino debes tomar el tiempo necesario para planificar con detalle tu viaje perfecto.
            <br>
            <br>
            <span style="color: rgb(78, 230, 192)">Relaxing Music</span>
        </p>
        <audio src="Audio1.mp3" controls></audio>
        <audio src="Audio3.mp3" controls></audio>
        <audio src="Audio2.mp3" controls></audio>
        <audio src="Audio4.mp3" controls></audio>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Si te gusta la naturaleza y buscas <u>lugares turísticos de Colombia,</u> alista tu maleta porque hemos
            recopilado
            35 lugares para visitar en Colombia y descubrir la enorme biodiversidad del país.</p>

        <iframe src="https://travelgrafia.co/blog/lugares-turisticos-de-colombia/" width="700" height="500"></iframe>


        <p>El mundo es tan grande que a la hora de <u>viajar</u> necesitamos inspiración para decidirnos por un destino
            u otro.
            Hoy en día podemos alcanzar prácticamente cualquier rincón del planeta.</p>
        <iframe src="https://viajes.nationalgeographic.com.es/a/destinos-mas-populares_11415" width="700"
            height="500"></iframe>
    </section>

    <div>Recuerda que es importante planear cada detalle de tu viaje: tiquetes, alojamientos, lugares para visitar y
        tener claro tu itinerario de viaje.
        <br>
        <br>
        <strong>¿Ya escogiste un destino?</strong>
        <br>
        <br>
        <strong>¡Disfruta tu viaje!</strong>
    </div>
    <br>
    <br>
    <footer>
        Zully Vega
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```