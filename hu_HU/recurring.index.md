Ez megmutat minden ismétlődő tranzakciót.

Az ismétlődő tranzakciók használatával aFirefly III automatikusan létrehozza a tranzakciókat. Ennek érdekében létre kell hozni egy ütemezett feladatot ami létrehozza ezeket a tranzakciókat.

Az ismétlődő tranzakciókról további információ [a hivatalos dokumentációban](https://firefly-iii.readthedocs.io/en/latest/advanced/recurring.html) található.

**Ütemezett feladat**

Azért, hogy a tranzakció ténylegesen automatikusan létre legyen hozva be kell állítani egy ütemezett feladatot. You can read about that on the [page in the official documentation about cron jobs](https://firefly-iii.readthedocs.io/en/latest/installation/cronjob.html).