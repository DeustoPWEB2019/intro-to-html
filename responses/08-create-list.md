## Paso 9: Crear una lista

Puedes ver tu sitio con la foto aquí: {{ pagesUrl }}

> Nota: A veces un sitio de GitHub Pages tarda algunos minutos en actualizarse. Si tus cambios todavía no se muestran pasados unos minutos, puedes intentar borrar la caché de tu navegador y refrescar la página.

### Listas ordenadas y sin ordenar

Las listas se usan por todo internet. Las hay de dos sabores: ordenadas y sin ordenar.

1. Esto
2. es una
3. lista ordenada

Y...

- Esto
- es una
- lista sin ordenar

Puedes crear una lista usando la etiqueta `<ol>` para listas ordenadas (u _ordered list_) y la etiqueta `<ul>` para listas sin ordenar (_unordered lists_). Después, cada elemento de la lista debe rodearse de una etiqueta `<li>`, o elemento de lista (_list item_). Aquí tienes el código que genera la lista que te mostraba más arriba:

```html
<ol>
    <li>Esto</li>
    <li>es una</li>
    <li>lista ordenada</li>
</ol>
```

Y...

```html
<ul>
    <li>Esto</li>
    <li>es una</li>
    <li>lista sin ordenar</li>
</ul>
```

Para la siguiente actividad, vas a crear una lista de tus sitios web favoritos. Después, añadiremos los enlaces para que puedas acceder a ellos rápidamente. Por ahora céntrate en crear los elementos de la lista.

### :keyboard: Actividad: Crea una lista de tus sitios web favoritos

1. Edita el archivo `index.html` en tu branch `master` [usando este enlace directo]({{ repoUrl }}/edit/master/index.html) o yendo a la pestaña **Code**, haciendo clic en el archivo `index.html` y clic en el icono del lápiz :pencil: para editar el HTML.
1. Dentro de la etiqueta `body`, crea una lista, da igual si es ordenada o sin ordenar, de tus sitios web favoritos. 
1. En la sección _Commit changes_, introduce un mensaje de commit que describa lo que acabas de hacer.
1. Asegúrate de que has seleccionado _Create a new branch for this commit and start a pull request_.
1. Dale a tu branch un nombre descriptivo, como `add-links-and-lists`.
1. Haz clic en **Commit changes**.
1. Dale un título a tu pull request, y una descripción.
1. Haz clic en **Create pull request.**

<hr>
<h3 align="center">Busca mi respuesta en el nuevo pull request.</h3>
