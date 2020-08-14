Die Suche kann zum Finden von Transaktionen, Konten, Kostenrahmen, etc. genutzt werden.

Um die Suche auf bestimmte Transaktionen einzugrenzen, stehen folgende Suchparameter zur Verfügung. Sie sind auf Transaktionen beschränkt und funktionieren in Kombination: Wenn Sie nach Transaktionen mit einem bestimmten Datum UND einem bestimmten Typ suchen, müssen beide Bedingungen erfüllt werden.

* Nutzen Sie `amount:12.34` um Transaktionen mit *exakt* diesem Betrag zu finden. Sie müssen Punkte (.) zum Trennen von Nachkommastellen benutzen.
* Sie können `amount_less:100.00` und `amount_more:15.02` entsprechend benutzen, um Transaktionen mit einem Betrag größer oder kleiner dem angegebenen zu verwenden.
* Nutzen Sie `amount_less` in Kombination mit `amount_more`, um nach Beträgen im angegebenen Bereich zu suchen.
* Nutzen Sie `source:Arbeitgeber` um nach Transaktionen von einem ausgehenden Konto zu suchen.
* Nutzen Sie `destination:Aldi` um nach Transaktionen zu dem angegebenen Zielkonto zu suchen.
* Nutzen Sie `category:Lebensmittel` um nach Transaktionen mit der angegebenen Kategorie zu suchen.
* Nutzen Sie `budget:Rechnungen` um nach Transaktionen zu suchen, die zu einem bestimmten Kostenrahmen gehören.
* Use `tag:groceries` to search for transactions with a specific tag.
* Use `bill:insurance` to search for transactions tied to a specific bill.
* Use `type:withdrawal` to search for specific types. Supported: transfer, deposit, withdrawal.
* Use `on:2017-02-19`, `before:2016-12-10` or `after:2015-08-30` to limit the date range of the transactions returned.
* Use `internal_reference:abc` or `external_id:def`.

Was Sie *nicht* mit Suchparametern machen können ist folgendes:

* `source:my employer`: you cannot use spaces. You must use `source:"my employer"` with double quotes. This also applies to the other fields of course.
* `amount:€12,35`: don't use currency denominators, and use the dot as the decimal separator.
* `on:today` or `before:30/5/17`: the only supported format is `YYYY-MM-DD`.