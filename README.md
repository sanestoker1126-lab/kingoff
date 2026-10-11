# ST — Estoker Locations Money Services

## Sitio web
Repositorio preparado para alojar el sitio estático de Estoker Locations Money Services. La versión completa actual está disponible como archivo descargable en la conversación de ChatGPT: `ST_Estoker_Locations_Money_Services_Directorio_Con_Mapa.html`.

## Funciones del prototipo completo
- Directorio preparado con búsqueda y filtros por nombre, teléfono, ciudad, estado, ZIP, categoría y proveedor.
- Mapa Leaflet/OpenStreetMap para registros con coordenadas válidas.
- Ficha de negocio con enlaces a fuentes y estado de verificación.
- Registro de llamadas, notas y seguimiento.
- Importación y exportación CSV.

## Publicación en GitHub Pages
Cuando el archivo HTML completo se encuentre en la raíz como `index.html`, abre Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/ (root)` y guarda. La dirección aparecerá en ese panel cuando GitHub Pages termine la publicación.

## Limitaciones y calidad de datos
El archivo de prototipo aún debe copiarse íntegramente a `index.html` para servir como sitio web. Los datos locales importados y candidatos de OpenStreetMap no han sido verificados de forma independiente. No se debe inferir que una persona es propietaria del negocio sin evidencia. El estado y las notas de llamadas se guardan en el almacenamiento del navegador y no se sincronizan entre empleados; para uso multiusuario hace falta un backend autenticado y una base de datos.
