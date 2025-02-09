# AI Pneumonia Detector  

## Overview  
AI Pneumonia Detector is a deep learning-based web app that analyzes chest X-ray images to detect pneumonia. The system provides a probability score and an easy-to-understand explanation to help users interpret the results.  

## Inspiration  
Pneumonia diagnosis can be complex, especially for elderly patients. This tool helps simplify the process by providing clear AI-driven explanations.  

## Features  
- **Pneumonia Detection**: Uses a pre-trained DenseNet-121 model to analyze chest X-rays.  
- **Probability Score**: Outputs a high or low probability of pneumonia.  
- **AI-Generated Explanation**: Uses OpenAI’s GPT to explain the diagnosis in simple terms.  
- **Streamlit UI**: Provides an easy-to-use web interface for uploading and analyzing images.  

## Dataset  
The model is trained using the **ChestX-ray14** dataset from [CheXNet](https://github.com/arnoweng/CheXNet/tree/master/ChestX-ray14/images), a widely used dataset for pneumonia detection.  

## How It Works  
1. **Upload a Chest X-ray**: Users upload an X-ray image via the Streamlit web interface.  
2. **AI Analysis**: The pre-trained DenseNet-121 model processes the image and predicts the probability of pneumonia.  
3. **Explanation Generation**: OpenAI’s GPT generates a simple explanation based on the probability score.  

## Technologies Used  
- **Deep Learning**: Pre-trained DenseNet-121 from CheXNet  
- **Python**: For backend processing  
- **Streamlit**: To build the web interface  
- **Google Colab**: For training and running the model  
- **OpenAI GPT**: For generating easy-to-understand explanations  

## Installation & Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/AI-Pneumonia-Detector.git
   cd AI-Pneumonia-Detector
