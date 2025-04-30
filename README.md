# Garbage Image Classification with ResNet101V2

This project implements an image classification model to categorize garbage images into 10 classes using a convolutional neural network with a ResNet101V2 backbone. It was developed using TensorFlow and Keras and supports deployment in TFLite and TensorFlow.js formats.

## 📁 Dataset

- **Source**: [Kaggle - Garbage Classification V2](https://www.kaggle.com/datasets/sumn2u/garbage-classification-v2)
- **License**: MIT
- **Classes**:
  - `battery`
  - `biological`
  - `cardboard`
  - `clothes`
  - `glass`
  - `metal`
  - `paper`
  - `plastic`
  - `shoes`
  - `trash`

## 🚀 Features

- Kaggle API authentication and dataset downloading
- Dataset preprocessing: normalization, splitting (train/validation/test), and augmentation
- Model building using:
  - ResNet101V2 base (frozen)
  - Custom convolutional and dense layers
- Training with callbacks: EarlyStopping and ReduceLROnPlateau
- Performance evaluation: accuracy, confusion matrix
- Export to:
  - TFLite (`model.tflite`) for mobile inference
  - TensorFlow.js (`tfjs_model/`) for web deployment

## 📊 Results

- **Validation Accuracy**: ~92.18%
- **Test Accuracy**: **92.14%**

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/garbage-classification.git
   cd garbage-classification

2. Install dependencies
   pip install -r requirements.txt

3. Open the notebook in Google Colab or Jupyter:
   Proyek_Klasifikasi_Gambar_Template_Submission_Akhir.ipynb
   
5. Run all cells to train and export the model.

📦 Exported Files

saved_model/ – TensorFlow SavedModel format
    
tflite/model.tflite – TFLite model

tflite/label.txt – Class labels for TFLite

tfjs_model/ – TensorFlow.js model directory

