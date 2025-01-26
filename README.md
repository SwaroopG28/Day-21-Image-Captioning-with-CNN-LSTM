# Image Captioning with CNN-LSTM

## **Overview**
This project demonstrates **Image Captioning** using a **CNN-LSTM architecture**, where:
- A pre-trained **InceptionV3 CNN** extracts features from input images.
- An **LSTM-based decoder** generates textual captions based on the image features.

The model is trained on a dummy dataset for demonstration purposes and can generate captions for unseen images.

---

## **How It Works**
1. **Feature Extraction**:
   - A pre-trained CNN (InceptionV3) is used to extract a feature vector for each image.
2. **Caption Tokenization**:
   - Textual captions are tokenized and converted into numerical sequences using Keras' Tokenizer.
3. **Model Architecture**:
   - The CNN feature vector is combined with an LSTM-based sequence model to predict captions word by word.
4. **Caption Generation**:
   - For a given image, the trained model generates a caption.
