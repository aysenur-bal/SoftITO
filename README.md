# SoftITO Veri Analitiği Eğitimi Çalışmaları

SoftITO Veri Analitiği programı (320 saat) kapsamında hazırladığım ödev ve uygulama çalışmaları. Çalışmalar veri okuma ve temizlemeden keşifsel veri analizine, gruplama ve pivot tablolardan Power BI raporlamaya kadar uzanıyor.

**Araçlar:** Python · pandas · NumPy · Matplotlib · Seaborn · Power BI

> Program kapsamındaki proje çalışmam ayrı bir depoda yer alıyor: [İstanbul Baraj Doluluk Oranları ve İklim Faktörleri Analizi](https://github.com/aysenur-bal/Baraj-doluluk-oranlari-ist)

---

## İçerik

| Klasör | Çalışma | Öne çıkan teknikler |
|---|---|---|
| [`EDA`](EDA) | **Öğrenci sınav performansı: keşifsel veri analizi.** Veri setinin yapısı, eksik değerler, dağılımlar ve değişkenler arası ilişkiler incelendi. | `info`, `describe`, eksik değer analizi, sütun yeniden adlandırma, Seaborn görselleştirme |
| [`Pandas_25.10.2026`](Pandas_25.10.2026) | **İstanbul AVM satış verisi analizi.** Cinsiyet, yaş grubu, ödeme yöntemi ve ürün kategorisine göre harcamalar beş soru üzerinden incelendi. | `groupby`, `pivot_table`, yaş gruplama fonksiyonu, Matplotlib/Seaborn çubuk grafikler |
| [`Power_BI_31.10.2026`](Power_BI_31.10.2026) | **İstanbul satış verisi Power BI raporu.** Satış verisi ürün referans tablosuyla ilişkilendirilerek görselleştirildi. | Veri modeli (ilişkili tablolar), Power BI görselleri |
| [`Pandas_07.11.2026`](Pandas_07.11.2026) | **Öğrenci değerlendirme verisi.** Çok sayfalı bir Excel dosyasından sınav ve günlük değerlendirme puanları birleştirildi, normalize edildi ve ağırlıklı bir başarı ölçüsüyle en başarılı öğrenciler sıralandı. | `read_excel` (çoklu sayfa), min-max normalizasyon, ağırlıklı skor, birleştirme ve sıralama |
| [`Pandas_29.10.2026`](Pandas_29.10.2026) | **Pandas temel alıştırmaları.** Farklı formatlardaki veri setleriyle (CSV, TSV) okuma, inceleme, eksik değer ve Series işlemleri. | `read_csv` (ayırıcı, indeks sütunu), `isnull`, `value_counts`, `drop_duplicates` |

## Çalıştırma

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
jupyter notebook
```

Power BI dosyası (`.pbix`) için [Power BI Desktop](https://powerbi.microsoft.com/desktop/) gerekir.
