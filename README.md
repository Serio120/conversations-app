# Conversations App

Archivo HTML estático para organizar conversaciones con modelos de IA, con metadatos, mensajes, imágenes y notas personales editables.

## Uso local

Desde la carpeta del proyecto, inicia un servidor HTTP local:

```bash
python -m http.server 8000
```

Abre [http://localhost:8000](http://localhost:8000) en el navegador. También puedes abrir directamente la versión que quieras consultar, por ejemplo `index_v27.html`.

## Versiones

El repositorio conserva distintas iteraciones de la aplicación (`index_v2.html` a `index_v27.html`) para mantener la evolución del diseño. La página `index.html` actúa como índice de entrada.

## Privacidad

Antes de publicar una conversación, revisa y elimina nombres, direcciones, identificadores de conversaciones, rutas locales, datos del navegador, credenciales y cualquier contenido que no quieras hacer público. No incluyas volcados de pestañas abiertas ni metadatos de sesión.

Las primeras versiones contenían metadatos de pestañas del navegador y enlaces de conversaciones. Esta propuesta los elimina de las páginas actuales, pero no borra los valores de commits anteriores. Si necesitas retirarlos del historial Git, será necesaria una limpieza coordinada del historial y revisión de clones y forks.

## Despliegue

Puedes publicar los archivos estáticos en cualquier servicio de hosting compatible con HTML, CSS y JavaScript, por ejemplo GitHub Pages o Netlify.
