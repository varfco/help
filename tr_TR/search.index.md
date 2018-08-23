Arama işlemleri, hesapları, bütçeleri vb. bulmak için kullanılabilir.

Belirli işlemler için aramanızı daraltmak için aşağıdaki "değiştiricileri" kullanabilirsiniz. Bunlar işlemlerle sınırlıdır ve birlikte çalışırlar: belirli bir tarihe ve belirli bir türe sahip işlemleri ararsanız, her iki koşul da yerine getirilmelidir.

* Bu tutardan *tam olarak* olan işlemleri bulmak için `amount: 12.34` şeklinde kullanın. Onluk ayırıcı olarak nokta (.) kullanmanız gerekir.
* `amount_less: 100.00` kullanabilirsiniz ve `amount_more:15.02 ` aynı şekilde kullanabilirsiniz.
* Bir miktar aralık aramak için `amount_less` ile ` amount_more` kullanın.
* Belirli bir kaynak hesabı olan işlemleri aramak için `source:employer` kullanın.
* Belirli bir hedef hesabı olan işlemleri aramak için `destination:walmart` kullanın.
* Belirli bir kategoriye sahip işlemleri aramak için `category:groceries` kullanın.
* Belirli bir bütçeyle yapılan işlemleri aramak için `budgte:bills` kullanın.
* Belirli bir faturaya bağlı işlemleri aramak için `bill:insurance` kullanın.
* Belirli türleri aramak için `type:withdrawal` kullanın. Şunlar desteklenir: transfer, para yatırma, geri çekme.
* Döndürülen işlemlerin tarih aralığını sınırlamak için `on:2017-02-19`, `before:2016-12-10` veya `after:2015-08-30` kullanın.

Değiştiriciler ile aşağıdakileri *yapamazsınız*:

* `source:my employer`: boşluk kullanamazsınız.
* `destination:"albert heijn"`: çift tırnak işaretlerini kullanmak yardımcı olmayacaktır.
* `amount:€12,35`: para birimi payları kullanmayın ve ondalık ayırıcı olarak nokta kullanın.
* `on:today` or `before:30/5/17`: the only supported format is `YYYY-MM-DD`.