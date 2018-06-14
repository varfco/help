La ricerca può essere utilizzata per trovare transazioni, conti, budget, ecc.

Per restringere la tua ricerca a specifiche transazioni puoi utilizzare i seguenti "modificatori". Questi sono limitati alle transazioni e funzionano assieme: se cerchi una transazione con una spefica data E (AND) e di uno specifico tipo, devono valere entrambe le condizioni.

* Usa `amount:12.34` per trovare le transazioni che hanno *esattamente* questo importo. Devi utilizzare il punto (.) come separatore dei decimali.
* Allo stesso modo puoi usare `amount_less:100.00` e `amount_more:15.02` per trovare, rispettivamente, le transazioni con un importo minore o maggiore di quello indicato.
* Utilizza `amount_less` assieme ad `amount_more` per trovare le transazioni con un importo all'interno di un intervallo.
* Usa `source:lavoro` per cercare le transazioni che hanno un specifico conto di origine.
* Usa `destination:walmart` per cercare le transazioni che hanno uno specifico conto di destinazione.
* Usa `category:spesa` per cercare le transazioni di una specifica categoria.
* Usa `budget:bollette` per cercare le transazioni associate ad uno specifico budget.
* Usa `bill:assicurazione` per cercare le transazioni legate ad una specifica bolletta.
* Usa `type:withdrawal` per cercare le transazioni di uno specifico tipo. Tipi supportati: transfer (trasferimento), deposit (deposito), withdrawal (prelievo).
* Usa `on:2017-02-19` (il), `before:2016-12-10` (prima del) o `after:2015-08-30` (dopo il) per limitare la ricerca alle transazioni avvenute in certo intervallo di date.

Quello che *non* puoi fare con i modificatori comprende:

* `source:dato di lavoro`: non puoi usare gli spazi.
* `destination:"centro commerciale"`: utilizzare le virgolette non aiuta.
* `amount:€12,35`: non utilizzare i caratteri della valuta e non utilizzare il punto come separatore dei decimali.
* `on:today` (oggi) o `before:30/5/17`: l'unico formato supportato per le date è `AAAA-MM-GG`.