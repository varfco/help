Wyszukiwanie może być używane do znalezienia transakcji, kont, budżetów itp.

Aby zawęzić wyszukiwanie do konkretnych transakcji, możesz użyć następujących "modyfikatorów". Są one ograniczone do transakcji i działają razem: jeśli szukasz transakcji z określoną datą ORAZ określonym rodzajem, muszą być spełnione oba warunki. Wyszukiwanie transakcji po koncie źródłowym, docelowym, kategorii itd. może uwzględniać wielkość liter (zależy od bazy danych).

* Użyj `amount:12.34` aby znaleźć transakcje z *dokładnie* tą kwotą. Musisz użyć kropki (.) jako separatora dziesiętnego.
* Możesz użyć `amount_less:100.00` i `amount_more:15.02` w ten sam sposób.
* Użyj `amount_less` razem z `amount_more` aby wyszukać zakres kwot.
* Użyj `source:employer` aby wyszukać transakcje, które mają określone konto źródłowe.
* Użyj `destination:walmart` aby wyszukać transakcje, które mają określone konto docelowe.
* Użyj `category:zakupy` aby wyszukać transakcje z określoną kategorią.
* Użyj `budget:rachunki` aby wyszukać transakcje z określonym budżetem.
* Użyj `tag:zakupy` aby wyszukać transakcje z określonym tagiem.
* Użyj `bill:ubezpieczenie` aby wyszukać transakcje związane z określonym rachunkiem.
* Użyj `type:withdrawal` aby wyszukać określone typy. Obsługiwane: transfer, wpłaty, wypłata.
* Użyj `on:2017-02-19`, `before:2016-12-10` lub `after:2015-08-30` aby ograniczyć zakres dat transakcji.
* Use `internal_reference:abc` or `external_id:def`.

Czego *nie możesz* zrobić z modyfikatorami:

* `source:my employer`: you cannot use spaces. You must use `source:"my employer"` with double quotes. This also applies to the other fields of course.
* `amount:€12,35`: don't use currency denominators, and use the dot as the decimal separator.
* `on:today` or `before:30/5/17`: the only supported format is `YYYY-MM-DD`.