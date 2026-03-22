Sleep Health and Lifestyle Analysis

Bu proje, bireylerin yaşam tarzı alışkanlıklarının uyku kalitesi ve genel sağlık parametreleri (tansiyon, stres vb.) 
üzerindeki etkilerini analiz etmek amacıyla hazırlanmıştır.Bu çalışma, veri temizleme, özellik mühendisliği ve keşifçi veri analizi (EDA) süreçlerini içerir.

Veri Seti Hakkında
Bu çalışmada kullanılan Sleep Health and Lifestyle Dataset, 374 bireyden toplanan verileri içermektedir. Veri seti Kaggle'dan hazır olarak alınmıştır. Veri seti aşağıdaki temel parametreleri kapsamaktadır:
- Demografik Bilgiler: Yaş, Cinsiyet, Meslek.
- Uyku Verileri: Uyku Süresi, Uyku Kalitesi.
- Sağlık Göstergeleri: Fiziksel Aktivite Düzeyi, Stres Seviyesi, BMI Kategorisi, Kan Basıncı (Tansiyon), Kalp Atış Hızı ve Günlük Adım Sayısı.
- Uyku Bozuklukları: (None, Insomnia, Sleep Apnea).

 Öne Çıkan Bulgular
Analizlerim sonucunda elde ettiğim bazı şaşırtıcı sonuçlar:
- Tansiyonun Gerçek Nedeni: Stres seviyesi ile tansiyon arasında doğrudan bir bağ saptanmazken, BMI (Kilo durumu)ile tansiyon arasında çok güçlü bir korelasyon bulunmuştur.
- Yaş ve Uyku: Beklentilerin aksine, 50 yaş üstü bireylerin veri setindeki en kaliteli uykuya sahip olduğu görülmüştür.
- Mesleki Stres: Satış Temsilcileri ve Doktorlar, en yüksek stres seviyesine sahip meslek grupları olarak öne çıkmaktadır.

 Kullanılan Teknolojiler & Teknikler
- Python: Veri işleme ve analiz.
- Pandas: Veri temizleme ve Feature Engineering (Tansiyon verisinin Systolic/Diastolic olarak ayrılması).
- Seaborn & Matplotlib: Veri görselleştirme (Box Plot, RegPlot, Line Plot).
- Git & GitHub: Versiyon kontrolü.

 Klasör Yapısı
- data/: Analiz edilen ham veri seti.
- notebook/: Tüm analiz adımlarının ve yorumların bulunduğu Jupyter Notebook dosyası.

Hazırlayan: Ebru Arık - AI Operator Student
