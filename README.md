# geoiniciativas-widget


![GeoIniciativas](http://127.0.0.1:5500/assets/imgs/geoiniciativas.gif)

```html
<script>
    const  repoUrl = "https://geo-developers.github.io/geoiniciativas-widget",
           js = document.createElement("script");
           css = document.createElement("link");

    js.type = "text/javascript";
    js.src = repoUrl + "/geoiniciativas-widget.js";

    css.rel = "stylesheet"
    css.href = repoUrl + "//geoiniciativas-widget.css", d
    
    document.querySelector("head").appendChild(js);
    ocument.querySelector("head").appendChild(css);
</script>
```
