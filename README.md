# Fake News Detection using a Hybrid CNN-XGBoost Model

This research project focuses on identifying misinformation and fake news by leveraging a **Hybrid Deep Learning and Machine Learning** architecture. By combining the strengths of Convolutional Neural Networks (CNN) and XGBoost, this model achieves high precision in text classification.

## Project Overview
The spread of fake news is a significant challenge in the digital age. This project proposes a hybrid approach where:
1. **CNN** acts as an automatic feature extractor from raw text.
2. **XGBoost** serves as a powerful classifier to make the final prediction based on those features.

## Hybrid Architecture
The pipeline of this project follows these stages:
* **Pre-processing**: Tokenization, removing stop words, and padding sequences to a uniform length.
* **Feature Extraction (CNN)**: A 1D-CNN layer captures local spatial features and semantic relationships within the news articles.
* **Classification (XGBoost)**: The flattened output from the CNN is passed to an XGBoost classifier, which provides robust decision-making and handles non-linear relationships efficiently.



## Key Features
* **Advanced Text Representation**: Uses word embeddings to represent text in a high-dimensional space.
* **Optimized Performance**: The hybrid nature reduces overfitting compared to a standalone CNN and provides better accuracy than traditional ML models.
* **Comprehensive Evaluation**: Includes metrics like Accuracy, Precision, Recall, and F1-Score.

## Repository Structure
* `Fake_News_Detection_Hybrid.ipynb`: The main notebook containing the model implementation.
* `Data/`: Placeholder for the dataset used for training and testing.
* `Releases/`: Contains stable versions and PDF documentation of the research.

## How to Run
1. Clone the repository:
   ```bash
   https://github.com/professor4044/Fake-News-Detection-using-a-Hybrid-CNN-XGBoost.git
2. Install necessary libraries:
   pip install tensorflow xgboost scikit-learn pandas numpy

   Author: Md. Jamir Shekh
   
   Institution: American International University-Bangladesh (AIUB)
   
