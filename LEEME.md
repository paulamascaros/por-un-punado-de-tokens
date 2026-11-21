# Por un puñado de tokens

Web estática de la serie de microrrelatos. No necesita nada instalado: son archivos HTML y una hoja de estilos.

## Publicarla en GitHub Pages

1. Crea una cuenta en github.com si no la tienes.
2. Pulsa **New repository**. Ponle de nombre `por-un-punado-de-tokens`, márcalo como **Public** y pulsa **Create repository**.
3. En el repositorio vacío, pulsa **uploading an existing file**. Arrastra todo el contenido de esta carpeta: `index.html`, `estilo.css` y la carpeta `relatos`. Pulsa **Commit changes**.
4. Ve a **Settings › Pages**. En **Source** elige **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`. Pulsa **Save**.
5. Espera un par de minutos. La web quedará en `https://TU-USUARIO.github.io/por-un-punado-de-tokens/`.

## Añadir un relato nuevo

1. Duplica uno de los archivos de `relatos/` y cámbiale el nombre (por ejemplo, `relatos/nuevo-relato.html`).
2. Cambia el título, la ilustración y los párrafos.
3. En `index.html`, añade el relato a la lista.
4. Actualiza los enlaces «Anterior» y «Siguiente» del relato que va antes.
5. Sube los archivos cambiados al repositorio con **Add file › Upload files**.
