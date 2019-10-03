## Paso 4: Añadir una página de título

¡Tu página web empieza a tomar forma! Las etiquetas `html` y `body` son importantes, pero su efecto no es muy visible. A continuación, haremos un cambio visible, añadiendo un título a la página. El título de tu página se mostrará en la barra de título de tu navegador, o como el título de alguna de las pestañas que tienes abiertas. El título se usa también en muchos otros sitios.

![captura de pantalla del título en una pestaña del navegador](https://user-images.githubusercontent.com/16547949/41006294-e990b476-68ee-11e8-8cfa-67c72c132095.png)

La etiqueta de título tiene este aspecto:

```html
<title>Soy un título</title>
```

Pero la etiqueta de título debe estar dentro de una etiqueta `head`, o cabecera. A estas alturas te habrás dado cuenta de que las etiquetas siguen una estructura jerárquica. En nuestro anterior ejemplo, la etiqueta `html` era _madre_ de la etiqueta `body`. Igualmente, la etiqueta `head` será la madre de la etiqueta `title`, así:

```html
<head>
    <title>Soy un título</title>
</head>
```

Finalmente, las etiquetas `head` y `title` serán _hijas_ de la etiqueta `html`, pero _hermanas_ de la etiqueta `body`.

```html
<html>
    <head>
        <title>Soy un título</title>
    </head>

    <body>
        Algo de contenido.
    </body>
</html>
```

### :keyboard: Actividad: Añade un título a tu página


Aplica este cambio sugerido, o sigue las instrucciones de más abajo si prefieres teclear el código manualmente.

```suggestion
    <head>
        <title>Mi genial página web</title>
    </head>

```

1. Haz clic en **Files Changed**.
1. Haz clic en los puntos suspensivos (...) y selecciona **Edit file**.
1. Coloca una etiqueta `<head>` de apertura y una etiqueta `<title>` de apertura después de la primera etiqueta `html` de apertura, pero antes de la etiqueta `body`.
1. Escribe tu título después de la etiqueta `title` de apertura.
1. Coloca una etiqueta `</title>` de cierre y una etiqueta `</head>` de cierre después de tu nuevo título, pero antes de la etiqueta `body`. 
1. En la sección _Commit changes_, introduce un mensaje de commit que describa lo que acabas de hacer.
1. Asegúrate de que has seleccionado _Commit directly to the `add-index` branch_.
1. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando hayas confirmado algún cambio (commit) en este pull request.</h3>