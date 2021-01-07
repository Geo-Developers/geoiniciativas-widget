# geoiniciativas-widget


![GeoIniciativas](http://127.0.0.1:5500/assets/imgs/geoiniciativas.gif)

```html
<div class="geoiniciativas-widget" data-sheetid="1bF4YYH7bXPSLI___zMfh3tDfSxDlWWZLkkuT5vD4zHQ" data-tab="datos"></div>
<script>
    const  repoUrl = "https://geo-developers.github.io/geoiniciativas-widget",
           js = document.createElement("script");
           css = document.createElement("link");

    js.type = "text/javascript";
    js.src = repoUrl + "/geoiniciativas-widget.js";

    css.rel = "stylesheet"
    css.href = repoUrl + "/geoiniciativas-widget.css", d
    
    document.querySelector("head").appendChild(js);
    ocument.querySelector("head").appendChild(css);
</script>
```
