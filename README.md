# DFABilisim

Makine Öğrenmesi ile Metin İşleme Proje Açıklaması:
Bu proje, Türkçe haber başlıklarını 7 farklı kategoride (Ekonomi, Siyaset, Yaşam, Teknoloji, Magazin, Sağlık, Spor) 
sınıflandırmak için geliştirilmiş bir makine öğrenmesi modelidir.

Öne Çıkan Özellikler:
%98.4 doğruluk oranına ulaşan Multinomial Naive Bayes modeli
Türkçe'ye özel metin ön işleme (TÜİK, THY gibi kısaltmaların özel işlenmesi)
TF-IDF vektörleştirme ile 3-gram desteği
Naive Bayes ve Lojistik Regresyon modellerinin karşılaştırmalı analizi

Veri Seti Bilgileri:
Toplam 4,200 haber başlığı (her kategori için 600 başlık)
Mynet ve Milliyet gibi Türk haber sitelerinden derlenmiştir
Verilerin %85'i eğitim, %15'i test için ayrılmıştır

Teknik Özellikler:
Python 3.8 ile geliştirilmiştir
Kullanılan kütüphaneler: scikit-learn, NLTK, TurkishStemmer
Google Colab üzerinde eğitilmiştir
