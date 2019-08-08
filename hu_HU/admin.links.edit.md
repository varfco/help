Az utólag létrehozott tranzakció szerkeszthetőek. A kapcsolatok három tulajdonsággal írhatóak le:

* A leírás. Ez egyértelmű.
* Bejövő leírás. Ez megadja, hogy "A" tranzakciót hogyan befolyásolja "B". Képzeljük el, hogy "B" tranzakció "berepül" és valahogy módosítja az "A" tranzakciót.
* Kimenő leírás. Ez megadja, hogy "B" tranzakciót befolyásolja "A" tranzakció. Ugyanaz mint az előző példában, csak fordítva.

Az összes tranzakció kapcsolat szerkeszthető, de egyedieknek kell lenniük.

A tranzakciók kapcsolatáról további információ [a hivatalos dokumentációban](https://firefly-iii.readthedocs.io/en/latest/advanced/links.html) található.