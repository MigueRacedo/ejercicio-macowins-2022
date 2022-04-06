# ejercicio-macowins-2022

Requerimientos:
- Saber el precio de venta de una prenda y sus tipos.
- Registrar las ventas de prendas y saber las ganancias de un determinado día.

Decisiones de desarrollo:
- Los tipos de prendas los modelamos momentaneamente como un Enum, ya que no poseen comportamiento.
- Los estados y formas de pagos son Interfaces, de la que heredan los distintos tipos de ellos que etienden un metodo de forma polimorfica para llegar a un resultado.
- Las ventas tiene una lista de prendas, y la caja tiene una lista de ventas.
- Cada instancia de una Venta, es una venta hecha en un dia.
