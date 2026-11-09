# Nuvio Glass Badges — Dark Glass Edition

Pack visual con insignias PNG individuales, fondo transparente y estética glass: cuerpo oscuro tintado, degradado, borde luminoso, brillo superior y tipografía blanca. Incluye categorías técnicas y plataformas de streaming.

## Contenido
- `assets/`: imágenes PNG individuales agrupadas por categoría.
- `badges.json`: configuración de filtros con patrones regex y URLs de imagen de ejemplo.
- `badges-streaming.json`: configuración limitada a plataformas.
- `README.md`: instrucciones.

## Antes de importar
Las URLs de `imageURL` son plantillas: reemplaza `USERNAME/REPOSITORY` por el usuario y repositorio público donde alojes estos archivos. Sube el contenido completo manteniendo las carpetas.

URL del JSON una vez publicado:
`https://raw.githubusercontent.com/USERNAME/REPOSITORY/main/badges.json`

La compatibilidad exacta de campos y la ruta del menú pueden variar según la versión de Nuvio. Verifica el formato que acepta tu versión antes de importar.

## Plataformas
Las insignias de servicios solo se muestran si el addon incluye el nombre o alias de la plataforma en el título/metadatos de la fuente. No es posible inferir el servicio si el proveedor no lo informa.
