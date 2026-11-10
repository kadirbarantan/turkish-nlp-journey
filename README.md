****Türkçe ile İngilizce Ön İşleme Arasındaki Farklar****
*Benim Yorumum*:Türkçe eklemeli bir dil modeli olduğu için anlam farklılaşması daha fazla oluyor.Bu yzüden de işlemler biraz daha farklı oluyor.Bunun için popüler olan(bu alanda), Java temelli ancak eklenti ile Python'da kullandığımız Zemberek kütüphanesini kullanıyoruz.
    İngilizce'de kelimenin kökünü atmak kolaydır.   Playing -> Play
                                        Türkçe'de   Koyun -> Koy   Anlam değişimine uğrar.

    İngilizce'de stop_words'ler kolayca ayrıştırılabilirken, Türkçe'de onlar da ek aldığı için önce köküne inilmeli ardından stop_words düşürme işlemi               yapılmalıdır.