
# 🎤 Speech Emotion Recognition (SER) Project

This project focuses on recognizing emotions from speech using deep learning techniques. It involves feature extraction, data augmentation, and model comparison using CNN, CNN + Bi-directional LSTM, and RNN architectures. The datasets used for this project include **RAVDESS, TESS, and SAVEE**.

---

## 🚀 Features
- **Emotion Classes**: Happy, Angry, Neutral, Sad, Calm, Disgust, Fear, and Surprise.
- **Datasets**:
  - [RAVDESS](https://zenodo.org/record/1188976)
  - [TESS](https://tspace.library.utoronto.ca/handle/1807/24487)
  - [SAVEE](http://kahlan.eps.surrey.ac.uk/savee/)
- **Models Compared**:
  - ✅ **CNN**
  - ✅ **CNN + Bi-Directional LSTM**
  - ✅ **RNN**
- **Augmentation**: Applied **noise addition, pitch shifting, and time-stretching** to enhance dataset diversity.
- **Libraries Used**:
  - `Librosa` (for audio feature extraction - version 0.10)
  - `TensorFlow/Keras` (for model building and training)
  - `NumPy, Pandas, Matplotlib` (for data processing and visualization)

---

## 📌 Workflow
1. **Preprocessing**:
   - Audio files processed with **Librosa** to extract **MFCCs** as features.
   - Data augmentation techniques applied to increase dataset size.
2. **Feature Extraction**:
   - Extracted **MFCCs, Chroma, and Spectral Contrast** features.
3. **Model Training**:
   - Implemented **CNN, CNN + Bi-Directional LSTM, and RNN** architectures.
   - Compared their performance based on **accuracy, precision, recall, and F1-score**.
4. **Evaluation**:
   - Models evaluated on **test datasets** and compared for efficiency.

---

## 🛠 How to Run the Project
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-repository/speech-emotion-recognition.git
cd speech-emotion-recognition
