# 5.5- Sonic Harbor Visualization

https://public.tableau.com/views/el_artico_discos/Historia1?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link

El siguiente trabajo se basa en el análisis del actual inventario de la tienda de venta online [El Ártico Discos](https://www.discogs.com/es/seller/elarticodiscos/profile "El Ártico Discos"). Se nos ha encargado la visualización de algunas estadísticas relevantes respecto al precio, condición y sellos musicales.

En los datos recibicos se ha utilizado la información de la columna format para establecer varias categorías en los datos. Se ha extraido la info de estos registros para crear las siguientes columnas booleanas: `['promo', 'vinyl', 'special', 'CD', 'single', 'album']`

Estas columnas se han utilizado para contrastar el precio medio de los items catalogados según pertenecian a una u otra categoría, viendo que el mayor precio medio se úbica en los registros de la categoría album, seguido de aquellos catalogados como promo.

También se han realizado gráficos sobre los tops ded artistas y sellos musicales, así como mediciones en base a la condición del item y la funda, contrastando estas categorías con el precio de los items. De esta última medición se ha observado que la diferencia de precio media entre los items catalogados cómo mint(sin abrir) y near mint(abierto, en condición óptima) es muy pequeña, lo que podría llevar a una revisión de los mismos con el objetivo de aumentar las ganancias.
