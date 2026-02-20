# 📊 Öğrenci Sınav Performansı Analizi

Bu proje, Kaggle üzerindeki popüler **"Students Performance in Exams"** veri setini kullanarak öğrencilerin akademik başarılarını veri bilimi teknikleriyle incelemektedir. Özellikle matematik notlarının dağılımını ve istatistiksel özetini **Box Plot (Kutu Grafiği)** yöntemiyle görselleştirmeyi hedefler.

## 🚀 Proje Hakkında

Veri görselleştirme, karmaşık veri setlerindeki eğilimleri ve aykırı değerleri (outliers) anlamak için kritik bir araçtır. Bu çalışmada:
- Veri setindeki matematik notlarının genel dağılımı incelenmiştir.
- **Matplotlib** ile temel görselleştirme yapılmıştır.
- **Plotly Express** kullanılarak etkileşimli, detaylı bilgi sunan dinamik bir grafik oluşturulmuştur.

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

Proje, modern Python veri bilimi ekosistemi üzerine inşa edilmiştir:

| Kütüphane | Kullanım Amacı |
| :--- | :--- |
| **Pandas** | Veri setinin okunması, temizlenmesi ve analize hazırlanması. |
| **Matplotlib** | Statik veri görselleştirme ve grafik düzenlemeleri. |
| **Plotly** | Kullanıcı etkileşimli, web tabanlı dinamik grafikler. |
| **Jupyter Notebook** | Kodun adım adım çalıştırılması ve sonuçların anlık takibi. |

## 📈 Veri Seti Detayları

Kullanılan veri seti şu özellikleri içermektedir:
- **Demografik Bilgiler:** Cinsiyet, etnik köken, ebeveyn eğitim seviyesi.
- **Sınav Notları:** Matematik, okuma ve yazma skorları.
- **Hazırlık Durumu:** Sınav hazırlık kursunun tamamlanıp tamamlanmadığı.

> **Not:** Analiz kapsamında özellikle matematik notlarının varyansı ve çeyreklik (quartile) değerleri üzerine yoğunlaşılmıştır.

## 💻 Kurulum ve Çalıştırma

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. **Depoyu Klonlayın:**
   ```bash
   git clone https://github.com/zeycanaslan/student-performance-analysis.git
   cd student-performance-analysis
   ```

2. **Gerekli Kütüphaneleri Yükleyin:**
   ```bash
   pip install pandas matplotlib plotly notebook
   ```

3. **Notebook'u Başlatın:**
   ```bash
   jupyter notebook box-chart.ipynb
   ```

---
📫 **İletişim:** Herhangi bir soru veya geri bildirim için profilim üzerinden bana ulaşabilirsiniz.

*Bu çalışma Zeycan Aslan tarafından bir veri analizi pratiği olarak geliştirilmiştir.*
