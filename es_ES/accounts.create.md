**Cuentas de gastos**

Solo crea cuentas de gastos para lugares donde gasta dinero.

**Cuentas de ingresos**

Solo cree cuentas de ingresos para lugares donde obtiene dinero.

**Cuentas de activos**

Si esta creando una cuenta de activos, debería llenar el "saldo inicial" y la fecha asociada. Solo pocas personas empiezan a usar Firefly III y tienen un saldo de 0.00. En todo caso, ya tienen un poco de dinero en su cuenta. Saque su estado de cuenta, lea el saldo vigente de la cuenta a la que está agregando y llénelo.

En cuanto a los roles disponibles:

- Usando "cuenta de activos predeterminada" para sus propias cuentas.
- Usando "cuenta de activos compartidos" para cuentas domésticas.
- Usando "cuenta de ahorro" para cuentas en las que ahorre dinero.
- Usar "tarjetas de crédito" para tarjetas de crédito. Usted puede añadir los detalles en otro momento.

**Pasivos**

Firefly III soporta pasivos. Puede añadir deudas, préstamos y otras obligaciones como medio para rastrearlos. Por cada uno de ellos, puede introducir la cantidad que debe y el interés que paga sobre ella.

*Pasivos y cantidades*

Digamos, por ejemplo, que debe 1000,-. La mejor manera de rastrear la cantidad es almacenar una nueva deuda en Firefly III en la cantidad de "-1000". De esta manera, su valor neto está influenciado y puede mover dinero al pasivo para pagarlo. Una vez que llega a cero, puede marcar la cuenta como inactiva y estar orgulloso de pagarla.

La otra manera sería que alguien le debe 1000,-. En tal caso, es **también** una buena idea almacenar la deuda como una cantidad negativa. Después de todo, no tiene el dinero ahora mismo y cuando esa persona le paga, influirá positivamente en su valor neto.

*Saldo virtual*

Digamos que usted quiere tener un mínimo de $100,- bajo cualquier circunstancia. Ingrese "-100" y Firefly III tomara en cuenta su saldo de $100,- como cero. Si está creando una cuenta de tarjeta de crédito, introduzca el límite de su tarjeta de crédito (por ejemplo $1000,-). Firefly III le mostrara correctamente que tanto de su limite utilizó.

If you want to read more about accounts, check out the [official documentation on accounts](https://docs.firefly-iii.org/concepts/accounts).