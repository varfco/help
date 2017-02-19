The search can be used to find transactions, accounts, budgets, etc.

To narrow down your search for specific transactions, you may use the following "modifiers". These are limited to transactions and work together: if you search for transactions with a specific date AND of a specific type, both conditions must be met.

* Use `amount_is:12.34` to find transactions with _exactly_ this amount. You must use dots (.) as decimal separator.
* You can use `amount_less:100.00` and `amount_more:15.02` in the same fashion.
* Use `amount_less` together with `amount_more` to search for a range of amounts.
* Use `source:employer` to search for transactions that have a specific source account.
* Use `destination:walmart` to search for transactions that have a specific destination account.
* Use `category:groceries` to search for transactions with a specific category.
* Use `budget:bills` to search for transactions with a specific budget.
* Use `bill:insurance` to search for transactions tied to a specific bill.
* Use `type:withdrawal` to search for specific types. Supported: transfer, deposit, withdrawal.


What you _cannot_ do with modifiers is the following:

* `source:my employer`: you cannot use spaces.
* `destination:"albert heijn"`: using quotes will not help.
* `amount:€12,35`: don't use currency denominators, and use the dot as the decimal separator.
* `date:today` or `date:30/5/17:` the only supported format is `YYYY-MM-DD`. 
