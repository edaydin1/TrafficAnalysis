Genel Bakış
Amaç: Yıllara göre trafik kazalarını derinlemesine analiz etmek, veri kalıplarını keşfetmek ve potansiyel risk faktörlerini ortaya çıkarmak.

Analizler kapsamında; zaman, konum, hava durumu ve araç özellikleri gibi faktörlerin kaza sayılarıyla ilişkisi incelenmiştir.

Veri Seti & Yapısı
Veri, üç zaman dilimine ayrılmış CSV dosyalarından alınmıştır:

accidents_2005_to_2007.csv

accidents_2009_to_2011.csv

accidents_2012_to_2014.csv

Her satır bir trafik kazasını temsil eder ve içerik olarak şunları kapsar:

Tarih, saat, konum (post code, yol tipi),

Hava durumu ve yol koşulları,

Yaralanma seviyesi ve araç sayısı,

Koordinatlar (enlem, boylam) gibi detaylar.

Kurulum



Kullanılan Kütüphaneler
pandas & NumPy – Veri manipülasyonu

Matplotlib, Seaborn – Statik görselleştirmeler

GeoPandas, Folium – Coğrafi veri ve interaktif haritalar

Scikit-learn – Temel sınıflandırma/regresyon modelleri (opsiyonel kısımlar için)

Analiz Adımları
Veri Yükleme & Birleştirme

Farklı zaman dilimlerini kapsayan CSV dosyalarının okunması ve birleştirilmesi

Temizlik & Ön İşleme

Eksik verilerin tespiti ve işlenmesi

Gerekli kolonların seçimi, tarih formatlama

Keşifsel Veri Analizi (EDA)

Yıllara, aylara, gün saatine göre kaza trendleri

Lokasyonlara göre yoğunluk analizi

Görselleştirme

Zaman serisi grafikler, çubuk/grafik analizler

Harita üzerinde kaza yoğunluğu görselleştirmesi

Modelleme (opsiyonel)

Kaza şiddeti veya sayısı tahmini için basit sınıflandırma veya regresyon modelleri

Görselleştirmeler & Bulgu Örnekleri
📅 Trend Analizi: Belirli yıllarda ve sezonlarda kaza sayılarındaki artış/düşüş

📍 Coğrafi Yoğunluk: Bazı şehir ve yol kesimlerinde daha sık kazalar

🌦 Koşul Etkisi: Hava durumu ve yol şartlarının kaza sayılarına etkisi

🕓 Saatlik Dağılım: Günün yoğun saatlerinde kaza patlamaları

