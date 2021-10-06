# Fabrica-de-muebles
Una fábrica de productos de madera construye tres tipos de muebles: sillas, mesas y banquetas.

Las sillas vienen en dos formatos, altas y bajas, y tienen además un peso límite soportado. Mesas hay cuadradas y rectangulares, con una cantidad de lugares disponibles. Banquetas hay fijas y regulables, algunas con y otras sin respaldo.

Los atributos pueden salir de estas preguntas:
qué mueble?
qué formato?
cuánto vale?
cuánto peso soporta?
cuántas personas caben?
tiene respaldo?


Hay un stock inicial en un archivo en formato CSV (stock_muebles.csv)

El programa debe poder hacer lo siguiente:

Agregar muebles al stock.
Consultar los artículos mayores a un precio solicitado.
Contar la cantidad de cada mueble discriminado por tipo.



Datos de prueba:

Agrego el artículo silla, tipo baja, con precio $12001

Resultado de la consulta para un precio mayor a $12000, debe salir:
Mueble: mesa, Tipo: rectangular, Precio: $13476
Mueble: banqueta, Tipo: regulable, Precio: $15635
Mueble: silla, Tipo: alta, Precio: $13274
Mueble: banqueta, Tipo: fija, Precio: $16265
Mueble: silla, Tipo: baja, Precio: $12001

Consultando cantidad de banqueta fija:
Mueble: banqueta Tipo: fija Stock: 3
