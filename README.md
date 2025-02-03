# Music-genre-Classification

# Music Genre Classification with Convolutional Neural Networks


This project applies **deep learning** techniques to classify music genres using **Convolutional Neural Networks (CNNs)**. The system analyzes sound patterns, including **Mel spectrograms**, to predict the genre of a given audio file. 

## **How It Works**

1. **Upload Audio**: Upload an audio file in the **Prediction** section of the web app.
2. **Analysis**: The system processes the audio, converts it to a **Mel spectrogram**, and uses the trained model for classification.
3. **Results**: The model predicts the genre and displays the result.

---

## **Tech Stack**

- **Python**
- **TensorFlow** (Deep Learning)
- **Keras** (Model building)
- **Librosa** (Audio feature extraction)
- **Streamlit** (Web interface)

---

## **Features**

- Upload and classify audio files into one of 10 genres:  
  `blues`, `classical`, `country`, `disco`, `hiphop`, `jazz`, `metal`, `pop`, `reggae`, `rock`
- Visualization of **Mel spectrograms**
- User-friendly interface built with **Streamlit**

---

## **Project Structure**

- `Music_Genre_App.py`: Streamlit-based web app for audio upload and prediction
- `Train_Music_Genre_Classifier.ipynb`: Notebook for training the model
- `Test_Music_Genre.ipynb`: Notebook for testing the model
- `training_hist.json`: Training and validation metrics (loss and accuracy over epochs)
- `requirement.txt`: List of dependencies
- `README.md`: Project documentation

---

## **Model Training**

The model was trained on the **GTZAN** dataset, a popular benchmark for music genre classification. It contains 30-second audio clips across 10 genres. The training process involved:

- **Feature Extraction**: Conversion of audio clips to **Mel spectrograms**
- **Model Architecture**: Convolutional Neural Network (CNN)
- **Performance Metrics**:
  - **Training Accuracy**: ~98%
  - **Validation Accuracy**: ~90%

---

