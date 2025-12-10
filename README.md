# Plant-Leaf-Disease-Detection-with-CNN-Transfer-Learning
CNN ve transfer learning kullanarak bitki yaprak hastalığı tespiti yapan derin öğrenme projesi.



# 🌿 Plant Leaf Disease Detection with Deep Learning

Bu projede bitki yapraklarındaki hastalıkları tespit etmek amacıyla derin öğrenme tabanlı görüntü sınıflandırma modelleri geliştirilmiştir. Projede sıfırdan oluşturulmuş bir CNN modeli ve transfer learning kullanılarak ResNet50 modelleri eğitilmiş ve karşılaştırılmıştır.

---

## 📊 Kullanılan Veri Seti
- **PlantVillage Dataset**
- Kaggle üzerinden alınmıştır.
- Toplam **15 sınıf** içermektedir.

---

## ⚙️ Uygulanan Adımlar
- Görüntüler **224x224** boyutuna getirildi.
- Veri seti **Train / Validation / Test** olarak bölündü.
- **Data Augmentation** uygulandı (rotate, shift, zoom, flip).
- Modeller eğitildi ve performansları karşılaştırıldı.

---

## 🧠 Kullanılan Modeller
- ✅ **CNN (Sıfırdan oluşturuldu)**
- ✅ **ResNet50 (Transfer Learning)**
- ✅ **ResNet50 Fine-Tuned**

---

## 📈 Model Karşılaştırma Sonuçları

| Model | Train Acc | Val Acc | Test Acc |
|-------|-----------|----------|----------|
| CNN | ~0.89 | ~0.90 | ~0.90 |
| ResNet50 | ~0.33 | ~0.39 | ~0.39 |
| ResNet50 Fine-Tuned | ~0.15 | ~0.16 | ~0.16 |

➡️ **Bu sonuçlara göre en başarılı model CNN olmuştur.**

---

## 🧪 Test ve Tahmin
Model, harici bir yaprak görseli üzerinde test edilmiştir ve başarılı şekilde sınıf tahmini yapmıştır.

---

## ✅ Sonuç
Bu projede:
- CNN modeli transfer learning modellerine kıyasla daha iyi performans göstermiştir.
- Bunun sebebi veri artırma ve veri setine özel öğrenme yapabilmesidir.
- Proje, gerçek hayatta tarım hastalıklarının erken tespiti için kullanılabilir.

---

## 🚀 Kullanılan Teknolojiler
- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas
- Matplotlib, Seaborn
- Google Colab

---

