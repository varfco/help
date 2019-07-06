**Cuentas de gastos**

Solo crea cuentas de gastos para lugares donde gastas dinero.

**Cuentas de ingresos**

Solo crea cuentas de ganancia para lugares donde consigues dinero.

**Cuentas de activos**

Si estas creando una cuenta de activos, deberías llenar el "saldo inicial" y la fecha correspondiente. Solo pocas personas empiezan a usar Firefly III y tienen un saldo de 0.00. En todo caso, ya tienen un poco de dinero en su cuenta. Salga de su administración. lea el saldo vigente de su cuenta a la que está agregando y llénelo.

Los roles que están disponibles:

- Usar "cuentas de activos predeterminadas" para tus propias cuentas.
- Usar "cuentas de activos compartidos" para cuentas domésticas.
- Usar "cuenta de ahorro" para cuentas en las que ahorre dinero.
- Usar "tarjetas de crédito" para tarjetas de crédito. Usted puede añadir los detalles en otro momento.

**Liabilities**

Firefly III supports liabilities. You can add debts, loans and other liabilities as a means to track these. For each of them, you can enter the amount that you owe and the interest you pay over it.

*Liabilities and amounts*

Let's say for the example you owe 1000,-. The best way to track the amount is by storing a new Debt in Firefly III in the amount of "-1000". This way, your net worth is influenced and you can move money into the liability to pay it off. Once it reaches zero, you can mark the account as inactive and be proud of paying it.

The other way around would be that somebody owes you 1000,-. In such a case, it's **also** a good idea to store the debt as a negative amount. After all, you don't have the money right now and when that person pays you, it will positively influence your net worth.

*Virtual balance*

Let's say you want to have a minimum balance of $100,- at all times. Enter "-100" and Firefly III will treat a balance of $100,- as zero. If you are creating a credit card account, enter the limit of your credit card (for example $1000,-). Firefly III will correctly display how far your limit is stretched.

If you want to read more about accounts, check out the [official documentation on accounts](https://firefly-iii.readthedocs.io/en/latest/concepts/accounts.html).