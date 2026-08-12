# SOFAM + Spliti — GitHub Pages

Sitio estático listo para publicar con GitHub Pages.

## URLs finales previstas

- `https://sofam.com.ar/`
- `https://sofam.com.ar/spliti/`
- `https://sofam.com.ar/spliti/privacidad/`
- `https://sofam.com.ar/spliti/terminos/`

También se incluyen alias de compatibilidad:

- `/spliti/termin/` → `/spliti/terminos/`
- `/spliti/privacy/` → `/spliti/privacidad/`

## Publicar en GitHub Pages

1. Crear un repositorio nuevo en GitHub.
2. Subir todos los archivos de esta carpeta a la rama `main`.
3. Ir a **Settings → Pages**.
4. En **Build and deployment**, elegir **Deploy from a branch**.
5. Seleccionar **main** y **/(root)**.
6. Guardar.

GitHub publicará primero una URL del tipo:

`https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`

## Usar `sofam.com.ar`

Cuando quieras conectar el dominio:

1. Renombrá `CNAME.example` a `CNAME`.
2. Hacé commit y push.
3. En **Settings → Pages → Custom domain**, indicá `sofam.com.ar`.
4. Configurá los registros DNS que GitHub te indique en el proveedor que administra tu dominio.

## Nota técnica

El sitio anterior estaba planteado con archivos PHP. GitHub Pages no ejecuta PHP, por eso esta versión está convertida a HTML/CSS estático y no requiere servidor.
