Aygaz Görüntü İşleme Bootcamp Projesi
Bu proje, CNN (Convolutional Neural Network) modellerinin temelini pekiştirmek amacıyla geliştirilmiş bir hayvan sınıflandırma sistemidir. Proje, farklı ışık koşullarında ve renk sabitliği uygulanmış görüntülerle modelin performansını test etmeyi amaçlamaktadır.
Proje Özeti
Proje kapsamında 10 farklı hayvan türünü (collie, dolphin, elephant, fox, moose, rabbit, sheep, squirrel, giant panda, polar bear) sınıflandıran bir CNN modeli geliştirilmiştir. Model, farklı ışık koşullarında ve renk sabitliği algoritması uygulanmış görüntülerle test edilmiştir.
Veri Seti

Kaynak: Animals with Attributes 2 (AwA2) veri seti
Sınıf Sayısı: 10 hayvan türü
Görüntü Sayısı: Her sınıf için 650 görüntü (toplam 6500 görüntü)
Bölümleme: %70 eğitim, %30 test

Kullanılan Teknolojiler

Python 3.x
Kütüphaneler:

TensorFlow: CNN modelinin oluşturulması ve eğitimi için
OpenCV (cv2): Görüntü işleme ve manipülasyon için
NumPy: Sayısal işlemler için
Matplotlib: Görselleştirme için
scikit-learn: Veri bölümleme için



Model Mimarisi

Konvolüsyon katmanları
Maksimum havuzlama katmanları
Dropout katmanları
Tam bağlantılı katmanlar
Aktivasyon fonksiyonu: ReLU
Çıkış katmanı aktivasyonu: Softmax
Kayıp fonksiyonu: Categorical Crossentropy

Test Senaryoları

Orijinal Test Seti

Temel model performansının değerlendirilmesi


Manipüle Edilmiş Test Seti

Farklı ışık koşullarında test
Parlaklık ve kontrast değişimleri


Renk Sabitliği Uygulanmış Test Seti

Gray World algoritması kullanılarak renk sabitliği uygulanmış görüntülerle test



Veri Ön İşleme

Görüntü boyutlandırma: 224x224 piksel
Normalizasyon: Piksel değerleri 0-1 aralığına ölçeklendirildi
Veri artırma teknikleri:

Rastgele döndürme
Yatay çevirme
Zoom
Kontrast değişimleri



Proje Sonuçları
[Bu bölüm modelin farklı test senaryolarındaki başarı oranlarıyla güncellenecek]
Kurulum ve Çalıştırma

Gerekli kütüphanelerin kurulumu:

bashCopypip install tensorflow opencv-python numpy matplotlib scikit-learn

Veri setinin indirilmesi ve hazırlanması
Model eğitimi ve test aşamaları
Sonuçların değerlendirilmesi

Gelecek İyileştirmeler

Farklı renk sabitliği algoritmalarının denenmesi
Model mimarisinin optimizasyonu
Veri artırma tekniklerinin genişletilmesi
Daha fazla sınıf eklenmesi




colab bağlantı:https://colab.research.google.com/drive/1tAlWITceXNMiQ0SjAG40-tU4KH13ZdLt?usp=sharing
