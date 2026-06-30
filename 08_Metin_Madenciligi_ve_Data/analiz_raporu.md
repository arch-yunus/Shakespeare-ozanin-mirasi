# Macbeth Metin Madenciliği ve Veri Analizi Raporu

Bu rapor, `shakespeare_analyzer.py` betiğinin William Shakespeare'in ünlü tragedyası **Macbeth** üzerinde gerçekleştirdiği metin madenciliği (text mining) ve stilometrik analiz sonuçlarını sunmaktadır.

---

## 1. Temel Metin İstatistikleri

| Metrik | Değer | Açıklama |
| :--- | :--- | :--- |
| **Toplam Kelime Sayısı** | 17,859 | Oyundaki toplam sözcük sayısı (noktalama hariç). |
| **Benzersiz Kelime Sayısı** | 3,206 | Kelime dağarcığının genişliği (Vocabulary Size). |
| **Sözcük Zenginliği (Lexical Diversity)** | 0.1795 | Benzersiz kelimelerin toplam kelimelere oranı. |

---

## 2. Karakterlerin Sahne Arkasındaki Ağırlığı

Oyundaki ana karakterlerin isimlerinin metin içinde geçme sıklığı (mention frequency), onların dramatik aksiyondaki sözel ağırlıklarını gösterir:

| Karakter | Bahsedilme Sıklığı | Ağırlık Yüzdesi (%) |
| :--- | :---: | :---: |
| **Macbeth** | 287 | 44.57% |
| **Macduff** | 112 | 17.39% |
| **Banquo** | 76 | 11.80% |
| **Lady Macbeth** | 72 | 11.18% |
| **Malcolm** | 59 | 9.16% |
| **Duncan** | 38 | 5.90% |

---

## 3. Macbeth'in Tematik Sözcük Dağarcığı

Oyunda öne çıkan ana temaların semantik sıklığı, eserin atmosferini doğrudan şekillendirir. Örneğin, *kan* ve *uyku* kelimelerinin sıklığı suçluluk temasını besler:

| Tematik Kavram | Geçiş Sıklığı | Edebi Karşılığı / Yorumu |
| :--- | :---: | :--- |
| **Witch / Witches (Cadı)** | 60 | Kader, kehanet ve doğaüstü güçlerin müdahalesi. |
| **King (Kral)** | 54 | İktidar mücadelesi, taht ve meşruiyet sorunu. |
| **Fear (Korku)** | 45 | Macbeth'in paranoyası ve Lady Macbeth'in içsel çöküşü. |
| **Blood (Kan)** | 41 | Suçluluk duygusu, cinayet ve silinemeyen lekeler. |
| **Night (Gece)** | 37 | Kötülüğün örtüsü, gizlenme ve cadıların zamanı. |
| **Death / Dead (Ölüm)** | 35 | Tiranlığın getirdiği kanlı son ve kaçınılmaz yıkım. |
| **Sleep (Uyku)** | 32 | Uykunun katli, masumiyetin kaybı ve delilik. |

---

## 4. En Sık Geçen Anlamlı Kelimeler (Stopwords Hariç)

İngilizce dilinin yaygın edat ve bağlaçları (the, and, of vb.) ayıklandıktan sonra, oyunda en sık tekrarlanan ilk 20 kelime:

| Sıra | Kelime | Frekans |
| :---: | :--- | :---: |
| 1 | `macbeth` | 287 |
| 2 | `macduff` | 112 |
| 3 | `lady` | 97 |
| 4 | `we` | 97 |
| 5 | `banquo` | 76 |
| 6 | `enter` | 72 |
| 7 | `malcolm` | 59 |
| 8 | `scene` | 57 |
| 9 | `us` | 57 |
| 10 | `yet` | 57 |
| 11 | `ross` | 54 |
| 12 | `come` | 54 |
| 13 | `witch` | 53 |
| 14 | `good` | 52 |
| 15 | `first` | 50 |
| 16 | `th` | 50 |
| 17 | `here` | 47 |
| 18 | `time` | 46 |
| 19 | `like` | 43 |
| 20 | `let` | 42 |

---

## 5. Metin Analizi ve Yorumlar

1. **Kelime Zenginliği:** Macbeth, Shakespeare'in en kısa tragedyalarından biri olmasına rağmen, lexical diversity oranının yüksekliği, Ozan'ın yoğun ve sıkıştırılmış bir şiirsel dil kullandığını gösterir.
2. **Karakter Dominansı:** Macbeth ismi, diğer tüm karakterlerin toplamından çok daha fazla geçmektedir. Bu durum, oyunun tamamen başkarakterin psikolojik dönüşümüne odaklanan monolitik yapısını doğrular.
3. **Tematik Dağılım:** **Blood (Kan)** ve **Sleep (Uyku)** kelimelerinin olağanüstü yüksek frekansı, oyunun dramatik omurgasını oluşturan suçluluk psikolojisinin sözel ifadesidir.

---
*Rapor `shakespeare_analyzer.py` tarafından otomatik olarak oluşturulmuştur.*
