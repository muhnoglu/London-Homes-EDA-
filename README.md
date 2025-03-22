


https://github.com/user-attachments/assets/1d224677-b678-4d60-9a27-84b667975865


![indir](https://github.com/user-attachments/assets/8d0e6144-5caf-40c1-bc2d-efa69825ade1)
# Ev Fiyat Tahmin Modeli ve Dinamik Dashboard

Bu projede, **Londra Evleri** veri seti üzerinde, ev fiyatlarını tahmin etmek amacıyla **Doğrusal Regresyon (Linear Regression)** modeli geliştirildi. Modelleme süreci, **keşifsel veri analizi (EDA), veri manipülasyonu, özellik mühendisliği, modelleme** ve **sonuçların görselleştirilmesi** adımlarını içermektedir. Ayrıca, **dinamik bir Power BI dashboard** tasarımı yapılmış ve kullanıcıların ev özelliklerine göre fiyat analizi yapabilmesi için etkileşimli bir platform oluşturulmuştur.

## 📌 İçerik
- [Keşifsel Veri Analizi (EDA)](#keşifsel-veri-analizi-eda)
- [Özellik Mühendisliği](#özellik-mühendisliği)
- [Modelleme (Doğrusal Regresyon)](#modelleme-doğrusal-regresyon)
- [Model Sonuçları](#model-sonuçları)
- [Dinamik Dashboard](#dinamik-dashboard)
- [Nasıl Kullanılır](#nasıl-kullanılır)
- [Yazar](#yazar)

---
## 🔍 Keşifsel Veri Analizi (EDA)
Keşifsel veri analizi adımında, **Londra Evleri** veri seti üzerinde kapsamlı bir inceleme yapılmıştır. Ev fiyatları ile ilgili önemli değişkenlerin (**Luxury Indicator, Square Meters, Price per Square Meter**) dağılımları ve korelasyonları analiz edilmiştir.

### Bu süreçte gerçekleştirilen adımlar:
✅ Verinin genel yapısı ve özet istatistikleri incelendi.
✅ Eksik ve aykırı değerler tespit edilip temizlendi.
✅ Korelasyon matrisleri ve dağılım grafikleri ile fiyatla ilişkili değişkenler belirlendi.
✅ Ev fiyatlarının **konum, büyüklük ve diğer özelliklere** göre görselleştirmeleri yapıldı.

Bu adım sayesinde, ev fiyatlarını etkileyen önemli faktörler hakkında derinlemesine bilgi edinilmiştir.

---
## 🏗️ Özellik Mühendisliği
Bu projede, özellikle **Luxury Indicator (Lüks Özellikler)** gibi yeni özellikler türetilmiştir. **Luxury Indicator**, evin lüks olup olmadığını belirleyen bir faktör olarak modelde kullanılmıştır. Ayrıca, **metrekare başına fiyat analizi** gibi işlevsel değişkenler oluşturulmuş ve modele dahil edilmiştir.

🔹 **Özellik mühendisliği sayesinde modelin doğruluğu artırılmıştır ve ev fiyatlarını tahmin etmek için en anlamlı değişkenler seçilmiştir.**

---
## 📈 Modelleme (Doğrusal Regresyon)
Modelleme adımında, **Doğrusal Regresyon (Linear Regression)** algoritması kullanılmıştır. **Modelin amacı**, ev fiyatlarını tahmin etmek ve belirli özelliklere dayalı olarak fiyat analizleri yapmaktır.

📌 **Eğitim ve test setlerine** ayrılan veriler üzerinde model eğitilmiş ve çeşitli değerlendirme metrikleri kullanılarak performansı ölçülmüştür. Ayrıca, **çapraz doğrulama (cross-validation)** ile modelin genellenebilirliği değerlendirilmiştir.

---
## 📊 Model Sonuçları
| Metrik | Değer |
|--------|------|
| **Train MSE** | 0.1188 |
| **Test MSE** | 0.1418 |
| **Train R²** | 0.8804 |
| **Test R²** | 0.8617 |
| **Cross-Validation Mean MSE** | 0.1204 |

✅ **Bu sonuçlar, modelin doğru tahminlerde bulunma kapasitesinin yüksek olduğunu ve ev fiyatlarını başarılı bir şekilde tahmin ettiğini göstermektedir.**

---
## 📊 Dinamik Dashboard
Projede, **Power BI** kullanılarak **dinamik bir dashboard** tasarlanmıştır. Bu dashboard, kullanıcıların farklı ev özelliklerine göre (**konum, fiyat, metrekare, lüks özellikler, vb.**) filtreler uygulayarak **ev fiyat analizleri** yapabilmesini sağlar.

### 📌 Dashboard Özellikleri:
✅ **Fiyat analizi:** Evlerin fiyatlarına göre farklı filtreler uygulanabilir.
✅ **Konum analizi:** Evin bulunduğu mahalleye göre fiyat analizleri yapılabilir.
✅ **Ev özellikleri:** Evlerin büyüklüğü, oda sayısı, lüks durumu gibi özelliklere göre filtreleme yapılabilir.

**Bu dashboard, kullanıcı dostu bir arayüze sahip olup, ev fiyatlarını dinamik olarak analiz etmeyi mümkün kılar.**

---
## 🚀 Nasıl Kullanılır
1️⃣ **Veri Seti:** Londra Evleri veri setini kullanarak modeli geliştirin.
2️⃣ **Modeli Eğitme:** Veriyi **eğitim ve test setlerine** ayırarak **Doğrusal Regresyon modelini** eğitin.
3️⃣ **Dashboard:** Power BI ile oluşturulan dashboard'u kullanarak **ev fiyatlarına dair dinamik analizler yapın.**

---
## 👨‍💻 Yazar
**Proje:** Muhammed Hanoğlu tarafından geliştirilmiştir.

📌 **GitHub:** [GitHub Profilim](https://github.com/muhammedhanoglu)
📌 **LinkedIn:** [LinkedIn Profilim](https://www.linkedin.com/in/muhammedhanoglu)

📌 **Bu projeyi beğendiyseniz, yıldız vermeyi unutmayın! ⭐**

---
