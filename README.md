# Dilan-yapay-zeka-ödev
MoMA Müze Koleksiyonu Veri Analizi
​Bu proje, Kaggle üzerinden alınan Museum of Modern Art (MoMA) koleksiyon verilerini kullanarak; veri temizleme, keşifsel veri analizi (EDA) ve görselleştirme adımlarını içermektedir.
​📌 Projenin Amacı
​Bu çalışma, dünyanın en kapsamlı modern sanat koleksiyonlarından birine sahip olan MoMA'daki eserlerin;
​Hangi departmanlarda yoğunlaştığını,
​En yaygın eser türlerinin neler olduğunu,
​Veri setindeki eksik değerlerin (missing values) durumunu analiz etmek amacıyla hazırlanmıştır.
​🛠️ Kullanılan Teknolojiler
​Proje kapsamında Python programlama dili ve aşağıdaki kütüphaneler kullanılmıştır:
​Pandas: Veri manülasyonu ve CSV dosyasının işlenmesi.
​Matplotlib & Seaborn: Verilerin sütun grafiklerine (bar chart) dökülerek görselleştirilmesi.
​Kagglehub: Güncel verinin doğrudan Kaggle sunucularından çekilmesi.
​📊 Veri Seti Hakkında
​Veri seti yaklaşık 130,000+ kayıt içermekte olup 21 farklı sütundan oluşmaktadır. Öne çıkan sütunlar şunlardır:
​Title: Eserin başlığı
​Artist ID & Name: Sanatçı bilgileri
​Department: Eserin bağlı olduğu müze departmanı
​Classification: Eserin sınıflandırılması (Fotoğraf, Çizim, Mimari vb.)
​Dimensions: Eser boyutları (Yükseklik, Genişlik, Ağırlık vb.)
​🚀 Analiz Adımları
​Veri Yükleme: kagglehub kütüphanesi ile en güncel MoMA verisi indirilmiş ve artworks.csv dosyası Pandas DataFrame'e dönüştürülmüştür.
​Genel Bakış: df.head() ve df.info() komutları ile verinin yapısı, sütun türleri ve bellek kullanımı incelenmiştir.
​Eksik Veri Analizi: df.isnull().sum() ile hangi alanlarda ne kadar veri kaybı olduğu saptanmıştır (Özellikle fiziksel ölçülerde yüksek oranda boş veri olduğu görülmüştür).
​Görselleştirme:
​Müzedeki departman dağılımı yatay sütun grafiği ile gösterilmiştir.
​En çok bulunan ilk 10 eser türü (Classification) belirlenerek görselleştirilmiştir.
​📈 Öne Çıkan Bulgular
​Müze koleksiyonunda bazı departmanların eser sayısı bakımından diğerlerinden çok daha baskın olduğu gözlemlenmiştir.
​Fiziksel boyut verileri (derinlik, ağırlık vb.) birçok eser için sisteme girilmemiştir.
Notebook:https://www.kaggle.com/code/dilan0015/notebook386e066d9e
Kaynak:https://www.kaggle.com/datasets/momanyc/museum-collection
