<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->


### Actividad: Propiedades de espaciado y unidades de medida
Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

Crea un nuevo archivo HTML y CSS.
En el archivo HTML, agrega el siguiente código:

```html

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

```css

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

- Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.

```css

.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}
```


- Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.


```css
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- Border: Agrega un borde de 5 píxeles de color rojo.

```css
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- Border-radius: Agrega un radio de esquina de 10 píxeles.

```css
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

- Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.

```css
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}
```

## Preguntas:
¿Qué es la propiedad margin?
-  establece el margen para los cuatro lados.

¿Qué es la propiedad padding?
- crea el espacio o área alrededor del contenido de un elemento.

¿Qué es la propiedad border?
- permite definir en una única regla todos los bordes de los elementos seleccionados.

¿Qué es la propiedad border-radius?
- establece el redondeo de la esquina superior izquierda del elemento.

¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?
- in: hace referencia a las pulgadas.
- cm: se refiere a los centímetros.
- mm: hace referencia a los milímetros.
- q: se refiere a un cuarto de la unidad.
- pt: un punto es igual a 1/72 de una pulgada.
- pc: una pica es igual a 12 puntos.
- px: esta etiqueta se refiere a los píxeles.