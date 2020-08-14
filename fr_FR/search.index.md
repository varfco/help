La recherche peut être utilisée pour trouver des transactions, des comptes, des budgets, etc.

Pour affiner votre recherche de transactions spécifiques, vous pouvez utiliser les "modificateurs" suivants. Ceux-ci sont limités aux transactions et fonctionnent ensemble : Si vous recherchez des transactions avec une date spécifique ET d'un type spécifique, les deux conditions doivent être remplies.

* Utilisez `amount:12.34` pour trouver des transactions avec *exactement* Cette somme. Vous devez utiliser des points (.) comme séparateur décimal.
* Vous pouvez utiliser `amount_less:100.00` et `amount_more:15.02` de la même manière.
* Utilisez `amount_less` ensemble avec `amount_more` pour rechercher une plage de montants.
* Utiliser `source: employeur` pour rechercher des transactions qui ont un compte source spécifique.
* Utilisez `destination:walmart` pour rechercher des transactions qui ont un compte de destination spécifique.
* Utilisez `category:épicerie` pour rechercher des transactions avec une catégorie spécifique.
* Utilisez `budget:factures` pour rechercher des transactions avec un budget spécifique.
* Utilisez `tag:épicerie` pour rechercher des transactions avec un tag spécifique.
* Utilisez `bill:assurance` pour rechercher des transactions liées à une facture spécifique.
* Utilisez `type:withdrawal` pour rechercher un type de transaction spécifique. Valeurs supportées : transfer, deposit, withdrawal.
* Utilisez `on:2017-02-19`, `before:2016-12-10` ou `after:2015-08-30` pour limiter la plage de date des transactions retournées.
* Use `internal_reference:abc` or `external_id:def`.

Ce que vous *ne pouvez pas* faire avec des modificateurs :

* `source:my employer`: you cannot use spaces. You must use `source:"my employer"` with double quotes. This also applies to the other fields of course.
* `amount:€12,35`: don't use currency denominators, and use the dot as the decimal separator.
* `on:today` or `before:30/5/17`: the only supported format is `YYYY-MM-DD`.