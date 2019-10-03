### Enseña al mundo tu página terminada

Bien hecho @{{ user.username }}, aquí tienes el resultado final: {{ pagesUrl }}

Has aprendido lo básico de HTML y lo has usado para crear una página web sencilla.

Aunque esto funciona, hay todavía mucho que puedes hacer para asegurarte de estar al día de las convenciones y estándares, como utilizar un validador de HTML.

{% if GHE_HOST %}
<h3 align="center"><a href="https://validator.w3.org/nu/?showsource=yes&doc=https://pages.{{ GHE_HOST }}/{{ user.login }}/{{ repo }}/">Ver validación</a></h3>
{% else %}
<h3 align="center"><a href="https://validator.w3.org/nu/?showsource=yes&doc=https://{{ user.login }}.github.io/{{ repo }}">Ver validación</a></h3>
{% endif %}

Si quieres, puedes establecer tu nueva página web como la página de inicio de tu navegador. Simplemente sigue los siguientes enlaces para más información:


- [Google Chrome](https://support.google.com/chrome/answer/95314?hl=en)
- [Safari](https://support.apple.com/guide/safari/set-your-homepage-ibrw1020/mac)
- [Firefox](https://support.mozilla.org/en-US/kb/how-to-set-the-home-page)
- [Microsoft Edge](https://support.microsoft.com/en-us/help/4027577/windows-change-your-home-page)
