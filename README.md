# ANN-CNN-Examples
# Balık Sınıflandırma Projesi

## Proje Amacı
Bu projede, görüntü işleme ve derin öğrenme teknikleri kullanarak balık türlerini sınıflandırmak amacıyla bir yapay sinir ağı (ANN) modeli geliştirilmiştir. Amaç, modelin doğruluğunu artırmak ve balık türlerinin otomatik olarak tanınmasını sağlamaktır.

## Veri Seti
Proje, **A Large Scale Fish Dataset** veri setini kullanmaktadır. Bu veri seti, farklı balık türlerini temsil eden etiketlerle birlikte birçok balık görüntüsü içermektedir.

## Yöntemler
- **Model:** Yapay Sinir Ağı (ANN)
- **Hedef:** Balık türlerini sınıflandırmak.
- **Değerlendirme Metrikleri:** Doğruluk, Kaybı, F1 Skoru.

### Kullanılan Yöntemler
- **Veri Ön İşleme:** Görüntülerin boyutlandırılması ve normalizasyonu.
- **Model Yapısı:** 
  - Girdi katmanı: Görüntüleri düzleştirerek 1D forma getirme.
  - Gizli katmanlar: Relu aktivasyon fonksiyonu ile 64 ve 32 nöronlu katmanlar.
  - Çıkış katmanı: Softmax aktivasyon fonksiyonu ile balık türlerini sınıflandırma.

## Sonuçlar
Modelin eğitim ve test sonuçları değerlendirildi. Aşağıdaki grafikler, eğitim süreci boyunca kayıp ve doğruluk değerlerini göstermektedir:
- Eğitim ve doğrulama kaybı
- Eğitim ve doğrulama doğruluğu
- Karışıklık matrisi

## Gelecek Çalışmalar
- **Model Optimizasyonu:** Daha derin sinir ağı mimarileri ile modelin performansını artırma.
- **Veri Artırma:** Görüntü augmentasyonu ile eğitim veri setini genişletme.
- **Gerçek Zamanlı Uygulama:** Modelin gerçek zamanlı balık sınıflandırma sistemlerinde uygulanması.

## Kullanılan Kütüphaneler
- `pandas`: Veri analizi ve işleme.
- `numpy`: Matematiksel işlemler için.
- `opencv-python`: Görüntü işleme.
- `tensorflow`: Derin öğrenme modeli oluşturma ve eğitme.

## Kaggle Bağlantısı
Proje ile ilgili daha fazla bilgi için: [Balık Sınıflandırma Projesi](https://www.kaggle.com/your-kaggle-username/fish-classification) 
ANN Mimarisi için: [Balık Sınıflandırma Projesi](https://www.kaggle.com/code/sinemeviker/fish-dataset-ann)
CNN Mimarisi için:[Balık Sınıflandırma Projesi](https://www.kaggle.com/code/sinemeviker/fish-dataset-cnn)
