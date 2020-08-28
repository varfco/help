**Nákladové účty**

Only create expense accounts for places where you spend money.

**Účty výnosů**

Only create revenue accounts for places where you get money from.

**Účty aktiv**

Pokud vytváříte účet aktiv, měli byste vyplnit "počáteční zůstatek" a související data. Velmi málo lidí začíná používat Firefly III a zůstatek mají 0,00. Místo toho již mají nějaké peníze na jejich účet. Get out your administration, read the current balance of the account you're adding, and fill it in.

As for the roles that are available:

- Use "default asset account" for your own accounts.
- Use "shared asset account" for household accounts.
- Use "savings account" for accounts on which you save money.
- Use "credit card" for credit cards. You can add some details later.

**Liabilities**

Firefly III supports liabilities. You can add debts, loans and other liabilities as a means to track these. For each of them, you can enter the amount that you owe and the interest you pay over it.

*Liabilities and amounts*

Let's say for the example you owe 1000,-. The best way to track the amount is by storing a new Debt in Firefly III in the amount of "-1000". This way, your net worth is influenced and you can move money into the liability to pay it off. Once it reaches zero, you can mark the account as inactive and be proud of paying it.

The other way around would be that somebody owes you 1000,-. In such a case, it's **also** a good idea to store the debt as a negative amount. After all, you don't have the money right now and when that person pays you, it will positively influence your net worth.

*Virtual balance*

Let's say you want to have a minimum balance of $100,- at all times. Enter "-100" and Firefly III will treat a balance of $100,- as zero. If you are creating a credit card account, enter the limit of your credit card (for example $1000,-). Firefly III will correctly display how far your limit is stretched.

If you want to read more about accounts, check out the [official documentation on accounts](https://docs.firefly-iii.org/concepts/accounts).