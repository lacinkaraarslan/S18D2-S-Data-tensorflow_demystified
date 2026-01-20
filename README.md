```bash
# TensorFlow & Keras – Derin Öğrenmenin Temelleri (Recap)

Bu proje, TensorFlow ve Keras kullanılarak derin öğrenmenin temel
kavramlarını pekiştirmek amacıyla hazırlanmış bir recap (özet) çalışmasıdır.

## İçerik

### 1. TensorFlow ve NumPy Karşılaştırması
- TensorFlow Tensor ve NumPy Array farkları
- Mutable (NumPy) vs Immutable (TensorFlow Tensor) yapılar
- Bilinçli olarak oluşturulan hata örnekleri ve açıklamaları

### 2. Keras Model Mimarileri
- Sequential API kullanımı
- Functional API ile model oluşturma
- Parametre sayılarının model.summary() ile incelenmesi
- Parametrelerin manuel olarak hesaplanması

### 3. Regresyon Modeli
- Dense (50) → Dense (20) → Dense (1) mimarisi
- ReLU aktivasyon fonksiyonu
- Adam optimizer ve MSE loss
- Model eğitimi (fit) ve loss (yakınsama) grafiği
- init_model fonksiyonu ile modelin yeniden başlatılması

### 4. İkili Sınıflandırma Modeli
- Sigmoid aktivasyonlu çıkış katmanı
- Binary Crossentropy loss
- Accuracy metriği
- init_model_2 fonksiyonu

### 5. Çok Sınıflı (10 Sınıf) Sınıflandırma Modeli
- Softmax aktivasyonlu çıkış katmanı
- Sparse Categorical Crossentropy loss
- Accuracy metriği
- init_model_10_class fonksiyonu

### 6. Donanım Kullanımı
- CPU ve GPU device seçimi
- TensorFlow’da hızlandırıcı bellek (GPU/TPU) kavramı
- Yerel ortamda GPU bulunmaması durumunun açıklanması

## Kullanılan Teknolojiler
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

## Not
Bu çalışma eğitim amaçlıdır ve derin öğrenme kavramlarını
anlamaya yönelik bir özet (recap) niteliği taşır.
```
