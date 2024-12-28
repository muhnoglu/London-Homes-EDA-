
![indir](https://github.com/user-attachments/assets/8d0e6144-5caf-40c1-bc2d-efa69825ade1)

# London-Homes-EDA-
# Emlak Verileri Üzerine Analiz Sonuçları

Bu rapor, verilen emlak verileri setine dayanarak hazırlanmıştır. Analiz, emlak fiyatları, bina kalitesi, dış özellikler ve mahalle popülerliği gibi konulara odaklanmaktadır.

## Analiz Sonuçları

### 1. Metrekare Başına Fiyat (Price per Square Meter)
Metrekare başına fiyat, mülklerin değerini kıyaslamak için kullanılan önemli bir metriktir.

| **Mülk Adı**         | **Fiyat (GBP)** | **Metrekare Başına Fiyat** |
|----------------------|----------------|---------------------------|
| 78 Regent Street     | £12,800        | £12,800                   |
| 198 Oxford Street    | £12,000        | £12,000                   |

Daha yüksek fiyatlar genellikle bina kalitesi, lokasyon popülerliği veya lüks göstergelerle ilişkilidir.

### 2. Lüks Göstergesi (Luxury Indicator)
Lüks özelliklerin bir göstergesi olarak bu değişken, yüksek değere sahip mülklerin tespiti için önemlidir.

| **Mülk Adı**         | **Lüks Göstergesi** |
|----------------------|---------------------|
| 78 Regent Street     | 1 (Lüks)            |
| 198 Oxford Street    | 0 (Lüks değil)      |

### 3. Yenileme Yaşı (Renovation Age)
Binaların yenileme yaşları, modernlik ve değer potansiyeli açısından kritik bir rol oynar.

| **Mülk Adı**         | **Yenileme Yaşı**  |
|----------------------|-------------------|
| 78 Regent Street     | 72 yıl önce        |
| 198 Oxford Street    | Bilgi yok         |

### 4. Bahçe ve Garaj Endeksi (Garden and Garage Index)
Bahçe ve garaj gibi dış özelliklerin varlığı mülk değerini artırabilir.

| **Mülk Adı**         | **Bahçe ve Garaj** |
|----------------------|--------------------|
| 78 Regent Street     | 0 (Yok)            |
| 198 Oxford Street    | 1 (Bahçe var)      |

### 5. Bina Kalite Puanı (Building Quality Score)
Bu puan, kullanılan malzeme kalitesi ve yapısal durum gibi kriterlere dayanır.

| **Mülk Adı**         | **Bina Kalite Puanı** |
|----------------------|-----------------------|
| 78 Regent Street     | 4                     |
| 198 Oxford Street    | 1                     |

### 6. Mülk Yaşı Kategorisi (Property Age Category)
Mülklerin yaşı, kategori olarak değerlendirilmiştir:
- **Eski (Old)**: 78 Regent Street
- **Orta Yaşta (Moderate)**: 198 Oxford Street

### 7. Oda/Banyo Oranı (Room to Bathroom Ratio)
Daha fazla banyo genellikle lüks bir gösterge olarak kabul edilir.

| **Mülk Adı**         | **Oda/Banyo Oranı** |
|----------------------|---------------------|
| 78 Regent Street     | 0.67                |
| 198 Oxford Street    | 2.0                 |

### 8. Dış Özellikler Endeksi (Outdoor Feature Index)
Dış özellikler (bahçe, balkon gibi) bu endeksle değerlendirilmiştir.

| **Mülk Adı**         | **Dış Özellikler Endeksi** |
|----------------------|---------------------------|
| 78 Regent Street     | 3.0                       |
| 198 Oxford Street    | 3.0                       |

### 9. Mahalle Popülerlik Skoru (Neighborhood Popularity Score)
Bu skor, mahallelerin popülerlik ve prestij seviyesini gösterir.

| **Mülk Adı**         | **Mahalle Popülerlik Skoru** |
|----------------------|-----------------------------|
| 78 Regent Street     | 1.96 milyon puan            |
| 198 Oxford Street    | 2.28 milyon puan            |

---

## Sonuç ve Öneriler

- **78 Regent Street**: Lüks mülk kategorisinde yer almakta ve daha yüksek fiyatlarla öne çıkmaktadır. Ancak, modernlik ve yenileme yaşı eksiklikleri mülk değerini olumsuz etkileyebilir.
- **198 Oxford Street**: Orta düzey bir mahallede bulunmasına rağmen uygun fiyatıyla alıcılar için cazip bir seçenek olabilir.

### Gelecekteki Yatırım Önerileri:
- **Mahalle Popülerliği**: Mahallelerin prestij seviyesi, mülk değerinde kritik bir rol oynamaktadır.
- **Bina Kalitesi ve Modernlik**: Yenileme ve yapısal kalite, yatırım kararlarında öncelikli olmalıdır.

