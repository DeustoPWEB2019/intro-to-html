## Paso 7: Añade una imagen

¡Fantástico! Los títulos de sección te permiten resaltar segmentos de tu página web.

Hasta ahora, hemos utilizado etiquetas que se valen por sí solas. Sin embargo, a veces necesitamos especificar un atributo, que es información que la etiqueta necesita para poder funcionar. Por ejemplo, para mostrar una imagen, necesitamos una etiqueta `<img>`, pero también necesitamos un atributo que indique la fuente (o _source_) para que el navegador sepa dónde localizar la imagen. Podemos añadir un atributo así:

```html
<img src="https://octodex.github.com/images/vinyltocat.png">
```

Te darás cuenta también de que la etiqueta de imagen no necesita cerrarse, porque se considera una etiqueta [vacía](https://www.w3schools.com/html/html_elements.asp).

### :keyboard: Actividad: Añade una imagen a tu página web

Aplica este cambio sugerido, o sigue las instrucciones de más abajo si prefieres teclear el código manualmente.

```suggestion
<img src="{{ user.avatarUrl }}">

```

1. Haz clic en **Files Changed**.
1. Haz clic en los puntos suspensivos (...) y selecciona **Edit file**.
1. Coloca una etiqueta `<img>` de apertura entre las etiquetas `body`. Recuerda: ¡no necesitas cerrar una etiqueta `<img>`!
1. Establece el atributo `src` con la ubicación de la imagen que te gustaría mostrar. Puedes usar tu foto de perfil: `{{ user.avatarUrl }}`
1. En la sección _Commit changes_, introduce un mensaje de commit que describa lo que acabas de hacer.
1. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando hayas confirmado algún cambio (commit) en este pull request.</h3>