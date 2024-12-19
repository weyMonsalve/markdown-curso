<!--encabezados-HEADINGS -->

# my title
## my title h2
### my title h3
#### my title h4
##### my title h5
###### my title h6

<!--PARA TEXTO ITALICO-->
This is an *italic* text

<!--PARA TEXTO EN NEGRITA-->
This is an **strong** text

<!--PARA TEXTO EN TACHADO-->
esto es un ~~texto~~ tachado

<!--PARA LISTAS DESORDENADAS UL-->
* MANZANA
    * manzana2
* NARANJA
    * naranja2
* MANGO
    * mango2

<!--PARA LISTAS ORDENADAS -->
1. NARANJA
    1. naranja2
2. MANZANA
    1. manzana2
3. MANGO
    1. mango2


<!--PARA GENERAR ENLACES -->
[azure.com](https://dev.azure.com/sancolombia/callcenter/_sprints/taskboard/callcenter%20Team/callcenter/Sprint%201)

<!--PARA GENERAR CITAS -->

> Esta es una cita

<!--PARA GENERAR UNA LINEA DIVISORA U HORIZONTAL O UNA ETIQUETA HR EN HTML-->

---
---

<!--PARA GENERAR CODIGO PARA UNA PUBLICACION EN UN BLOG-->
"cosole.log("Hello")"

```javascript
  <script>
        // Generar un número aleatorio entre 1 y 6
        let numeroPC = Math.floor(Math.random() * 6) + 1;

        // Pedir al jugador que adivine el número
        let numeroJugador = parseInt(prompt("Adivina el número de la cara del dado (entre 1 y 6)"));

        // Función para verificar si el jugador adivinó el número
        function eleccion(jugada) {
            let resultado; // Declarar la variable para almacenar el mensaje
            if (jugada === numeroPC) {
                resultado = "¡Adivinaste el número!";
            } else {
                resultado = "Ese no es el número. El número correcto era " + numeroPC + ".";
            }
            return resultado; // Devolver el resultado al final
        }

        // Mostrar el resultado al jugador
        alert(eleccion(numeroJugador));
    </script>

```

```python
print(hello world)
```

```html
<h1>Hola Mundo</h1>
```

<!--PARA GENERAR TABLAS CON COLUMNAS Y CELDAS-->

| Table         | Are           | Cool   |
|---------------|---------------|--------|
| Col 3 is      | rigth-aligned |  $1600 |
| Col 2 is      | centered      |     $12|
| Zebra stripes | Are neat      |      $1|


<!--PARA GENERAR IMAGENES O LLAMAR ENLACES-->
![visual studio logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTebRBzJhW1BDg-1D9keKRb3e0GXVBUBI1ORA&s)

![visual studio logo](vscode.png)


<!--GITHUB MARKDOWN-->

*[X] TAREA 1 <!--la X significa TO DO-->
*[] TAREA 2 <!--tarea no esta realiada-->
*[] TAREA 3
*[] TAREA 4
