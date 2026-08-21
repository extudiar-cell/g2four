# G2 Four — Librería Web de Presets

Repositorio de presets `.zptc` para el Zoom G2 Four / G2X Four.

## Estructura

- `index.html` — la web que lista los presets y los carga en la pedalera.
  Publicada como GitHub Pages, es la URL que abres desde el navegador
  (con la pedalera conectada por USB) para pinchar un preset y enviarlo.
- `presets/` — aquí van los archivos `.zptc`. Cualquier archivo que subas
  a esta carpeta aparece automáticamente en la lista de la web (puede
  tardar unos minutos en refrescarse la caché de jsDelivr).

## Cómo añadir un preset nuevo

1. Entra en la carpeta `presets/` de este repo en GitHub.
2. Botón **Add file → Upload files**.
3. Arrastra el `.zptc`.
4. Commit changes.
5. Recarga la lista en la web (botón "Guardar y cargar lista"). Si no
   aparece enseguida, espera unos minutos o purga la caché en
   https://www.jsdelivr.com/tools/purge pegando la URL del archivo.

## Configuración de la web (primera vez)

Al abrir `index.html`, en el apartado "Repositorio de GitHub" rellena:

- Usuario: tu usuario de GitHub
- Repositorio: el nombre de este repo
- Rama: `main`
- Carpeta: `presets`

Y pulsa "Guardar y cargar lista". Queda guardado en el navegador para
las próximas veces.
