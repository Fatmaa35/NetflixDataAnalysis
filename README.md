# Netflix Veri Analizi ve İş Zekası (BI) Raporu

Bu proje, ham bir Netflix veri setini işleyerek içerik stratejisi, büyüme trendleri ve izleyici tercihleri üzerine interaktif grafikler ve iş zekası öngörüleri üreten bir Python veri analizi çalışmasıdır.

##  Özellikler

- **Veri Temizleme:** Eksik verilerin doldurulması, yinelenen kayıtların silinmesi ve veri tiplerinin standartlaştırılması.
- **İçerik Dağılımı Analizi:** Film (Movie) ve Dizi (TV Show) oranlarının karşılaştırılması.
- **Trend Analizi:** Yıllara göre içerik üretim ve platforma eklenme hızının incelenmesi.
- **Kitle ve Tür Hedeflemesi:** Yaş derecelendirmeleri (Rating) ve en popüler içerik türlerinin (Genre) analizi.
- **İnteraktif Dashboard:** Plotly kullanılarak hazırlanan 4 panelli dinamik görselleştirme paneli.
- **Otomatik Raporlama:** Terminal üzerinden okunabilir, yöneticiler için "İş Zekası Özeti" çıktısı.

##  Kullanılan Teknolojiler

- **Dil:** Python 3.x
- **Veri İşleme:** Pandas, NumPy
- **Görselleştirme:** Plotly, Matplotlib, Seaborn

## 📂 Dosya Yapısı

- **`data/`**
  - `Dataset (1).csv` : İşlenecek orijinal ham veri seti.
  - `cleaned_dataset.csv` : Kod çalıştıktan sonra oluşturulan temizlenmiş veri seti.
- **`notebook/`**
  - `netflixdataanalysis.ipynb` : Tüm veri temizleme, analiz ve interaktif dashboard işlemlerini barındıran ana Jupyter Notebook dosyası.
- `requirements.txt` : Projenin çalışması için gereken kütüphanelerin listesi.
- `README.md` : Proje hakkında genel bilgileri içeren bu dosya.

## ⚙️ Kurulum

1. Bu projeyi bilgisayarınıza indirin.
2. Terminal (veya Komut İstemi) açarak proje klasörüne gidin.
3. Gerekli kütüphaneleri tek seferde kurmak için aşağıdaki komutu çalıştırın:

```bash
pip install -r requirements.txt
