# Portfolio de Victoria Sánchez

Versión con portada de montaña y logos originales, sin avatar ni foto personal.

## Subir a GitHub

1. Descomprimir este ZIP.
2. En el repositorio vacío, hacer clic en "uploading an existing file".
3. Arrastrar la carpeta dist completa y este README.md al área de carga.
4. Pulsar "Commit changes".

En GitHub debe quedar la carpeta dist directamente en la raíz del repositorio.
Dentro de dist están index.html, style.css, app.js y assets.
No subir el archivo ZIP ni la carpeta exterior que Windows puede crear al descomprimirlo.

## Publicar en Vercel

Importar este repositorio como nuevo proyecto.
Framework Preset: Other
Root Directory: dejar por defecto (raíz del repositorio)
Build Command: dejar vacío; desactivar cualquier comando automático si aparece.
Output Directory: dist

Es un sitio estático: no necesita instalar dependencias, servidor, base de datos ni claves.

## Ejecutar localmente

Servir la carpeta dist con un servidor estático, por ejemplo Live Server de Visual Studio Code.
git add .
git commit -m "Agregar portfolio"
git push
