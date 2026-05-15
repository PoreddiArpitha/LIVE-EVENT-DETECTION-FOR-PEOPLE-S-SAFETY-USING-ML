# 🎯 **Project Title**

<h1>Live Event Detection for People’s Safety Using Audio Analysis and LightGBM</h1>

---

# 📌 **Project Overview**

This project is a **machine learning-based audio classification system** designed to detect real-world events (like alarms, screams, accidents, etc.) from audio signals to enhance public safety.

The system:

* Takes **audio (.wav) files** as input
* Extracts **acoustic features** using signal processing techniques
* Trains multiple ML models
* Compares performance of classifiers
* Uses a **LightGBM model** as the proposed approach
* Provides **GUI-based interaction using Tkinter**

---

# 🎯 **Objectives**

1. Detect critical real-world events from audio signals
2. Improve public safety through automated sound recognition
3. Compare performance of multiple ML algorithms
4. Handle **imbalanced datasets using SMOTE**
5. Build a **user-friendly GUI system** for easy interaction
6. Provide real-time prediction for new audio inputs

---

# 🛠️ **Technologies Used**

### 💻 Programming & GUI

* Python
* Tkinter (GUI development)

### 📊 Data Processing & Visualization

* NumPy
* Pandas
* Matplotlib
* Seaborn

### 🎧 Audio Processing

* Librosa
* OpenCV (for visualization)

### 🤖 Machine Learning

* Scikit-learn
* XGBoost
* LightGBM
* Imbalanced-learn (SMOTE)

### 📦 Model Persistence

* Joblib
* Pickle

---

# 🧱 **Project Structure**

```
project/
│
├── model/                  # Saved models & cached features
│   ├── X.npy
│   ├── Y.npy
│   ├── MLPClassifier
│   ├── KNN
│   ├── DTC
│   ├── LRC
│   ├── LGBMClassifier
│
├── dataset/                # Audio dataset (organized in folders by class)
│   ├── class1/
│   ├── class2/
│   └── ...
│
├── Test Data/              # New audio samples for prediction
│
├── main.py                 # Main application 
├── waveplot.png            # Generated visualization
```

---

# ⚙️ **Installation & Setup**

### 1️⃣ Clone the repository

```bash
git clone https://github.com/PoreddiArpitha/LIVE-EVENT-DETECTION-FOR-PEOPLE-S-SAFETY-USING-ML.git
```

### 2️⃣ Create a virtual environment

```bash
python -m venv myenv
myenv\Scripts\activate
```
### 3️⃣ Install required librabries

Run this command:

```bash
pip install numpy pandas matplotlib seaborn librosa opencv-python scikit-learn xgboost lightgbm imbalanced-learn joblib
```

---

# ▶️ **How to Run the Project**

1. Run the Python file:

```bash
python Main.py
```

2. GUI will open with buttons:

### Workflow:

1. **Upload Dataset**
2. **Preprocess Dataset**
3. **Train-Test Splitting**
4. Train models:

   * MLP
   * KNN
   * Decision Tree
   * Logistic Regression
   * AdaBoost
5. (Optional) Apply **SMOTE Data Balancing**
6. Run **Proposed LGBM**
7. Click **Prediction** → upload new audio file

---

# 🤖 **Model Details**

## 🔊 Feature Extraction

Each audio file is converted into a feature vector using:

* MFCC (Mel Frequency Cepstral Coefficients)
* Chroma features
* Mel Spectrogram
* Spectral Contrast
* Tonnetz
* RMS Energy
* Spectral Bandwidth
* Spectral Centroid
* Spectral Rolloff
* Zero Crossing Rate

---

## 📊 Models Used

### Existing Models:

* MLP Classifier
* K-Nearest Neighbors (KNN)
* Decision Tree
* Logistic Regression
* AdaBoost

### Proposed Model:

* **LightGBM Classifier**

  * Faster training
  * Better handling of large datasets
  * High accuracy in classification tasks

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

---

## ⚖️ Data Balancing

* **SMOTE (Synthetic Minority Oversampling Technique)**
  Used to handle class imbalance by generating synthetic samples.

---

# 🔮 **Future Enhancements**

1.  Real-time audio streaming (live microphone input)
2.  Mobile or web-based deployment
3.  Deep learning models (CNN, RNN, LSTM for audio)
4.  Integration with IoT-based safety systems
5.  Alert system (SMS/email notifications during danger detection)
6.  Cloud deployment for scalability
7.  Improve noise reduction techniques
8.  Hyperparameter tuning for better accuracy
9.  Support more audio formats (mp3, flac, etc.)

---

# 👩‍💻 Author

Name: Poreddi Arpitha
(B.Tech AI&ML Student)
Role: Developer / Research Student


# 📜 License

This project is developed for educational and research purposes.
