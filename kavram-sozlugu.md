**NLP**:Kelimeleri makinelerin anlayacağı numeric ifadelere çevirme işlemine verilen genel addır.
**Corpus** -> Metin Kümesi : Veri setleri halinde düzenlenmiş metin veya ses koleksiyonlarıdır.Bunlarla dil işleme işlemleri yapılır.
**Döküman**: En temel metin birimidir.Bir araya gelmeleriyle corpuslar oluşur.
            *Döküman*:Ev
            *Corpus*:Mahalle
**token**:Bir metni daha küçük parçalara böldükten sonra oluşan her parçaya token denir.
**NLP Pipeline**:Ham metin verilerini bilgisayarın analiz edebileceği ve modellerin öğrenebileceği yapılandırılmış bir formata dönüştürmek için uygulanan ardışık adımlar dizisidir.
**Regex**:Metin içerisindeki belirli kalıpları bulmak, düzenlemek ve değiştirmek için kullanılan karakter, kalıp yapısıdır.
**Metin Normalizasyonu**:Ham haldeki metin verilerini daha tutarlı, standart, işlenebilir tek bir standart tek bir biçime dönüştürme sürecidir.
**Unicode**:Dünya'daki tüm yazı sistemlerindeki karakterleri ve sembolleri tek bir standartta toplayan evrensel  bir karakter setidir.
**Tokenization**:Bir metnin anlamlı parçalara ayrılma işlemidir.Parçalara token dedik.
**n-gram**:Ardışık n adet öğrenin bir arada bulunma dizisidir.Dizinin her bir indexinin içerisinde bulunan n adet sayısını göre şekillenir.
                • Unigram (N=1): Metindeki tekli öğelerdir (her bir kelime veya karakter ayrı ele alınır).
                    	• Örnek (Kelime): ["elma", "armut", "portakal"]
                • Bigram (N=2): Yan yana gelen ikili öğe gruplarıdır.
                    	• Örnek (Kelime): ["elma armut", "armut portakal"]

**NLP Vocabulary**:Bir dil modelinin işleyebileceği,işleme sokabileceği kelime dağarcığı,kümesi.
**Stopwords**:Text içerisinde bulunan bağlaçlar ve edatlardır.Cümleden çıkarılmaları gerekir temiz bir işlem yapmak için.
**Lemmatization**:Kelimeyi köküne indirerek işlem yapacak kök dizini sağlamak.
**Stemming**:Kelimenin aldığı ekleri kaba bir şekilde keserek kök dizinine ayırma.Lemma daha detaylı ve titiz çalışır.
**Eklemeli Dil**
**Morfoloji**:Dili inceleyen bilim dalı.
**Bag of Words**:Kelimeleri bilgisayarın anlayacağı sayısal değerlere çeviren en temel vektörizasyon modeli.
**Document-term Matrix**:Bir veri koleksiyonundaki kelimlerin belge içerisinde geçme sıklıklarını matematiksel bir tablo olarak gösterir.
**Sparse (seyrek) matris**:Elemanlarının çok büyük çoğunluğu  değerine sahip olan matrislerdir.
**Supervised Learning**:Etiketli veri üzerinden makinenin öğrenerek bir sonraki tahmini yapması.
**Unsupervised Learning**:Etiketlenmemiş veri üzerinden öğrenip örüntü oluşturarak,bularak tahmin yapma
**Train-test split**:Verinin bir kısmını test için bir kısmınınında eğitim için kullanılarak normal öğrenime karşın doğruluk oranlarını  arttırmayı hedefler.
**Overfitting**:Eğitime ayrılan verinin çok fazla olması durumu ile makinenin testte kullandığı veri sonucunun ezbere dayalı olarak gelmesi durumu.
**Bayes Teoremi**:Yeni bir bilgi veya kanıt elde edildiğinde, bir olayın gerçekleşme olasılığının nasıl güncelleneceğini hesaplamaya yarayan temel bir koşullu olasılık kuralıdır.
**Naive Bayes**:Bayes Teoremi'ne dayanan,verileri kategorilere ayırmak 