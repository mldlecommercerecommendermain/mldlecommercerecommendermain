# 🧠 Makine Öğrenmesi ve Derin Öğrenme Yöntemleri ile E-Ticaret Sistemlerinde: Ürün Önerisi Amaçlı En İyi Model Seçimi ve Performans Değerlendirmesi

Bu proje, **Makine Öğrenmesi ve Derin Öğrenme Yöntemleri ile E-Ticaret Sistemlerinde: Ürün Önerisi Amaçlı En İyi Model Seçimi ve Performans Değerlendirmesi** başlıklı yüksek lisans tezi kapsamında geliştirilmiştir.

---

## 🌐 Proje Amacı

E-ticaret platformlarında kullanıcı deneyimini artırmak amacıyla farklı öneri algoritmalarının performansları karşılaştırılmış ve en uygun öneri modelini belirlemek hedeflenmiştir. Bu kapsamda yedi farklı öneri algoritması, çeşitli performans metrikleri üzerinden test edilmiştir.

---

## 🧠 Kullanılan Algoritmalar

| Durum | Algoritma                                      |
|-------|-----------------------------------------------|
| ✅    | Random-based Recommendation                    |
| ✅    | Popularity-based Recommendation                |
| ✅    | Content-Based Filtering (CBF)                  |
| ✅    | Item-Based Collaborative Filtering (IBCF)      |
| ✅    | Hybrid Model (CBF + IBCF)                      |
| ✅    | Recurrent Neural Networks (RNN)                |
| ✅    | Random Forest                                  |

---

## 📊 Performans Metrikleri

Bu çalışmada algoritmalar şu ölçütlere göre değerlendirilmiştir:

- **MAP** (Mean Average Precision)  
- **CC** (Catalog Coverage)  
- **MNS** (Mean Novelty Score)  
- **MDS** (Mean Diversity Score)  
- **MPS** (Mean Personalization Score)

Bu metrikler doğruluk, yenilikçilik, çeşitlilik ve kişiselleştirme yönünden algoritmaları değerlendirmek için kullanılmıştır.

---

## 📁 Dosya Yapısı

| Dosya Adı                     | Açıklama |
|------------------------------|----------|
| `veri_seti_hazirlama.ipynb`  | Veri setinin yüklenmesi, temizlenmesi ve işlenmesi |
| `random_based.ipynb`         | Rastgele öneri algoritması |
| `popularity_based.ipynb`     | Popülerliğe dayalı öneri algoritması |
| `content_based.ipynb`        | İçerik tabanlı öneri algoritması |
| `item_based.ipynb`           | Item-Based Collaborative Filtering |
| `hybrid.ipynb`               | Hibrit öneri algoritması (CBF + IBCF) |
| `rnn.ipynb`                  | RNN (Recurrent Neural Network) tabanlı öneri |
| `random_forest.ipynb`        | Random Forest algoritmasına dayalı öneri |
| `sonuclari_gosterme.ipynb`   | Tüm algoritmaların sonuçlarını tablolar ve grafiklerle gösterir |
| `kullanici_etkilesim_veri.csv` | Kullanıcıların ürünlerle olan etkileşimleri |
| `kullanici_satin_alma_veri.csv` | Kullanıcıların satın alma geçmişi |
| `urun_ozellikleri.csv`       | Ürünlere ait özellikler ve kategoriler |

---

## 🚀 Çalıştırma Sırası

Projeyi adım adım çalıştırmak için aşağıdaki sırayı takip edin:

### 1️⃣ Veri Hazırlama  
📂 `veri_seti_hazirlama.ipynb` dosyasını çalıştırın.  
Bu adımda veri setleri okunur, temizlenir ve modellemeye uygun hale getirilir.

### 2️⃣ Algoritmaları Çalıştırma  
Aşağıdaki notebook dosyalarını **tek tek çalıştırarak** her algoritmanın sonuçlarını üretin:

- `random_based.ipynb`
- `popularity_based.ipynb`
- `content_based.ipynb`
- `item_based.ipynb`
- `hybrid.ipynb`
- `rnn.ipynb`
- `random_forest.ipynb`

### 3️⃣ Sonuçları Gösterme  
📈 `sonuclari_gosterme.ipynb` dosyasını çalıştırarak:
- Tüm algoritmaların **MAP, CC, MNS, MDS, MPS** metriklerine göre karşılaştırıldığı tabloyu görün.
- Her metrik için oluşturulan grafiklerle karşılaştırma yapın.

---

## 📌 Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki Python kütüphaneleri gereklidir:

```bash
pandas
numpy
scikit-learn
matplotlib
pickle
