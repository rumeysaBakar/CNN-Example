# CNN ile Görüntü Sınıflandırma Projesi

## Proje Tanımı
Bu proje, derin öğrenmenin temel yapı taşlarından biri olan Convolutional Neural Network (CNN) mimarisiyle görsel sınıflandırma problemi çözmektedir. Eğitimde TensorFlow ve TensorFlow Datasets (TFDS) kullanılmıştır. Amaç, temel bir CNN mimarisinin pratikte nasıl kurulup eğitileceğini göstermek ve modelin başarımını ölçmektir.

## Kullanılan Teknolojiler ve Kütüphaneler
- Python 3.x
- TensorFlow & Keras
- TensorFlow Datasets (TFDS)
- NumPy, Matplotlib (görselleştirme ve veri işleme için)

## Veri Seti
Proje kapsamında, TFDS üzerinden kolayca erişilebilen popüler bir görüntü sınıflandırma veri seti kullanılmıştır. (Kullanılan veri setini koddan veya baştan belirtmek istersen buraya ismini ekleyebilirsin.)

## Model Mimarisi
Model, Keras'ın Sequential API'si ile oluşturulmuş klasik bir CNN mimarisidir:
- Birden fazla Convolutional ve MaxPooling katmanı
- Flatten ve Dense katmanları
- Aktivasyon fonksiyonu olarak `relu` ve çıktı katmanında `softmax`

## Eğitim ve Değerlendirme
- Model, eğitim verisi ile eğitilmiş ve doğruluk/başarı oranı takip edilmiştir.
- Eğitilmiş model `.h5` uzantısıyla kaydedilmiştir.
- Eğitim ve test doğruluk oranları çıktı olarak gösterilmiştir.

## Nasıl Çalıştırılır?
Google Colab veya Jupyter Notebook üzerinde aşağıdaki adımları takip edebilirsiniz:
1. Gerekli kütüphaneleri kurun.
2. Notebook'u açın ve adım adım hücreleri çalıştırın.
3. Eğitim bittikten sonra modeli kaydedebilir veya çıktılarını inceleyebilirsiniz.

## Gereksinimler
- Python 3.x
- TensorFlow >= 2.x
- tensorflow-datasets

Kurulum için:
```bash
pip install tensorflow tensorflow-datasets
