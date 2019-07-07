De zoekopdracht kan worden gebruikt om transacties, accounts, budgetten, enz te vinden.

Om uw zoekopdracht voor specifieke transacties te verkleinen, kunt u de volgende "modifiers" gebruiken. Deze zijn beperkt tot transacties en werken samen: als u transacties zoekt met een specifieke datum en een specifiek type, dan moet aan beide voorwaarden worden voldaan.

* Gebruik `amount:12.34` om transacties met *precies* dit bedrag te vinden. Gebruik punten (.) gebruiken als decimaal scheidingsteken.
* Je kan `amount_less:100.00` en `amount_more:15.02` op dezelfde manier gebruiken.
* Gebruik `amount_less` samen met `amount_more` om te zoeken naar een bandbreedte van bedragen.
* Gebruik `source:werkgever` om te zoeken naar transacties met een specifieke bronrekening.
* Gebruik `destination:walmart` om te zoeken naar transacties met een specifiek bestemmingsrekening.
* Gebruik `category:boodschappen` om te zoeken naar transacties met een specifieke categorie.
* Gebruik `budget:facturen` om te zoeken naar transacties met een specifiek budget.
* Gebruik `bill:insurance` om te zoeken naar transacties gekoppeld aan een specifiek contract.
* Gebruik `type:withdrawal` om te zoeken naar specifieke types. Ondersteund is: transfer, deposit, withdrawal.
* Gebruik `on:2017-02-19`, `before:2016-12-10` of `after:2015-08-30` om het datumbereik van de gevonden transacties te beperken.

Wat je *niet* kan doen met modifiers is het volgende:

* `source:mijn werkgever`: Je kan geen spaties gebruiken.
* `destination:"albert heijn"`: het gebruik van quotes helpt niet.
* `amount:€12,35`: gebruik geen valuta, en gebruik de punt als het decimale scheidingsteken.
* `on:today` of `before:30/5/17`: het enige ondersteunde formaat is `YYYY-MM-DD`.