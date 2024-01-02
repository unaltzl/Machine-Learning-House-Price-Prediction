House Price Prediction
Bu proje, ev fiyatlarını tahmin etmek için çeşitli makine öğrenimi modellerinin kullanıldığı bir çalışmayı içermektedir.

Kullanılan Teknolojiler ve Kütüphaneler
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
LightGBM
XGBoost
CatBoost
Veri Seti
Proje, "house_price_prediction.csv" adlı bir veri seti üzerinde gerçekleştirilmiştir. Veri seti ev özellikleri ve fiyatlarını içermektedir.

Genel Resim
Proje başlangıcında, veri setinin genel yapısı ve temel istatistikler incelenmiştir. Ayrıca, aykırı değerler temizlenmiştir.

Kategorik Değişken Analizi
Projenin bu bölümünde kategorik değişkenler detaylı bir şekilde incelenmiş, sınıflar arasındaki dağılımlar ve hedef değişkenle olan ilişkiler gösterilmiştir.

Sayısal Değişken Analizi
Sayısal değişkenlerin dağılımları, istatistikleri ve hedef değişkenle olan ilişkileri bu bölümde analiz edilmiştir.

Hedef Değişken Analizi
Hedef değişken olan "SalePrice" üzerinde çeşitli analizler yapılmıştır, örneğin dağılımı, log dönüşümü, korelasyon analizi vb.

Korelasyon Analizi
Veri setindeki sayısal değişkenler arasındaki korelasyonlar ısı haritası ile görselleştirilmiştir.

Veri Ön İşleme İşlemleri
Veri ön işleme adımları, aykırı değer temizleme, eksik değer doldurma, nadir sınıfları birleştirme, yeni özelliklerin oluşturulması vb. adımları içermektedir.

Modelleme
Projede çeşitli makine öğrenimi modelleri kullanılarak ev fiyatları tahmin edilmiştir. Modeller arasında LightGBM, XGBoost, Random Forest vb. bulunmaktadır.

Model Hiperparametre Optimizasyonu
Modellerin performansını artırmak için hiperparametre optimizasyonu gerçekleştirilmiştir. Özellikle LightGBM için GridSearchCV kullanılarak en iyi parametre seti bulunmuştur.

Model Test ve Performans
Son olarak, en iyi model seçilip test edilmiş ve elde edilen sonuçlar raporlanmıştır. Projede elde edilen RMSE değeri 22,118'dir.
