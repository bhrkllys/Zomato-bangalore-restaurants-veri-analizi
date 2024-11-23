# Zomato-Bangalore Restoran Veri Seti Analizi

**Açıklama:**  
Bu proje, restoranlara ait çeşitli veriler kullanılarak analiz yapılmasını ve lokasyon, mutfak türleri gibi özelliklerin incelenmesini amaçlamaktadır. 
Kaggle ortamında yürütülen bu çalışma, eksik verilerin gözlenmesi , doldurulması ,silinmesi , analiz ve görselleştirme adımlarını içermektedir.

---

## Kullanılan Veri Seti
/kaggle/input/zomato-bangalore-restaurants/zomato.csv

### Özellikler (Sütunlar):

| Sütun Adı                        | Açıklama                                                                 |
|----------------------------------|-------------------------------------------------------------------------|
| **url**                           | Tanımlayıcı bir kod sütunu, detaylı bilgi içermiyor.                     |
| **address**                      | Restoranın adres bilgisi.                                                |
| **name**                         | Restoranın adı.                                                          |
| **online_order**                 | Online sipariş seçeneğinin olup olmadığını belirtir (Evet/Hayır).        |
| **book_table**                   | Masa rezervasyonu yapılabilir mi (Evet/Hayır).                           |
| **rate**                         | Restoranın kullanıcı puanı.                                              |
| **votes**                        | Restorana verilen toplam oy sayısı.                                      |
| **phone**                        | Restorana ait telefon numarası.                                          |
| **location**                     | Restoranın bulunduğu lokasyon.                                           |
| **rest_type**                    | Restoranın türü (Kafe, Lokanta, Fast Food, vb.)                          |
| **dish_liked**                   | Restoranın öne çıkan yemekleri                                           |
| **cuisines**                     | Restoranın sunduğu mutfak türleri.                                       |
| **approx_cost(for two people)**  | İki kişi için ortalama ödeme tutarı.                                     |
| **reviews_list**                 | Restoran hakkında yapılan yorumlar.                                      |
| **menu_item**                    | Restoranın menüde sunduğu yemekler.                                      |
| **listed_in(type)**              | Restoranın listelendiği kategori (Yemek, Kafe, vb.).                     |
| **listed_in(city)**              | Restoranın bulunduğu şehir.                                              |

---

## Proje Adımları

### 1. **Veri İncelemesi ve Temizleme**
- Eksik veriler belirlendi Poje de istenen eksik veri ekleme adımı %1 oranında tercih edilerek veriye rastgele bir şekilde eklendi.
- İLave edilen eksik veriler dahilinde veri kontrol edildi.
- Eksik verilerin silinmesi ve doldurulması işlerimleri yapıldı(Sayısal ve kategorik değişkenlerin doldurulması )
  -Matplotlib,seaborn kütüphaneleri görselleştirme işleri yapıldı.

### 2. **Analizler**
- **Lokasyon Bazlı Analiz:** Restoranların bulunduğu lokasyonlara göre toplam ödemeler ve popüler mutfak türleri incelendi.
- **Mutfak Türü Analizi:** En popüler mutfak türleri ve bu türlerin lokasyonlara göre dağılımı görselleştirildi.
- **Puanlama ve Oy Analizi:** Restoranların puan ve oy sayılarının dağılımı değerlendirildi.
  
---

## Kullanılan Araçlar

- **Python Kütüphaneleri:**
  - `pandas` — Veri manipülasyonu.
  - `numpy` — Sayısal işlemler.
  - `matplotlib` ve `seaborn` — Veri görselleştirme.

- **Çalıştırma Ortamı:** Kaggle Notebook.

---

## Çıktılar ve Sonuçlar

- Eksik veriler, analizin doğruluğunu artırmak için filtrelendi.
- Lokasyon bazlı ödeme dağılımı ve mutfak türleri hakkında anlamlı sonuçlar elde edildi.
- Puanlama ve oy dağılımları restoranların genel performansı hakkında bilgi sağladı.

---

## İleride Yapılabilecekler

- **Aykırı Değer Analizi:** 
  - Özellikle **approx_cost(for two people)** sütunu üzerinde aykırı değerlerin tespiti.
- **Makine Öğrenimi Uygulamaları:** 
  - Restoran puanlamalarını ve ödeme tahminlerini öngörmek için regresyon veya sınıflandırma algoritmaları kullanılabilir.

---

## Proje Nasıl Çalıştırılır?

1. Kaggle'da bu projeyi açın. (https://www.kaggle.com/code/baharkolluya/global-ai-hub-veri-analizi-e-itimi/edit#4.-S%C3%BCrekli-De%C4%9Fi%C5%9Fken-Analizi)
2. Notebook'u kendi hesabınıza kopyalayarak çalıştırın.
3. Verilen hücreleri sırasıyla çalıştırarak analizlerinizi inceleyin.

---

## Yazar

**Bahar Aslan**  
-https://github.com/bhrkllys 
-www.linkedin.com/in/bahar-aslan

---

Bu dosya, proje hakkında genel bir özet ve kullanım yönergeleri sunmaktadır. Geri bildirimlerinizi bekliyorum! 😊
