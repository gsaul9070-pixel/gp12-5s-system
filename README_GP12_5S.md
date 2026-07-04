# Sistema GP12 Auditorías 5S

Archivos incluidos:

- `index.html`: pantalla de captura de auditoría 5S GP12. Ya incluye conexión a Firebase Firestore para guardar auditorías en la colección `auditorias_5s_gp12`.
- `dashboard.html`: dashboard GP12 con navegación hacia nueva auditoría.

## Uso en GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube `index.html` y `dashboard.html` a la raíz del repositorio.
3. En Settings > Pages, activa GitHub Pages desde la rama `main` y carpeta `/root`.
4. Abre la URL generada por GitHub Pages desde celular.

## Firebase

El archivo `index.html` ya tiene configurado el proyecto:

- Proyecto: `gp12-auditorias-5s`
- Colección Firestore: `auditorias_5s_gp12`

Antes de probar, asegúrate de tener Firestore Database activado y reglas temporales que permitan escritura durante pruebas.
