https://drive.google.com/file/d/1lvpcq0ku-9qBeSLOgSCjH7OKL2IyPsQC/view?usp=sharing

# Power BI Satış ve Müşteri Analizi Projesi

Bu Power BI projesinde, belirli bir e-ticaret veya satış verisi setini analiz ederek iş süreçlerine ve müşteri davranışlarına dair içgörüler sunmayı hedefledim.
## Proje Amacı

Bu Power BI projesinin temel amacı, ham verilerden anlamlı bilgiler çıkararak aşağıdaki konularda iş birimlerine destek olmaktır:

* **Genel Satış Performansını Takip Etmek:** Toplam ciro, sipariş sayısı, ortalama sepet değeri gibi anahtar performans göstergelerini (KPI) izlemek.
* **Müşteri Davranışlarını Anlamak:** Müşteri demografisi (cinsiyet, yaş grubu), bölgesel dağılım ve satın alma alışkanlıkları hakkında içgörüler edinmek.
* **Ürün ve Kategori Performansını Değerlendirmek:** Hangi ürün kategorilerinin en çok ciro getirdiğini, envanter yönetimi ve ürün geliştirme stratejilerini desteklemek.
* **Veri Odaklı Karar Alma Kültürünü Desteklemek:** İş birimlerinin daha bilinçli ve stratejik kararlar almasına yardımcı olmak.

## Kullanılan Veri Kaynakları

Bu proje için kullanılan veriler, şirketin satış ve müşteri veri tabanlarından elde edilmiştir. Temel veri tabloları şunlardır:

* `Kullanıcılar`: Müşteri demografik bilgileri (Ad, Soyad, Cinsiyet, Doğum Tarihi vb.).
* `Siparişler`: Sipariş bazında genel bilgiler (Sipariş Tarihi, Toplam Fiyat, Kullanıcı ID'si vb.).
* `SiparişDetayları`: Her bir sipariş içindeki ürün bazlı detaylar (Ürün ID'si, Miktar, Birim Fiyatı vb.).
* `Adresler`: Kullanıcı ve sipariş adres bilgileri (İl, İlçe, Ülke vb.).
* `Ürünler`: Ürün detayları (Ürün Adı, Kategorisi, Markası vb.).

## Veri Modeli

Projenin temelini oluşturan veri modeli, yukarıda belirtilen tablolar arasında kurulmuş ilişkilerle (bire-çok, çoka-çok vb.) verilerin doğru bir şekilde birleştirilmesini ve analiz edilmesini sağlamaktadır. Bu model, karmaşık soruların kolayca yanıtlanabilmesine olanak tanır.

*Aşağıdaki görsel, veri modelinin bir özetini sunmaktadır:*
![image 1](https://github.com/user-attachments/assets/e93df1b5-1f12-42f3-8e05-41460c3d5fbd)

## Rapor Sayfaları ve İçerikleri

Power BI raporu, farklı iş birimlerinin ihtiyaçlarına yönelik olarak tasarlanmış çeşitli sayfalardan oluşmaktadır:

### 1. Genel Bakış / Satış Performansı Sayfası

Bu sayfa, şirketin genel satış performansını gösteren anahtar metrikleri sunar.

* **KPI Kartları:** Toplam Ciro, Toplam Sipariş Sayısı, Müşteri Başına Ortalama Ciro gibi kritik göstergeler.
* **Haftalık Satış Trendleri:** Satış adetlerinin zaman içindeki değişimini gösteren grafikler.
* **Bölgesel Satış Dağılımı:** Türkiye haritası üzerinde veya çubuk grafiklerle bölgelere göre satış performansının görselleştirilmesi.
* **Sipariş Sayısına Göre Ciro Eğilimi:** Sipariş sayısı ile ciro arasındaki ilişkinin incelenmesi.

*Aşağıdaki görsel, Genel Bakış sayfasının bir özetini sunmaktadır:*
![image 2](https://github.com/user-attachments/assets/2a9a0a00-9cc2-4b10-9c86-8bc862d3e7f1)

### 2. Müşteri Perspektifi Sayfası

Bu sayfa, müşteri demografisi ve satın alma davranışları hakkında detaylı içgörüler sunar.

* **Müşteri Sayıları:** Toplam müşteri sayısı, cinsiyete göre dağılım (Kadın/Erkek).
* **Bölgesel Müşteri Yoğunluğu:** Bölgelere göre müşteri sayılarının gösterimi.
* **Yaş Grubuna Göre Ciro Analizi:** Hangi yaş gruplarının daha fazla ciroya katkıda bulunduğunun incelenmesi.
* **En Çok Ciro Yapan Müşteriler:** Yüksek değerli müşterilerin listesi.

*Aşağıdaki görsel, Müşteri Perspektifi sayfasının bir özetini sunmaktadır:*
![image 3](https://github.com/user-attachments/assets/4d62e7c4-5f18-4505-9bcb-54d0febe77db)

### 3. Kategori Perspektifi Sayfası

Bu sayfa, ürün kategorilerinin performansını ve ciroya katkılarını analiz eder.

* **Ana Kategori ve Üst Kategoriye Göre Toplam Ciro:** TreeMap (ağaç haritası) görseli ile en çok ciro getiren ürün kategorilerinin hiyerarşik gösterimi.
* **Ürün Bazında Ciro Analizi:** Belirli ürünlerin veya markaların performansının incelenmesi.

*Aşağıdaki görsel, Kategori Perspektifi sayfasının bir özetini sunmaktadır:*
![image 4](https://github.com/user-attachments/assets/f4f0b231-8707-4dde-be21-a62b1eb25f91)

## Nasıl Kullanılır?

1.  **Power BI Desktop:** Projeyi açmak ve düzenlemek için Microsoft Power BI Desktop yazılımına sahip olmanız gerekir.
2.  **Verileri Yenileme:** Raporu açtıktan sonra, `Giriş` sekmesindeki `Verileri Yenile` butonuna tıklayarak en güncel verileri çekebilirsiniz. (Veri kaynağı bağlantılarının doğru yapılandırıldığından emin olun.)
3.  **Filtreler ve Dilimleyiciler:** Her sayfada bulunan filtreleri ve dilimleyicileri kullanarak verileri farklı kriterlere göre filtreleyebilir ve detaylandırabilirsiniz.
4.  **Etkileşimli Görseller:** Görsellere tıklayarak veya belirli veri noktalarının üzerine gelerek daha fazla detaya ulaşabilirsiniz.

## Katkılar ve Geri Bildirim

Bu projenin sürekli iyileştirilmesi için geri bildirimleriniz ve katkılarınız değerlidir. Herhangi bir hata, geliştirme önerisi veya yeni bir analiz ihtiyacı için lütfen iletişime geçiniz!

---
