# 5.5- Sonic Harbor Visualization

![dashboard](https://github.com/jvr0/5.5-visualization/blob/main/img/dashboard.png)

El siguiente proyecto consiste en un encargo por parte de la tienda online [El Ártico Discos](https://www.discogs.com/es/seller/elarticodiscos/profile "El Ártico Discos"). Se ha encargo la realización de un análisis de los items en el inventario.

## Obtención y limpieza de datos
Los datos han sido obtenidos de forma directa por parte del cliente. Su obtención ha consistido en la exportación del inventario actual a través de la plataforma de venta Discogs. Una vez se recogieron los datos se procedió a su limpieza.

En este proyecto la preparación de la información ha consistido en la eliminación de columnas irrelevantes de cara al análisis del inventario, tales como la úbicación física del item en el almacen o los comentarios personales del cliente.

También se han corregido las categorías de ciertos items y se han creado nuevas columnas, cuya información ha sido obtenida de la columna original `format`. Esta nueva información son elementos booleanos que definen el item según sea vinilo, single o CD. 

## Creación dashboard

Durante la creación del dashboard se ha tenido en cuenta el objetivo último de cara al cliente, el resumen en un golpe de vista del inventario. Para esto se han creado varios gráficos presentando la siguiente información:
- precio medio en base a la condición establecida del item y la funda.
- artículos en stockaje según oferta y tipo de item.
- recuento de top artistas y sellos discográficos.

#### Enlace a dashboard

https://public.tableau.com/views/inven_artico/Dashboard1?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link