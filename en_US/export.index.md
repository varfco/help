This page allows you to export transactions. You will get a CSV file with *all* your transactions in it.

If you want more fine-grained control over the export, or if you want to export other files as well, please use the command line options.

**Command line**

The basic command for the command line is this: `php artisan firefly-iii:export-data`. Again, without a date it will simply export all your transactions in a CSV file called `yyyy_mm_dd_transactions.csv` in your current directory.

You can use the following options to expand the export. Note that some of these options may not yet work.

* `-start=yyyy-mm-dd`. Start date of the export.
* `-end=yyyy-mm-dd`. Start date of the export.
* `-accounts=1,2,3,4`. Only include these asset accounts or liabilities in the export of transactions.

You can expand the export using the following flags:

* `--export-accounts`. Creates a separate file with all your accounts and some meta data.
* `--export-budgets`. Creates a separate file with all your budgets and some meta data.
* `--export-categories`. Creates a separate file with all your categories and some meta data.
* `--export-tags`. Creates a separate file with all your tags and some meta data.
* `--export-recurring`. Creates a separate file with all your recurring transactions and some meta data.
* `--export-rules`. Creates a separate file with all your rules and some meta data.
* `--export-bills`. Creates a separate file with all your bills and some meta data.
* `--export-piggies`. Creates a separate file with all your piggy banks and some meta data.
* `--export-transactions`. If you use any of the flags in this list, transactions **won't be exported** unless you explicitely say so.


If you want to read more about exporting data, check out the [official documentation on exporting data](https://docs.firefly-iii.org/exporting-data/export).