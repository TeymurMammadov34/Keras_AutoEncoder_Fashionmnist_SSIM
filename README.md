# 👕 Fashion MNIST Autoencoder with Keras

Bu projede, Fashion MNIST veri seti kullanılarak bir **autoencoder (otokodlayıcı)** modeli inşa edilmiştir. Amaç, görüntüleri daha düşük boyutta temsil ederek yeniden oluşturmaktır.

---

## 📌 Proje Amacı

- Görüntüleri latent (gizli) uzayda daha küçük bir boyutta temsil etmek
- Temsillerden orijinal görüntüyü yeniden üretmek
- SSIM (Structural Similarity Index) ile çıktıların benzerliğini ölçmek

---

## 🧠 Kullanılan Teknolojiler

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-image (SSIM metriği için)

---

## 🔬 Model Değerlendirme

- **Loss Fonksiyonu:** `binary_crossentropy`
- **Optimizer:** `Adam`
- **Kalite Ölçütü:** SSIM (0–1 arası benzerlik skoru)
- **Ortalama SSIM Skoru:** ~0.8x

---

## 🖼️ Görsel Çıktılar

Modelin orijinal ve yeniden oluşturulmuş görselleri aşağıdaki gibidir:

- Üst sıra: Orijinal görüntüler  
- Alt sıra: Autoencoder tarafından yeniden üretilmiş halleri

---

![autoencoder](https://github.com/user-attachments/assets/a0a1e581-bb36-4ce6-913f-457a274b5c86)


## 👨‍💻 Geliştirici

**Teymur Mammadov** 

