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

## model files (Huggin-face) 
- https://huggingface.co/lavenhub/Stress_Detection_DistilBERT



