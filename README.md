# 🎙️ Speech Emotion Recognition using Librosa and Machine Learning

This project focuses on building a Speech Emotion Recognition (SER) system that classifies audio clips into different emotional states such as **happy**, **sad**, **angry**, and **neutral** using extracted features like MFCC, Chroma, and Mel spectrograms.

---

## 📂 Dataset
- **Source**: RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
- **Classes**: Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, Surprised
- **Format**: `.wav` files

---

## 🛠️ Technologies Used
- **Python**
- **Jupyter Notebook**
- **Librosa** – for audio processing
- **SoundFile** – to read audio data
- **Scikit-learn** – model building, evaluation, and hyperparameter tuning
- **Matplotlib / Seaborn** – visualizations

---

## 🧠 Features Extracted
- **MFCC (Mel-Frequency Cepstral Coefficients)**
- **Chroma Features**
- **Mel Spectrogram**

These features were concatenated to form a numerical feature vector for each audio file.

---

## 🚀 Model & Performance
- **Classifier Used**: `MLPClassifier` (Multi-layer Perceptron)
- **Accuracy Achieved**: ~55.67%
- **Evaluation Metrics**: Accuracy, Confusion Matrix, Classification Report

---

## 🔍 Model Evaluation

```python
from sklearn.metrics import confusion_matrix, classification_report
