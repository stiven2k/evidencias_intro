<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->

### Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

### Solucion

```html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>


<body>
    <table border="1" cellpadding="5" cellspacing="10">
        <thead>
            <tr>
                <th rowspan="2">Codigo</th>
                <th>nombre</th>
                <th colspan=3">descripcion</th>
                <th>precio</th>
                <th>stock</th>
                <th>fecha de creacion</th>

            </tr>

        </thead>

        <tbody>
            <tr>
                <td rowspan="2"> 5421
                </td>
                <th rowspan="2">Balocitos Jet </th>
                <td colspan="3">
Jet es una chocolatina colombiana producida y comercializada por el grupo empresarial colombiano Nutresa desde 1961. Su presentación habitual es en una barra de 12 gramos en un empaque de papel y aluminio de color azul con el logo la imagen de un avión tipo Jet.</td>
                <td>34.000 COP</td>
                <td>15</td>
                <td>1990-21-54</td>
            </tr>

            <tr>
                <td colspan="3">T El target fue pensado especialmente para niños, pero a través de los años se fue ampliando a jóvenes, adultos y adultos mayores. El consumo de esta chocolatina forma parte una tradición.</td>

                <th>00</th>


            </tr>


            <tr>
                <td rowspan="2"> 6666
                </td>
                <th rowspan="2">Chocoramo</th>
                <td colspan="3">es un ponqué simple, tradicional, fresco, rico y conveniente para calmar el hambre cuando no el tiempo es escaso</td>
                <td>2.000COP</td>
                <td>32</td>
                <td>2001-01-02</td>
            </tr>

            <tr>
                <td colspan="3">sin duda alguna este ponqué de empaque naranja hace parte de la tradición colombiana.</td>
                    <th>00</th>

            </tr>

            <tr>

                <td rowspan="2"> 6675
                </td>
                <th rowspan="2">Choclitos </th>
                <td colspan="3">un snack rico, crujiente, divertido que te lleva a una inigualable experiencia de sabor. Este producto ya está en la lista de solicitud de presupuesto.</td>
                <td>2.500COP</td>
                <td>10</td>
                <td>2000-04-10</td>
            </tr>
            <tr>

                <td colspan="3">maíz, aceite vegetal de palma, sabor artificial a limón(sal, acido cítrico E330), glutamato monosódico E621, azúcar, fécula de maíz, sabor artificial a limón, ají.</td>

                <th>00</th>

            </tr>

            <tr>
                <td rowspan="2"> 2213
                </td>
                <th rowspan="2">Bon Bon Bum</th>
                <td colspan="3">BON BON BUM fue un producto exitoso por su innovación al ser un caramelo relleno de chicle.</td>
                <td>500 COP</td>
                <td>9</td>
                <td>2019-09-09</td>

            </tr>

            <tr>
                <td colspan="3">además de su inconfundible sabor. Desde ese momento se convirtió en el producto estrella de COLOMBINA y la punta de lanza para conquistar nuevos mercados.</td>

                <th>00</th>

            </tr>

            <tr>
                <td rowspan="2"> 4444
                </td>
                <th rowspan="2">Minichips</th>
                <td colspan="3">Las MiniSIM se identifican porque en la cara que está el chip vas a ver una gran cantidad de plástico sobrante, y son tarjetas tan grandes como la punta de un dedo.</td>
                <td>1.200 COP</td>
                <td>5</td>
                <td>2023-02-02</td>

            </tr>
            <tr>
                <td colspan="3">aporta 178 kcal por envase, el cual contiene una sola porción, lo que equivale a un 9% de tu alimentación diaria</td>

                <th>00</th>
            </tr>

            <tr>
                <td rowspan="2"> 5483
                </td>
                <th rowspan="2">Frunas</th>
                <td colspan="3">Golosina de caramelo masticable envuelta en papel.</td>
                <td>500 COP</td>
                <td>67</td>
                <td>2023-03-08</td>
            </tr>
            <td colspan="3">Azúcar, jarabe de glucosa, aceite vegetal, agentes de glaseado (cera carnauba, goma laca), estabilizador (goma arábiga), maltodextrina, reguladores de acidez (ácido cítrico, ácido málico, citrato trisódico, ácido láctico), espesantes (almidón modificado (SIN 1422), (SIN 1450)), humectante (jarabe de sorbitol), aromas .</td>

            <th>00</th>
            <tr>
                <td rowspan="2"> 7764
                </td>
                <th rowspan="2">Super Coco</th>
                <td colspan="3">Es mucho mas que una golosina, es una tradicion que te hace recordar y vivir momentos especiales. </td>
                <td>700 COP</td>
                <td>150</td>
                <td>2022-04-29</td>
            </tr>

            <tr>
                <td colspan="3">Este bombon esta hecho de coco natural, su indescriptible sensacion hacen que nuestro Bombon Supercoco sea sencillamente insuperable.</td>
                <th>00</th>
            </tr>

            <tr>
                <td rowspan="2"> 0091
                </td>
                <th rowspan="2">Papas Margaritas</th>
                <td colspan="3">Papas Margarita Natural combina la frescura de láminas de papa seleccionadas con un toque saladito listo para disfrutar.</td>
                <td>1.500 COP</td>
                <td>22</td>
                <td>2020-03-23</td>

            <tr>
                <td colspan="3">serán el aliado indispensable que necesites para la lonchera de tus hijos, acompañar alimentos o simplemente para combatir el hambre.</td>
                <th>00</th>
            </tr>

            <tr>
                <td rowspan="2"> 9987
                </td>
                <th rowspan="2">bubbaloo</th>
                <td colspan="3">Se considera como la primera goma de mascar con un centro líquido.</td>
                <td>450  COP</td>
                <td>35</td>
                <td>2022-06-27</td>
            </tr>
            <tr>
                <td colspan="3">El nombre Bubbaloo fue creado a partir del juego de palabras Bubblegum (chicle de burbuja, en inglés) con la expresión cubana "Babalu", usada en forma de saludo.</td>
                <th>00</th>
            </tr>

            <tr>
                <td rowspan="2"> 5429
                </td>
                <th rowspan="2"> Nucita</th>
                <td colspan="3">Es un dulce cremoso con leche y cacao para disfrutarse a cualquier hora del día. Por sus ricos sabores ha demostrado ser un encanto al paladar de los niños.</td>
                <td>800 COP</td>
                <td>1</td>
                <td>2022-02-08</td>
            </tr>

            <tr>
                <td colspan="3"> todo el mundo son conquistados por su práctica y llamativa presentación, excelente precio y novedosa combinación trisabor.</td>
                <th>0</th>
            </tr>

        </tbody>




    </table>
</body>

</html>
```