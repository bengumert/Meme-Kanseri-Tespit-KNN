# Meme Kanseri Tespiti - K-En Yakın Komşu (KNN)

Bu proje, makine öğrenimi algoritmalarından K-En Yakın Komşu (KNN) sınıflandırıcısını kullanarak Wisconsin Meme Kanseri veri setindeki tümörlerin iyi huylu (benign) veya kötü huylu (malignant) olup olmadığını tahmin etmeyi amaçlamaktadır. Projede veri setinin keşfi, modelin eğitimi, performans değerlendirmesi ve hiperparametre ayarları (özellikle `k` değeri) detaylı olarak incelenmiştir.

## İçerik

Bu depo aşağıdaki Jupyter Notebook dosyasını içermektedir:

* **`mo.ipynb`**: Bu not defteri, "Wisconsin Meme Kanseri" veri setinin yüklenmesi, keşfedilmesi, eğitim ve test setlerine ayrılması, K-En Yakın Komşu (KNN) modelinin uygulanması, modelin test verileri üzerinde performansının değerlendirilmesi ve en uygun `k` değerini bulmak için hiperparametre ayarlaması (hyperparameter tuning) adımlarını kapsamlı bir şekilde göstermektedir. Doğruluk (Accuracy) metrikleri kullanılmıştır.

## Özellikler

* Wisconsin Meme Kanseri veri setinin analizi.
* KNN (K-Nearest Neighbors) sınıflandırma algoritmasının uygulanması.
* Modelin eğitim ve test verileri üzerinde performansı.
* Farklı `k` değerleri için model doğruluklarının karşılaştırılması.
* Scikit-learn kütüphanesinin kullanımı.


## Kullanılan Teknolojiler

* **Python**
* **Pandas**: Veri yükleme ve manipülasyonu için.
* **NumPy**: Sayısal işlemler için.
* **Scikit-learn**: KNN modeli, veri seti yükleme (`load_breast_cancer`) ve model değerlendirme metrikleri için.
* **Matplotlib**: Sonuçların görselleştirilmesi için.
