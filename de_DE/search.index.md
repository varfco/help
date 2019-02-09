Die Suche kann zum Finden von Transaktionen, Konten, Kostenrahmen, etc. genutzt werden.

Um die Suche auf bestimmte Transaktionen einzugrenzen, stehen folgende Suchparameter zur Verfügung. Sie sind auf Transaktionen beschränkt und funktionieren in Kombination: Wenn Sie nach Transaktionen mit einem bestimmten Datum UND einem bestimmten Typ suchen, müssen beide Bedingungen erfüllt werden.

* Nutzen Sie `amount:12.34` um Transaktionen mit *exakt* diesem Betrag zu finden. Sie müssen Punkte (.) zum Trennen von Nachkommastellen benutzen.
* Sie können `amount_less:100.00` und `amount_more:15.02` entsprechend benutzen, um Transaktionen mit einem Betrag größer oder kleiner dem angegebenen zu verwenden.
* Nutzen Sie `amount_less` in Kombination mit `amount_more`, um nach Beträgen im angegebenen Bereich zu suchen.
* Nutzen Sie `source:Arbeitgeber` um nach Transaktionen von einem ausgehenden Konto zu suchen.
* Nutzen Sie `destination:Aldi` um nach Transaktionen zu dem angegebenen Zielkonto zu suchen.
* Nutzen Sie `category:Lebensmittel` um nach Transaktionen mit der angegebenen Kategorie zu suchen.
* Nutzen Sie `budget:Rechnungen` um nach Transaktionen zu suchen, die zu einem bestimmten Kostenrahmen gehören.
* Nutzen Sie `bill:Versicherung` um nach Transaktionen zu suchen, die mit einer bestimmten Rechnung verknüpft sind.
* Nutzen Sie `type:withdrawal` um nach bestimmten Typen zu suchen. Unterstützt werden "transfer" (Umbuchung), "deposit" (Einnahme) und "withdrawal" (Ausgabe).
* Nutzen Sie `on:2017-02-19` (exaktes Datum), `before:2016-12-10` (vor) oder `after:2015-08-30` (nach), um die Transaktionen nach einem Datum zu filtern.

Was Sie *nicht* mit Suchparametern machen können ist folgendes:

* `source:Mein Arbeitgeber`: Es können keine Leerzeichen verwendet werden.
* `destination:"Aldi Süd"`: Anführungszeichen helfen auch nicht.
* `amount:€12,35`: Es können keine Währungszeichen benutzt werden, außerdem muss ein Punkt als Dezimaltrennzeichen verwendet werden.
* `on:today` oder `before:30/5/17`: Das einzig unterstützte Datumsformat ist `JJJJ-MM-TT`.