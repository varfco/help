La ricerca può essere utilizzata per trovare transazioni, conti, budget, ecc.

Per restringere la tua ricerca a specifiche transazioni puoi utilizzare i seguenti "modificatori". Questi sono limitati alle transazioni e funzionano assieme: se cerchi una transazione con una spefica data E (AND) e di uno specifico tipo, devono valere entrambe le condizioni.

* Usa `amount:12.34` per trovare le transazioni che hanno *esattamente* questo importo. Devi utilizzare il punto (.) come separatore dei decimali.
* Allo stesso modo puoi usare `amount_less:100.00` e `amount_more:15.02` per trovare, rispettivamente, le transazioni con un importo minore o maggiore di quello indicato.
* Utilizza `amount_less` assieme ad `amount_more` per trovare le transazioni con un importo all'interno di un intervallo.
* Usa `source:lavoro` per cercare le transazioni che hanno un specifico conto di origine.
* Usa `destination:walmart` per cercare le transazioni che hanno uno specifico conto di destinazione.
* Usa `category:spesa` per cercare le transazioni di una specifica categoria.
* Usa `budget:bollette` per cercare le transazioni associate ad uno specifico budget.
* Usa `tag:spesa` per cercare le transazioni con una specifica etichetta.
* Usa `bill:assicurazione` per cercare le transazioni collegata ad una specifica bolletta.
* Usa `type:withdrawal` per cercare le transazioni di uno specifico tipo. Tipi supportati: transfer (trasferimento), deposit (deposito), withdrawal (prelievo).
* Usa `on:2017-02-19` (il), `before:2016-12-10` (prima del) o `after:2015-08-30` (dopo il) per limitare la ricerca alle transazioni avvenute in certo intervallo di date.
* Use `internal_reference:abc` or `external_id:def`.

Quello che *non* puoi fare con i modificatori comprende:

* `source:my employer`: you cannot use spaces. You must use `source:"my employer"` with double quotes. This also applies to the other fields of course.
* `amount:€12,35`: don't use currency denominators, and use the dot as the decimal separator.
* `on:today` or `before:30/5/17`: the only supported format is `YYYY-MM-DD`.