## Paso 3: Añadir estructura al documento HTML

¡Buen trabajo abriendo ese pull request, @{{ user.username }}! Me he adelantado y he cerrado tu [issue anterior]({{ welcomeLink }}). 

Este pull request tiene algún contenido, pero no tiene nada de la estructura HTML que indica al navegador web cómo estructura el contenido. Todas las páginas creadas con HTML deben contener etiquetas que las identifiquen como tales. Esas etiquetas tienen este aspecto:

```html
<html>
    <body>
        El contenido HTML va aquí.
    </body>
</html>
```

Verás que hay dos copias de la etiqueta `html`, y dos copias de la etiqueta `body`. Llamamos a estas las etiquetas de _apertura_ y de _cierre_. Revisemos el mismo código, añadiendo un poco de explicación.

- `<html>` es la etiqueta de apertura de HTML
- `<body>` es la etiqueta de apertura de `body` (el cuerpo de la página)
- `</body>` es la etiqueta de cierre de `body` (el cuerpo de la página)
- `</html>` es la etiqueta de cierre de HTML

En HTML, los espacios no importan en realidad. Hemos añadido algunas tabulaciones para que el código sea más fácil de leer, pero el navegador ignorará ese espaciado extra. Ahora que has entendido los bloques con los que se constuye el HTML, añadamos algo más de HTML al archivo `index.html` de tu proyecto.

### :keyboard: Actividad: Añade las etiquetas `html` y `body` a tu `index.html`

Aplica este cambio sugerido, o sigue las instrucciones de más abajo si prefieres teclear el código manualmente.

```suggestion
<html>

  <body>
    ¡Hola, persona estupenda! 
  </body>

</html>
```

1. Haz clic en **Files Changed** para ver el recién añadido archivo `index.html`.
1. Haz clic en los puntos suspensivos (...) y selecciona **Edit file**.
1. Antes del contenido existente, añade una etiqueta `<html>` de apertura y una etiqueta `<body>` de apertura.
1. Después del contenido existente, añade una etiqueta `</body>` de cierre y una etiqueta `</html>` de cierre.
1. En la sección _Commit changes_, introduce un mensaje de commit que describa lo que acabas de hacer.
1. Asegúrate de que has seleccionado _Commit directly to the `add-index` branch_.
1. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando hayas confirmado algún cambio (commit) en este pull request.</h3>