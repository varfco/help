La búsqueda se puede usar para encontrar transacciones, cuentas; presupuestos, etc.

Para restringir su búsqueda de transacciones especificas, usted puede usar los siguientes modificadores. Estos se limitan a las transacciones y trabajan en conjunto: si usted busca transacciones con una fecha especifico Y de un tipo especifico, se deben cumplir ambas condiciones.

* Use`monto:12.34`para encontrar transacciones con*exactamente*este monto. usted debe usar puntos (.) como separador decimal.
* Usted puede usar `monto_menos:100.00`y`monto_mas: 15.02`en la misma moda.
* Use`monto_menos`junto con`monto_mas`para buscar un rango de montos.
* Use`fuente:empleador`para buscar transacciones que tienen una cuenta especifica.
* Use`destino:walmart`para buscar transacciones que tienen una cuenta especifica.
* Use `categoría:comestibles`para buscar transacciones con una categoría especifica.
* Use`presupuesto: facturas`para buscar transacciones con un presupuesto especifico.
* Use `tag:groceries` to search for transactions with a specific tag.
* Use `bill:insurance` to search for transactions tied to a specific bill.
* Use `type:withdrawal` to search for specific types. Supported: transfer, deposit, withdrawal.
* Use `on:2017-02-19`, `before:2016-12-10` or `after:2015-08-30` to limit the date range of the transactions returned.

Lo que usted * no puede * hacer con modificadores es lo siguiente:

* `source:mi empleador`: usted no puede usar espacios.
* `destination:"albert heijn"`: no ayudara el uso de comillas.
* `amount:€12,35`: no use denominaciones de moneras, y use el punto como el separador decimal.
* `on:today` or `before:30/5/17`: the only supported format is `YYYY-MM-DD`.