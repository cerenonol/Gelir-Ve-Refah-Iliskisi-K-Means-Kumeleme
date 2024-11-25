# Kişi Başına Gelir ve Refah Düzeyleri ile Ülkelerin Çalışma Saatleri Arasındaki İlişki: K-Means Kümeleme Analizi

Bu proje, ülkelerin **haftalık çalışma saatleri** ve **refah düzeyleri** gibi ekonomik verilerle, **kişi başına gelir** ilişkisini incelemeyi ve bu veriler üzerinden **K-Means kümeleme algoritması** kullanarak ülkeleri gruplamayı amaçlayan bir makine öğrenmesi projesidir.

## Proje Amacı

Projenin amacı, ülkeler arasındaki **ekonomik** farklılıkları anlamak için, ülkelerin **haftalık çalışma saatleri**, **refah düzeyleri** ve **kişi başına gelir** verilerini analiz etmektir. Ayrıca, bu verileri kullanarak ülkeleri benzer ekonomik özelliklere göre gruplamak için **K-Means kümeleme** algoritması uygulanmıştır.

- **Lineer Regresyon Modeli**: Bu model, ülkelerin haftalık çalışma saatleri ve refah düzeylerine dayalı olarak kişi başına gelir verilerini incelemek amacıyla kullanılmıştır.
- **K-Means Kümeleme Modeli**: Ülkeleri benzer özelliklerine göre kümelere ayırmak için K-Means algoritması kullanılmıştır. Bu sayede, benzer ekonomik özelliklere sahip ülkeler bir arada gruplanmıştır.

## Kullanılan Teknolojiler

Bu projede aşağıdaki teknolojiler ve kütüphaneler kullanılmıştır:
- **Python** (Programlama Dili)
- **Pandas** (Veri Manipülasyonu)
- **NumPy** (Sayısal Hesaplamalar)
- **Matplotlib & Seaborn** (Veri Görselleştirme)
- **scikit-learn** (Makine Öğrenmesi)
- **Jupyter Notebook / Google Colab** (Çalışma Ortamı)

## Veri Seti

Veri seti, farklı ülkelerin haftalık ortalama çalışma saatleri, refah düzeyleri ve kişi başına gelir verilerini içermektedir. Bu veriler kullanılarak, ülkeler arasındaki ekonomik ilişkiler ve kümeler analiz edilmiştir.

## Proje Adımları

1. **Veri Hazırlığı**:
   - Ülkelerin haftalık çalışma saatleri, refah düzeyleri ve kişi başına gelir verileri oluşturulmuştur.
   
2. **Lineer Regresyon Modeli**:
   - Haftalık çalışma saatleri ve refah düzeylerine dayalı olarak kişi başına gelir incelenmiştir. 
   - Modelin başarısı **ortalama kare hata (MSE)** ile değerlendirilmiştir.
   
3. **K-Means Kümeleme Modeli**:
   - Ülkeleri, çalışma saatleri ve refah düzeylerine göre gruplamak için K-Means algoritması kullanılmıştır.
   - Kümeleme başarısı **Silhouette Skoru** ile değerlendirilmiştir.

4. **Model Değerlendirmesi**:
   - **Lineer Regresyon** modelinin doğruluğu ve **K-Means Kümeleme** modelinin başarısı değerlendirilmiştir.
   - Görselleştirme teknikleriyle, ülkelerin ekonomik özellikleri arasında bir ilişki kurulmuştur.

## Kullanım Talimatları

Projeyi kendi bilgisayarınızda çalıştırabilmek için aşağıdaki adımları takip edebilirsiniz:

### Gerekli Kütüphaneler

Projeyi çalıştırabilmek için aşağıdaki Python kütüphanelerine ihtiyacınız olacaktır. Bu kütüphaneleri yüklemek için şu komutu kullanabilirsiniz:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
