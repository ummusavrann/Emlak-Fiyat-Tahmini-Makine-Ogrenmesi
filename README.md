# 🏠 Emlak Piyasası Analizi ve Konut Fiyatı Tahminleme

Bu proje, **İş Analitiği yandal programım** kapsamında aldığım **Veri Bilimi** dersi için bir **grup çalışması** olarak geliştirilmiştir. Projenin temel amacı, gerçek emlak verilerini kullanarak konut fiyatlarını etkileyen faktörleri belirlemek ve yüksek doğruluklu bir regresyon modeli oluşturmaktır.

## 🚀 Proje Metodolojisi ve Analiz
Proje süreci, istatistiksel varsayımların kontrolünden modelin dışa aktarılmasına kadar şu profesyonel aşamalardan oluşmaktadır:

* **Veri Stratejisi:** Modelin gerçek hayat performansını simüle etmek için 8. ay verileri eğitim, 9. ay verileri ise bağımsız test seti olarak ayrılmıştır.
* **Keşifsel Veri Analizi (EDA):** Konut fiyatları ile metrekare, oda sayısı ve lokasyon gibi değişkenler arasındaki korelasyonlar incelenmiş; aykırı değerler temizlenmiştir.
* **Model Yarıştırma:** Problem bir regresyon problemi olarak ele alınmış; Linear Regression, Decision Tree, KNN ve Random Forest Regressor modelleri performans metriklerine göre karşılaştırılmıştır.
* **Nihai Model:** Test verisi üzerinde **0.8787 R² skoru** ile en yüksek başarıyı gösteren **Random Forest** algoritması seçilmiştir.
* **Model Saklama (Deployment):** Eğitilen model, gerçek zamanlı tahminlerde kullanılmak üzere **pickle (.pkl)** formatında kaydedilmiştir.
  
## 🛠 Kullanılan Teknolojiler
* **Programlama:** Python
* **Veri Analizi:** Pandas, NumPy
* **Makine Öğrenmesi:** Scikit-learn
* **Görselleştirme:** Matplotlib, Seaborn
* **Model Saklama:** Pickle

## 👥 Katkıda Bulunanlar (Grup Çalışması)
* Ümmü SAVRAN 
* Ezgi ALTINTOP  
* Hatice EFLATUN 
* Yağmur IŞIK
