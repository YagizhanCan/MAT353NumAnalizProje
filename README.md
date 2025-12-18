# SeismoSim-MDOF: Çok Katlı Yapıların Sismik Tepki Analizi ve Sayısal Modelleme

Bu proje, yapı mühendisliği ve sismoloji disiplinlerinde hayati öneme sahip olan gürültülü sensör verilerinin sayısal analiz yöntemleriyle işlenmesini ve çok katlı yapıların sismik yükler altındaki dinamik tepkilerinin modellenmesini amaçlar.

**MAT353 Nümerik Analiz Dersi Dönem Projesi** **İstanbul Medeniyet Üniversitesi - 2025**

## 👥 Geliştiriciler
* **Yağızhan Can** - 21120205711
* **Furkan Topçu** - 24120205080

## 🚀 Proje Özeti
Proje iki temel aşamadan oluşmaktadır:
1. **Veri Temizleme:** Sismik sinyallerin osilasyonlu yapısına uygun **Trigonometrik En Küçük Kareler (Least Squares)** yöntemi ile gürültü arındırma.
2. **Dinamik Simülasyon:** Çok Serbestlik Dereceli (MDOF) bir yapının hareket denklemlerinin **Runge-Kutta 4 (RK4)** ve **Euler** yöntemleri ile karşılaştırmalı çözümü.

## 🛠 Kullanılan Teknolojiler
* **Python 3.10**
* **NumPy:** Matris operasyonları ve vektörleştirme.
* **Pandas:** Performans metriklerinin tablolaştırılması.
* **Matplotlib:** Dinamik tepki, hata analizi ve enerji korunumu grafiklerinin oluşturulması.

## 📊 Öne Çıkan Bulgular
* **RK4 Kararlılığı:** RK4 yönteminin sönümsüz sistemlerde enerjiyi koruduğu ve stabil sonuçlar ürettiği kanıtlanmıştır.
* **Euler Iraksaması:** Euler yönteminin zaman adımı hassasiyetine bağlı olarak yapay enerji ürettiği ve ıraksadığı gözlemlenmiştir.
* **Sinyal Başarısı:** Trigonometrik regresyon ile gürültülü veride $R^2 = 0.98$ uyum başarısı yakalanmıştır.

## 📈 Örnek Çıktılar
Simülasyon sonucunda üretilen grafikler:
- Sismik Veri Temizleme Başarısı
- RK4 vs Euler Deplasman Karşılaştırması
- Enerji Korunumu Analizi (Kinetik & Potansiyel)

## 💻 Kurulum ve Çalıştırma
Projeyi Google Colab üzerinde veya yerel makinenizde çalıştırmak için:
1. Repoyu klonlayın: `git clone https://github.com/YagizhanCan/MAT353NumAnalizProje.git`
2. Gerekli kütüphaneleri yükleyin: `pip install numpy matplotlib pandas`
3. Notebook dosyasını çalıştırın.

## 📄 Lisans
Bu proje akademik amaçlarla geliştirilmiştir.# MAT353NumAnalizProje
