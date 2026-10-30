# Verge Dynamics · sitio web

Sitio estático (HTML puro), bilingüe ES/EN.
Dirección: https://vergedynamics-sketch.github.io/vergedynamics/

## Estructura
- `index.html`: toda la página (estilos, textos ES/EN y scripts adentro).
- `assets/img/`: capturas del programa, logo (SVG) y gráficos del modelo.
- `assets/video/`: videos (MP4 720p) y sus portadas.
- `favicon.svg`: ícono de la pestaña.

## Editar textos
Cada texto está dos veces, una por idioma:
`<span data-l="es">…</span><span data-l="en">…</span>`. Cambiá los dos.

## Formulario de contacto
Usa Web3Forms (access key en `index.html`, campo `access_key`). Los mensajes llegan a vergedynamics@gmail.com.
Si cambia la dirección del sitio, actualizala en el panel de Web3Forms.

## Publicar cambios
Subí los archivos modificados al repo (rama `main`). GitHub Pages actualiza el sitio en uno o dos minutos.

## Dominio propio (cuando esté registrado)
1. Crear un archivo `CNAME` en la raíz con una sola línea: `vergedynamics.com.ar`
2. En el proveedor del dominio, cargar registros A hacia 185.199.108.153, 185.199.109.153, 185.199.110.153 y 185.199.111.153
   (y un CNAME `www` → `vergedynamics-sketch.github.io`).
3. En el repo: Settings → Pages → Custom domain → `vergedynamics.com.ar` y activar "Enforce HTTPS".
4. Actualizar la Website URL en Web3Forms.
