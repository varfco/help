A kereséssel lehet megtalálni tranzakciókat, számlákat, költségkereteket, stb.

A következő "módosítók" használhatóak a keresés bizonyos tranzakciókra szűkítésére. Ezek lekorlátozzák a tranzakciók számát és együttműködnek: bizonyos dátumú ÉS típusú tranzakciók keresésekor mindkét feltételnek teljesülnie kell.

* Use `amount:12.34` to find transactions with *exactly* this amount. You must use dots (.) as decimal separator.
* You can use `amount_less:100.00` and `amount_more:15.02` in the same fashion.
* Use `amount_less` together with `amount_more` to search for a range of amounts.
* Use `source:employer` to search for transactions that have a specific source account.
* Use `destination:walmart` to search for transactions that have a specific destination account.
* Use `category:groceries` to search for transactions with a specific category.
* Use `budget:bills` to search for transactions with a specific budget.
* Use `bill:insurance` to search for transactions tied to a specific bill.
* Use `type:withdrawal` to search for specific types. Supported: transfer, deposit, withdrawal.
* Use `on:2017-02-19`, `before:2016-12-10` or `after:2015-08-30` to limit the date range of the transactions returned.

A következőket *nem lehet* megtenni a módosítókkal:

* `source:my employer`: nem lehet szóközöket használni.
* `destination:"albert heijn"`: az idézőjelek használata nem segít.
* `amount:€12,35`: a pénznem szimbóluma nem használható és pontot (.) kell használni a tizedesjegyek elválasztásához.
* `on:today` vagy `before:30/5/17`: az egyetlen támogatott formátum a `YYYY-MM-DD`.