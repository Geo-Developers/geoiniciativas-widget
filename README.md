# geoiniciativas-widget

El objetivo de este proyecto es proporcionar un widget que facilite embeber los datos del [proyecto geoiniciativas](https://github.com/Geo-Developers/geoiniciativas) en cualquier web.

A continuación se puede ver una [demo](https://geo-developers.github.io/geoiniciativas-widget/).

[![Tabla screenshot](./table_screenshot.png)](https://geo-developers.github.io/geoiniciativas-widget/)

## Cómo usarlo

Simplemente tienes que copiar este código dentro de cualquier página HTML:

```html
<div class="geoiniciativas-widget" data-sheetid="1bF4YYH7bXPSLI___zMfh3tDfSxDlWWZLkkuT5vD4zHQ" data-tab="datos"></div>
<script>
    const  repoUrl = "https://geo-developers.github.io/geoiniciativas-widget",
           js = document.createElement("script");
           css = document.createElement("link");

    js.type = "text/javascript";
    js.src = repoUrl + "/geoiniciativas-widget.js";

    css.rel = "stylesheet"
    css.href = repoUrl + "/geoiniciativas-widget.css",
    
    document.querySelector("head").appendChild(js);
    document.querySelector("head").appendChild(css);
</script>
```

Reemplaza el valor del atributo "data-tab" por el nombre de [la pestaña](https://geo-developers.github.io/geoiniciativas/#/docs) que quieras cargar.

## Dudas y contribuciones

Para las dudas, mejoras y reporte de errores por favor [crea un nuevo issue](https://github.com/Geo-Developers/geoiniciativas-widget/issues).

### GeoEntusiastas

Si quieres ayudar con la recopilación de enlaces por favor visita: [geo-developers.github.io/geoiniciativas/#/](https://geo-developers.github.io/geoiniciativas/#/)

### Desarrolladores

Ayúdanos a evolucionar este widget, tenemos un montón de [mejoras pendientes](https://github.com/Geo-Developers/geoiniciativas-widget/issues). 

El código de este proyecto está licenciado bajo [GPL v3.0](https://github.com/Geo-Developers/geoiniciativas-widget/blob/main/LICENSE). 
