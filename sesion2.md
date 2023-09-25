<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->

## Actividad: Creando mi primer sitio web
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

### Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto

#### Index o página de inicio

```

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Mi primer sitio web</title>
</head>

<body>
    <header>
        <h1>Mi sitio web</h1>
    </header>

    <nav>
        <a href="Acerca.html">Acerca</a>
        <a href="Contacto.html">Contacto</a>
    </nav>
    <main>
        <p>Bienvenidos a mi sitio sobre empresas XYZ</p>
        <p>Aqui encontraran información sobre nuestros servicios y productos</p>
        <p>Esto es <strong>importante</strong></p>
    </main>
    <footer>
        <p>Copyright 2023 - Juan Perez</p>
        <p>juanperez@email.com</p>
    </footer>
</body>

</html>
```

#### Acerca

```

<!DOCTYPE html>
<html lang="en">

<head>

  <title>Sobre nosotros</title>
</head>

<body>

  <header>
    <h1>Sobre nosotros</h1>
  </header>
  <nav>
    <a href="Index.html">Inicio</a>
    <a href="Contacto.html">Contacto</a>
  </nav>

  <section>
    <h2>Historia</h2>
    <p>Fundada en 2010...</p>
    <article>
      <h3>Misión y Visión</h3>
      <p>Nuestra misión es...</p>
      <h1>Valores</h1>
      <ol>
        <li>Equidad</li>
        <li>Respeto</li>
        <li>Compromiso</li>
      </ol>
    </article>
  </section>

  <footer>
    <p>Copyright 2023 - Juan Perez</p>
  </footer>
</body>

</html>
```

#### Contacto

```

<!DOCTYPE html>
<html lang="en">

<head>

    <title>Contacto</title>
</head>

<body>
    <header>
        <h1>Contacto</h1>
    </header>
    <nav>
        <a href="Index.html">Inicio</a>
        <a href="Acerca.html">Acerca</a>
    </nav>
    <main>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre"><br>

            <label for="email">Email:</label>
            <input type="email" id="email"><br>

            <label for="mensaje">Mensaje:</label><br>
            <textarea id="mensaje"></textarea><br>
            <input type="submit" value="Enviar">

        </form>
        <aside>
            <h3>Ubicación</h3>
            <p>Calle Falsa 123</p>
            <p>Ver en <i><u>Google Maps</i></u></p>
        </aside>
    </main>
    <footer>
        <p>Copyright 2023 - Juan Perez</p>
    </footer>
</body>

</html>
```