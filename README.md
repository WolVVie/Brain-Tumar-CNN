# Brain Tumor Classification using CNN (PyTorch)

Bu proje, beyin tümörü görüntülerini sınıflandırmak için PyTorch kullanılarak geliştirilmiş bir Convolutional Neural Network (CNN) modelini içerir.
Model, Kaggle’daki Brain Tumor MRI dataseti üzerinde eğitilmiş olup veri hazırlama, eğitim döngüsü, değerlendirme ve görselleştirme adımlarının tamamını kapsar.  

# Features

✔️ Custom PyTorch Dataset Class (NumPy → PIL → Tensor pipeline)

✔️ CNN architecture optimized for 128×128 medical images

✔️ Train / Validation / Test split (70/15/15)

✔️ Training & validation loops (loss + accuracy tracking)

✔️ Confusion Matrix, Classification Report, ROC Curve

✔️ Random sample predictions (10-image visualization)

✔️ End-to-end notebook (fully reproducible)
  
# 📁 Project Structure

│── notebook.ipynb           
│── README.md              
  
# 🧰 Technologies Used

Python

PyTorch

Torchvision

NumPy

Pandas

Matplotlib

scikit-learn
  
# 📊 Model Architecture

3 adet convolutional block

BatchNorm + ReLU + MaxPool

128×16×16 → Fully Connected layers

AdamW optimizer + CrossEntropyLoss
  
# 🖼️ Example Predictions

Notebook içinde test setinden 10 rastgele görüntü seçilip
modelin True Label vs Predicted Label çıktısı görselleştirilmiştir.
  
# 📌 Evaluation Metrics

## Aşağıdaki metrikler notebookta otomatik olarak üretilir:

✔️ Confusion Matrix

✔️ Precision / Recall / F1-score

✔️ ROC Curve + AUC

✔️ Loss & Accuracy curves
  
# 🔧 How to Run

## Repo’yu klonla:

git clone https://github.com/WolVVie/brain-tumor-cnn.git


## Gereken kütüphaneleri kur:

pip install -r requirements.txt


## Notebook’u çalıştır:

jupyter notebook

# 📥 Dataset

## Dataset Kaggle üzerinden indirilebilir:
https://www.kaggle.com/datasets/jakeshbohaju/brain-tumor  

Notebook içinde Kaggle Hub ile otomatik yükleme kodu da mevcuttur.
