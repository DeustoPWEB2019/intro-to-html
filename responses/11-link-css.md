## Paso 12: Hacerlo bonito

Puede que te estés preguntando por qué tu página no tiene el mismo aspecto que la que te enseñé al principio del curso. Es porque el HTML aporta la estructura a tu página, pero las etiquetas sencillas que has aprendido hasta ahora no le dicen al navegador cómo quieres que se vea cada uno de los elementos.

La apariencia de cada elemento de la página se define mediante estilos, y esto es materia para otro curso. Por ahora, he añadido una [hoja de estilos]({{ repoUrl }}/blob/add-style/style.css) por ti. 

Para que tu página web utilice tu nueva hoja de estilos, solamente tienes que enlazarla desde `<head>` en tu archivo `index.html`. Si incluyes el siguiente enlace en tu archivo `index.html`, tu página web empezará a usar el archivo `css` que hará que tu sitio se vea genial.

```html
  <link rel="stylesheet" href="style.css">
```

Como ejemplo, tu archivo `index.html` podría ser así:

```html
    <head>
        <title>Soy un título</title>
        <link rel="stylesheet" href="style.css">
    </head>
```

### :keyboard: Actividad: Crea un estilo para tu sitio

1. Edita el archivo `index.html` en el branch `add-style` utilizando este [enlace directo]({{ repoUrl }}/edit/add-style/index.html) o yendo a la pestaña **Code**, seleccionando el branch `add-style`,haciendo clic en el archivo `index.html` y clic en el icono del lápiz :pencil: para editar.
1. Entre las etiquetas `<head>`, añade esto: `<link rel="stylesheet" href="style.css">`.
1. En la sección _Commit changes_, introduce un mensaje de commit que describa lo que acabas de hacer.
1. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando hayas confirmado algún cambio (commit) en este pull request.</h3>