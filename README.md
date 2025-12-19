# Stress Detection from Text using DistilBERT
This project detects psychological stress from textual input using a **transformer-based NLP model (DistilBERT)**.  
The model is trained on stress-labeled social media text and provides **real-time stress prediction** through a simple **Streamlit web application**.

## Project Overview
- **Problem**: Automatically identify stress from user-written text  
- **Approach**: Fine-tune a DistilBERT transformer for binary text classification  
- **Output**:  
  - `Stressed`  
  - `Not Stressed`  
- **Deployment**: Streamlit web interface  
- **Model Hosting**: Hugging Face Model Hub (public)

## Model Details
- **Base Model**: `distilbert-base-uncased`
- **Task**: Binary Text Classification
- **Labels**:
  - `1` → Stressed
  - `0` → Not Stressed
- **Enhancement**:
  - Probability thresholding (≥ 0.7) to reduce false positives

## model files: 
Trained model files are hosted on Hugging Face: https://huggingface.co/lavenhub/Stress_Detection_DistilBERT

## steps to test the model
- download all the files from files and version option in hugging-face
- put all the files except app.py and requirements.txt in a single forlder and name it stress_DistilBERT
- save on the files in single folder loacally
- set up the enviroment in command prompt for the given folder where the files are stored
- run the command: pip install streamlit scikit-learn joblib
- then execute: streamlit run app.py
- local host will get directed to a webpage to test the model




