<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->

 ### Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto


## Solucion
- Index

```html
<!DOCTYPE html>

<html lang="en">



<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Distri Dulces</title>

</head>



<body>

    <header>

        <h1><strong>Distri Dulces</strong></h1>

    </header>



    <main>

        <p>Bienvenidos a la empresa Distri Dulces en la cual contamos con una variedad de productos dirigidos al publico

            Son: los distintos productos que se pueden apreciar por su sabor, tamaño  textura</p>

        <p>

        <h3><u>Aqui encontraran informacion sobre nuestros servicios y productos</u></h3>

        </p>

        <nav>

            <a href="about.html" target="_blank" rel="noopener noreferrer">Acerca</a>

        </nav>



        <p>

        <h3><u> formas con las cuales nos pueden contactar</u></h3>

        </p>



        <nav>

            <a href="contact.html" target="_blank" rel="noopener noreferrer">contacto</a>

        </nav>

    </main>

    <footer>

        <p><span style="color: red;">Stiven Rojas Martinez</span></p>

    </footer>

</body>



</html>
```

- Contact

```html

<!DOCTYPE html>

<html lang="en">



<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Contacto</title>

</head>



<body>

    <header>

        <h1><strong>Contacto</strong></h1>

    </header>

    <main>

        <p>ingresar datos para contactarte</p>

        <form>

            <label for="nombre">Nombre:</label>

            <input type="tex" id="nombre"><br>

            <p>



            </p>

            <label for="email">Email</label>

            <input type="email" id="email"><br>

            <p>



            </p>

            <label for="whatsapp">Whatsapp</label>

            <input type="whatsapp" id="whatsapp"><br>

            <p>



            </p>

            <label for="mensaje">Mensaje</label><br>

            <textarea id="mensaje"></textarea><br>

            <p>



            </p>

            <input type="submit" value="Enviar">

        </form>

        <aside>

            <h3><u>Ubicacion</u></h3>

            <p>calle 56, Cra. 32 #22-|7, Medellín, Antioquia</p>

        </aside>

        <p>

        <h3><u>informacion sobre nuestros servicios y productos</u></h3>

        </p>

        <nav>

            <a href="about.html" target="_blank" rel="noopener noreferrer">Acerca</a>

        </nav>

        <p>

        <h3><u>volver al Inicio</u></h3>

        </p>

        <nav>

            <a href="intex.html" target="_blank" rel="noopener noreferrer">Inicio</a>

        </nav>

    </main>


    

    


    <!DOCTYPE html>

<html lang="en">



<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Sobre nosotros</title>

</head>



<body>

    <header>

        <h1><strong>Nosotros</strong></h1>

    </header>

    <section>

        <h2><u>Historia</u></h2>

        <p>Creamos esta empresa con la funcion de expandir nuestros negocios a nivel nacioanl con la cantidad de nuestros.

            </p>

    </section>

    <article>

        <h3><u>Mision y vision</u></h3>

        <p>

        <ul>

            <li>Nos encargamos de que nuestros productos sean de la mejor calidad para el consumo de aquellos

        </li>

            <li>La vision es mantener nuestras instalaciones </li>

        </ul>

        </p>

    </article>



    <p>

    <h3><u> formas para contactar</u></h3>

    </p>



    <nav>

        <a href="contact.html" target="_blank" rel="noopener noreferrer">contacto</a>

    </nav>

    <p>

    <h3><u>volver al Inicio</u></h3>

    </p>

    <nav>

        <a href="intex.html" target="_blank" rel="noopener noreferrer">Inicio</a>

    </nav>

    <footer>

        <p><span style="color: red;">Stiven Rojas Martinez </span></p>
    </footer>

</body>



</html>
```