## Paso 10: Añade enlaces a tu lista

✅ ¡Marca eso
✅ como completado
✅ en tu lista!

Gran trabajo con las listas. Vamos a intentar añadir algunos enlaces, ¿te parece?

### Sobre los hiperenlaces

Los hiperenlaces permiten a las personas navegar entre las páginas de la web. Los enlaces se consiguen con la etiqueta de ancla, `<a>`, y tienen dos componentes principales: la ubicación a la que enlazan, y el contenido que debería funcionar como enlace. La ubicación del enlace se especifica como un atributo `href`, y el contenido que debería funcionar como enlace puede especificarse entre etiquetas de apertura y cierre, así:

{% if GHE_HOST %}
  https://pages.{{ GHE_HOST }}/{{ user.login }}/{{ repo }}
        ```html
      <li><a href="https://{{ GHE_HOST }}">Esto es un enlace a GitHub</a></li>
      ```
{% else %}
      ```html
      <li><a href="https://github.com">Esto es un enlace a GitHub</a></li>
      ```
{% endif %}

### :keyboard: Actividad: Crea los enlaces a tus páginas favoritas

Aplica este cambio sugerido, o sigue las instrucciones de más abajo si prefieres teclear el código manualmente. Ten en cuenta que el cambio sugerido puede no estar en el sitio correcto en tu lista, así que asegúrate de que está dentro de un par de etiquetas `<ol>` o `<ul>`.

```suggestion
      <li>Mi sitio favorito es <a href="https://github.com">GitHub</a></li>
```

1. Haz clic en **Files Changed**.
1. Haz clic en los puntos suspensivos (...) y selecciona **Edit file**.
1. En la lista que acabas de crear, añade un enlace a cada uno de tus sitios favoritos hacia sus respectivas URLs. Puedes hacer esto añadiendo una etiqueta de ancla de apertura, `<a>`, con un atributo `href` que indique la URL del sitio, el nombre del sitio dentro de la etiqueta de ancla, y una etiqueta de ancla de cierre, `</a>`. Aquí tienes un ejemplo de elemento de lista con enlace:

{% if GHE_HOST %}
        ```html
      <li><a href="https://{{ GHE_HOST }}">Esto es un enlace a GitHub</a></li>
      ```
{% else %}
      ```html
      <li><a href="https://github.com">Esto es un enlace a GitHub</a></li>
      ```
{% endif %}

1. En la sección _Commit changes_, introduce un mensaje de commit que describa lo que acabas de hacer.
2. Haz clic en **Commit changes**.

<hr>
<h3 align="center">Responderé cuando hayas confirmado algún cambio (commit) en este pull request.</h3>