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

- Usa ``` <strong> ``` para resaltar texto importante.
- Utiliza ``` <br> ``` para insertar saltos de línea si es necesario.
- Agrega ``` <span> ``` para aplicar estilos específicos a porciones de texto.
- Emplea ``` <i> ``` para enfatizar o dar énfasis a palabras o frases.
- Utiliza ``` <u> ``` para subrayar texto cuando sea necesario.
- Considera el uso de ``` <div> ``` para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

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
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Imagen1.jpg?alt=media&token=833ae1d4-07d1-46cd-bb02-c49252b54216" alt="Playa" width="600">

        <h3>Desiertos</h3>
        <p>Los <i>desiertos</i> son espectaculares: paisajes lunares, dunas de colores imposibles, caravanas de
            renqueantes
            camellos, espejismos de brillo metálico y la eterna promesa de un oasis. <a
                href="https://www.traveler.es/naturaleza/galerias/los-desiertos-mas-espectaculares-del-planeta/738"
                target="_blank">Más Información</a></p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Imagen1.jpg?alt=media&token=833ae1d4-07d1-46cd-bb02-c49252b54216" alt="Desierto" width="600">

        <h3>Clima Frío</h3>
        <p>Hay algunos lugares repartidos por la tierra que están considerados como los <i>lugares más fríos del
                mundo</i> ya que tienen temperaturas extremas en invierno. ¿Te atreves a pasar frío en los países más
            fríos del mundo y
            disfrutar de algunos de los paisajes más impresionantes que habrás visto en la vida? <a
                href="https://insolitviatges.com/blog/post/los-8-pa-ses-m-s-fr-os-pero-m-s-bonitos-del-mundo"
                target="_blank">Más Información</a></p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Imagen3.jpg?alt=media&token=a394b6cf-b146-43a3-9704-c34d33f486af" alt="Invierno" width="600" height="800">

        <h3>Bosques</h3>
        <p>Adentrarse en la espesura de un <i>bosque</i> es regalar a nuestros sentidos una mezcla de colores, aromas y
            texturas. Dependiendo de la época del año, la vegetación de esta pieza de arte puede variar su tonalidad y
            sus formas. El olor a musgo, a la resina de la madera recién cortada, a hierba húmeda o a los aromas
            florales que emanan dél son algunas de las esencias que lo identifican. Igual que su silencio, solo
            interrumpido por el crujir de las ramas, el viento, o el sonido de las especies que lo habitan. <a
                href="https://viajes.nationalgeographic.com.es/a/bosques-mas-bellos-mundo_8559" target="_blank">Más
                Información</a></p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Imagen4.jpg?alt=media&token=77cf6db0-7121-40f3-a55f-8516d362bbd6" alt="Bosque" width="600">


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
        <video src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Video1.mp4?alt=media&token=35f53a0a-809a-4fa5-95fa-1ac2e508192d" controls width="800"></video>

        <h3>Ciudades</h3>
        <p>Cada año, el ranking <i>“World's Best Cities”</i> nos ofrece una lista de <strong>Las Mejores Ciudades del
                Mundo</strong> para
            viajar. Este ranking tiene en cuenta diversos aspectos, como el entorno natural, la arquitectura, la
            cultura, la gastronomía y la calidad de vida.</p> <a
            href="https://elcomercio.pe/vamos/mundo/las-10-mejores-ciudades-del-mundo-para-viajar-segun-el-ranking-worlds-best-cities-lista-viajes-internacionales-noticia/"
            target="_blank">Más
            Información</a></p>
        <video src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Video2.mp4?alt=media&token=4902e262-f401-42d8-a60f-d2bbb08436ea" controls width="800"></video>


    </section>

    <section>
        <h2>Audios</h2>
        <p>Para escoger un buen destino debes tomar el tiempo necesario para planificar con detalle tu viaje perfecto.
            <br>
            <br>
            <span style="color: rgb(78, 230, 192)">Relaxing Music</span>
        </p>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Audio1.mp3?alt=media&token=5a236dc1-1d87-4169-b6ac-2c30833761cd" controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Audio3.mp3?alt=media&token=6a0d0e10-8c88-4e4b-afd4-b47cf9d6043d" controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Audio2.mp3?alt=media&token=f73fad29-e833-4373-ab08-98fe353f4eb5" controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Audio4.mp3?alt=media&token=ece0c1d4-87cc-4847-9497-c7f5f0b20580" controls></audio>

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
<br>

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
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Imagen1.jpg?alt=media&token=833ae1d4-07d1-46cd-bb02-c49252b54216" alt="Playa" width="600">

        <h3>Desiertos</h3>
        <p>Los <i>desiertos</i> son espectaculares: paisajes lunares, dunas de colores imposibles, caravanas de
            renqueantes
            camellos, espejismos de brillo metálico y la eterna promesa de un oasis. <a
                href="https://www.traveler.es/naturaleza/galerias/los-desiertos-mas-espectaculares-del-planeta/738"
                target="_blank">Más Información</a></p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Imagen1.jpg?alt=media&token=833ae1d4-07d1-46cd-bb02-c49252b54216" alt="Desierto" width="600">

        <h3>Clima Frío</h3>
        <p>Hay algunos lugares repartidos por la tierra que están considerados como los <i>lugares más fríos del
                mundo</i> ya que tienen temperaturas extremas en invierno. ¿Te atreves a pasar frío en los países más
            fríos del mundo y
            disfrutar de algunos de los paisajes más impresionantes que habrás visto en la vida? <a
                href="https://insolitviatges.com/blog/post/los-8-pa-ses-m-s-fr-os-pero-m-s-bonitos-del-mundo"
                target="_blank">Más Información</a></p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Imagen3.jpg?alt=media&token=a394b6cf-b146-43a3-9704-c34d33f486af" alt="Invierno" width="600" height="800">

        <h3>Bosques</h3>
        <p>Adentrarse en la espesura de un <i>bosque</i> es regalar a nuestros sentidos una mezcla de colores, aromas y
            texturas. Dependiendo de la época del año, la vegetación de esta pieza de arte puede variar su tonalidad y
            sus formas. El olor a musgo, a la resina de la madera recién cortada, a hierba húmeda o a los aromas
            florales que emanan dél son algunas de las esencias que lo identifican. Igual que su silencio, solo
            interrumpido por el crujir de las ramas, el viento, o el sonido de las especies que lo habitan. <a
                href="https://viajes.nationalgeographic.com.es/a/bosques-mas-bellos-mundo_8559" target="_blank">Más
                Información</a></p>
        <img src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Imagen4.jpg?alt=media&token=77cf6db0-7121-40f3-a55f-8516d362bbd6" alt="Bosque" width="600">


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
        <video src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Video1.mp4?alt=media&token=35f53a0a-809a-4fa5-95fa-1ac2e508192d" controls width="800"></video>

        <h3>Ciudades</h3>
        <p>Cada año, el ranking <i>“World's Best Cities”</i> nos ofrece una lista de <strong>Las Mejores Ciudades del
                Mundo</strong> para
            viajar. Este ranking tiene en cuenta diversos aspectos, como el entorno natural, la arquitectura, la
            cultura, la gastronomía y la calidad de vida.</p> <a
            href="https://elcomercio.pe/vamos/mundo/las-10-mejores-ciudades-del-mundo-para-viajar-segun-el-ranking-worlds-best-cities-lista-viajes-internacionales-noticia/"
            target="_blank">Más
            Información</a></p>
        <video src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Video2.mp4?alt=media&token=4902e262-f401-42d8-a60f-d2bbb08436ea" controls width="800"></video>


    </section>

    <section>
        <h2>Audios</h2>
        <p>Para escoger un buen destino debes tomar el tiempo necesario para planificar con detalle tu viaje perfecto.
            <br>
            <br>
            <span style="color: rgb(78, 230, 192)">Relaxing Music</span>
        </p>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Audio1.mp3?alt=media&token=5a236dc1-1d87-4169-b6ac-2c30833761cd" controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Audio3.mp3?alt=media&token=6a0d0e10-8c88-4e4b-afd4-b47cf9d6043d" controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Audio2.mp3?alt=media&token=f73fad29-e833-4373-ab08-98fe353f4eb5" controls></audio>
        <audio src="https://firebasestorage.googleapis.com/v0/b/fotos-f682a.appspot.com/o/Audio4.mp3?alt=media&token=ece0c1d4-87cc-4847-9497-c7f5f0b20580" controls></audio>

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