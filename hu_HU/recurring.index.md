Ez megmutat minden ismétlődő tranzakciót.

Az ismétlődő tranzakciók használatával aFirefly III automatikusan létrehozza a tranzakciókat. Ennek érdekében létre kell hozni egy ütemezett feladatot ami létrehozza ezeket a tranzakciókat.

Read more about recurring transactions in [the official documentation](https://docs.firefly-iii.org/advanced-concepts/recurring).

**Ütemezett feladat**

Azért, hogy a tranzakció ténylegesen automatikusan létre legyen hozva be kell állítani egy ütemezett feladatot. You can read about that on the [page in the official documentation about cron jobs](https://docs.firefly-iii.org/advanced-installation/cron).