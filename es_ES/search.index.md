La búsqueda se puede usar para encontrar transacciones, cuentas; presupuestos, etc.

Para restringir su búsqueda de transacciones especificas, usted puede usar los siguientes modificadores. Estos se limitan a las transacciones y trabajan en conjunto: si usted busca transacciones con una fecha especifico Y de un tipo especifico, se deben cumplir ambas condiciones.

* Use`monto:12.34`para encontrar transacciones con*exactamente*este monto. usted debe usar puntos (.) como separador decimal.
* Usted puede usar `monto_menos:100.00`y`monto_mas: 15.02`en la misma moda.
* Use`monto_menos`junto con`monto_mas`para buscar un rango de montos.
* Use`fuente:empleador`para buscar transacciones que tienen una cuenta especifica.
* Use`destino:walmart`para buscar transacciones que tienen una cuenta especifica.
* Use `categoría:comestibles`para buscar transacciones con una categoría especifica.
* Use`presupuesto: facturas`para buscar transacciones con un presupuesto especifico.
* Use `tag:comestibles`para buscar transacciones con una etiqueta especifica.
* Use `factura:seguro` para buscar transacciones enlazadas a una factura especifica.
* Use `tipo:retiro` para buscar tipos específicos. Soportados: transferencia, deposito, retiro.
* Use `on:2017-02-19`, `before:2016-12-10` o `after:2015-08-30` para limitar el rango de fecha de las transacciones devueltas.
* Use `internal_reference:abc` or `external_id:def`.

Lo que usted * no puede * hacer con modificadores es lo siguiente:

* `source:my employer`: you cannot use spaces. You must use `source:"my employer"` with double quotes. This also applies to the other fields of course.
* `amount:€12,35`: don't use currency denominators, and use the dot as the decimal separator.
* `on:today` or `before:30/5/17`: the only supported format is `YYYY-MM-DD`.