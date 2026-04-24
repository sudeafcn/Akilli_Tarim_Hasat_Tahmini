# 🌾 Akıllı Tarım: Hasat Verimi Analizi

Bu proje, **CRISP-DM** metodolojisi kullanılarak tarımsal verilerin analiz edilmesi ve makine öğrenmesi (Regresyon) modelleri ile hasat veriminin tahmin edilmesi amacıyla geliştirilmiştir. Proje kapsamında 15.000 satırlık veri seti üzerinde uçtan uca veri bilimi süreçleri uygulanmıştır.

## 📁 Proje Klasör Yapısı
Proje kapsamında aşağıdaki yapı kullanılmıştır

* **data/**: Projede kullanılan ham ve işlenmiş (temizlenmiş) veri setleri.
* **notebooks/**: Veri analizi, görselleştirme ve model eğitim adımlarını içeren `akıllı_tarım.ipynb` dosyası.
* **models/**: Eğitilmiş ve kaydedilmiş makine öğrenmesi model dosyaları (.pkl).
* **figures/**: Analiz sürecinde elde edilen grafik çıktıları ve korelasyon matrisleri.
* **README.md**: Projenin genel açıklaması ve kullanım rehberi.

## 🚀 Proje Adımları (CRISP-DM Akışı)
1. **İş Anlayışı:** Tarımsal değişkenlerin verim üzerindeki etkisini anlama.
2. **Veri Anlayışı:** Veri setinin yapısal incelenmesi ve Keşifçi Veri Analizi (EDA).
3. **Veri Hazırlama:** Eksik değerlerin doldurulması, aykırı değer (outlier) temizliği ve özellik mühendisliği.
4. **Modelleme:** Regresyon algoritmaları (Linear Regression, Random Forest vb.) ile tahminleme.
5. **Değerlendirme:** Modellerin hata metrikleri (RMSE, R2 vb.) üzerinden kıyaslanması.
6. **Dağıtım:** En iyi modelin kaydedilerek kullanıma hazır hale getirilmesi.

## 🛠️ Kullanılan Teknolojiler
* **Dil:** Python
* **Kütüphaneler:** Pandas, NumPy, Scikit-learn, Plotly, Matplotlib, Seaborn
* **Geliştirme Ortamı:** VS Code & Jupyter Notebook
* 
## 📊 Elde Edilen Sonuçlar 
	•	Hasat verimini etkileyen temel faktörler belirlendi
	•	Geliştirilen model ile başarılı tahminler elde edildi
	•	Veri analizi sayesinde anlamlı içgörüler çıkarıldı

## 📊 Öne Çıkan Bulgular
Analiz sonucunda, hasat verimi üzerinde en çok etki eden çevresel ve tarımsal faktörler belirlenmiştir. Geliştirilen model, verim tahminlemede yüksek başarı oranına ulaşmıştır.

## 💡 Projeden Kazanımlar 
	•	Veri temizleme ve ön işleme deneyimi
	•	Veri analizi ve yorumlama becerisi
	•	Makine öğrenmesi modelleme süreci
	•	Sonuçları iş değeri oluşturacak şekilde yorumlama
