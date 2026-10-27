# Colombia Compite · Tableros

Tableros interactivos de competitividad, uno por índice, con una portada que los reúne.

| Archivo | Tablero |
|---|---|
| `index.html` | Portada |
| `idc.html` | Índice Departamental de Competitividad (IDC) |
| `icc.html` | Índice de Competitividad de Ciudades (ICC) |
| `isem.html` | Índice Subnacional de Emprendimiento (ISEM) |
| `msbg.html` | Medición Subregional de Brechas de Género (MSBG) |

Son páginas estáticas: no hay build ni dependencias que instalar. Los cinco archivos deben estar en la misma carpeta.
D3 y Chart.js se cargan desde jsDelivr y la fuente Figtree desde Google Fonts, así que se necesita conexión a internet.

## Publicar con GitHub Pages
1. En el repositorio: Settings → Pages.
2. Source: *Deploy from a branch*; Branch: `main` y carpeta `/ (root)`.
3. La portada queda en `https://<usuario>.github.io/<repositorio>/`.

## Fuente tipográfica
La marca usa TT Commons (licencia comercial). Si tienes los archivos, ponlos en `fonts/`
como `TTCommons-Regular.woff2`, `TTCommons-Medium.woff2` y `TTCommons-Bold.woff2`; mientras tanto se usa Figtree.
