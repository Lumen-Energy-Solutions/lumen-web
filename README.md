# Sitio web de Lumen Energy Solutions

Página estática, sin framework ni paso de build: un `index.html` y la
carpeta `assets/` con logos, capturas de la plataforma e imágenes del
diagrama de arquitectura.

## Estructura

```
index.html            la página completa (HTML, CSS y JS en un archivo)
assets/clientes/      logos de los clientes
assets/plataforma/    capturas de Lumen Cloud
assets/hw/            equipos del diagrama de arquitectura
assets/lumen-*.png    logo; lumen-wordmark.png es el del encabezado
netlify.toml          publica la raíz, sin build
```

## Cómo se publica

Netlify está conectado a la rama `main`: cada push se despliega solo.

## Cómo verla en local

```sh
python3 -m http.server 8000   # y abrir http://localhost:8000
```
