# Hızlı Kazanç Algısı ve Emek İlişkisi: İstatistiksel Bir Analiz ve Modelleme

Şans oyunlarına yönelik "hızlı kazanç" algısı ile emeğe duyulan inanç arasındaki ilişkiyi inceleyen anket temelli bir veri bilimi araştırması. 152 katılımcıdan toplanan veri üzerinde tanımlayıcı istatistiklerden aracılık ve moderasyon analizine uzanan bir modelleme süreci yürütülmüştür.

**Durum:** ✅ Tamamlandı — Veri Bilimine Giriş dersi final projesi.

## Araştırma Akışı

Analiz `sans_oyunlariv1.ipynb` içinde şu sırayla ilerler:

1. **Veri hazırlığı ve ön işleme** — anket verisinin temizlenmesi ve kodlanması
2. **Değişken skorlarının oluşturulması ve güvenirlik analizi** — ölçek skorları, Cronbach alfa
3. **Veri kalitesi ve varsayım kontrolleri**
4. **Tanımlayıcı istatistikler** — demografi ve tercih dağılımları
5. **Ölçek ortalamaları ve merkezi eğilim analizi**
6. **Normallik testleri** — Shapiro-Wilk
7. **Karşılaştırmalı analizler** — gruplar arası farklar
8. **Korelasyon analizi**
9. **Çoklu doğrusal regresyon**
10. **Modelin görselleştirilmesi** ve hipotez testleri
11. **Aracılık (mediation) analizi**
12. **Moderasyon analizi**

## Dosyalar

| Dosya | Açıklama |
|---|---|
| `VeriBilimine Giriş Final/sans_oyunlariv1.ipynb` | Tüm analizi içeren Jupyter defteri |
| `VeriBilimine Giriş Final/Şans Oyunları ve Emek İnancı Araştırması Anket Formu(1-152).xlsx` | Ham anket verisi (152 yanıt) |
| `Hızlı Kazanç Algısı ve Emek İlişkisi ... .pdf` | Nihai araştırma raporu |
| `VERİ BİLİMİNE GİRİŞ ARAŞTIRMA PROJESİ.docx` | Proje dokümanı |

## Kullanılan Kütüphaneler

`pandas` · `numpy` · `scipy` · `statsmodels` · `pingouin` · `matplotlib` · `seaborn`

## Çalıştırma

```bash
pip install pandas numpy scipy statsmodels pingouin matplotlib seaborn openpyxl jupyter
jupyter notebook "VeriBilimine Giriş Final/sans_oyunlariv1.ipynb"
```

## Not

Anket verisi anonimdir; katılımcıları tanımlayan kişisel bilgi içermez.
