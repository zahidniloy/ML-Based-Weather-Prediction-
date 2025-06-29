
# ClimateWins: ML-Based Weather Prediction Project 🌦️


## Overview
This project is part of a machine learning course focused on predicting weather variations using advanced algorithms. The aim is to help **ClimateWins**, an organization committed to forecasting and understanding climate change, achieve its goals. The project spans multiple achievements, each exploring different machine learning techniques applied to historical weather data to predict atmospheric conditions.

![Img 2](https://github.com/user-attachments/assets/fc84ba4a-09fd-4770-a63d-03af9db14a35)


---

## Objectives
- Identify weather patterns outside the regional norm in Europe.
- Determine if unusual weather patterns are increasing over time.
- Generate possibilities for future weather conditions over the next 25 to 50 years.
- Identify the safest places for people to live in Europe over the next 25 to 50 years.

---

## Dataset
For this project, the following datasets were used:

1. **Weather Conditions Dataset**  
   Downloaded from Kaggle, this dataset includes images of various weather conditions such as sunny, cloudy, rainy, and snowy.  
   *[Download the dataset here](https://www.kaggle.com/datasets)*

2. **European Historical Weather Data**  
   This dataset includes historical weather data from various European cities used for training and testing weather prediction models.  
   *[Download the dataset here](https://www.kaggle.com/datasets)*

3. **Handwritten Digits (MNIST)**  
   Used to train and test handwriting recognition models, helping demonstrate CNN effectiveness.

4. **Pleasant Weather Answers Dataset** *(CareerFoundry proprietary)*  
   Labeled days as "pleasant" (1) and "unpleasant" (0) to help test prediction accuracy. *(Not publicly available)*

---

## Achievements Summary

### Achievement 1: Statistical and Machine Learning Models

**Data Analysis:** Conducted exploratory data analysis (EDA) on historical weather data.

**K-Nearest Neighbors (KNN):** Used to classify weather conditions based on temperature and other features.

**Linear and Logistic Regression:** Used to identify temperature trends and classify binary outcomes (e.g., rain/no rain).

**Random Forest:** Improved prediction accuracy using ensemble decision trees.

![2 5_visual_weather_confusion_matrix](https://github.com/user-attachments/assets/6b6e44d4-782b-4f60-b4d6-9b59b26b4c8d)


  Picture: Weather confusion matrix



---

### Achievement 2: Deep Learning Techniques

**Convolutional Neural Network (CNN):** Built to recognize visual weather patterns using images of various weather conditions.

**Recurrent Neural Network (RNN):** Applied to time-series weather data to capture temporal dependencies.

**Hyperparameter Tuning:** Used grid search and random search to optimize CNN and RNN model settings.

**Model Evaluation:** Evaluated models using accuracy, confusion matrix, and f-scores.


![2 2 1_CNN](https://github.com/user-attachments/assets/275ed1e1-1506-41e2-a99a-21c2b4a64259)


![2 2 2_RNN](https://github.com/user-attachments/assets/b31f390c-6a90-4ffa-8fdc-f956ac722e51)

  
  
  Picture: Confusion matrices and training graphs from Exercise 2.2 CNN/RNN

![2 5_visual_cnn_accuracy_loss](https://github.com/user-attachments/assets/e37cf709-99b4-4fa9-9c38-552511a5b52b)


  
Picture: Optimized CNN accuracy/loss from Exercise 2.5

---

## Project Structure
- **data/**: Contains datasets used for training and validation.
- **notebooks/**: Includes Jupyter notebooks showing all stages from EDA to modeling.
- **presentation/**: Contains the final slides summarizing project insights.
- **images/**: Stores all visuals referenced in the README.

---

## Key Results
- **CNN Model:** Achieved ~75% accuracy classifying weather visuals.
- **Random Forest:** Reached 73% accuracy after hyperparameter tuning.
- **RNN Model:** Effective in tracking long-term weather trends from time-series data.

---

## Thought Experiments for ClimateWins
- **GANs for Forecasting:** Use GANs to simulate future satellite imagery and visualize possible climate events.  


- **Transfer Learning:** Apply pre-trained networks to new datasets with limited samples.  

- **Ensemble Learning:** Combine CNN, RNN, and Random Forest models for stronger predictions.  


---

## Presentation & Analysis
Here is the link to the video presentation:  
📽️ https://vimeo.com/1097220218/5a5da6f75d?ts=0&share=copy

The powerpoint slide is provided with the notebooks.

---

## Getting Started

To run the project locally, follow these steps:

1. **Clone the repository**
```bash
git clone https://github.com/YourUsername/ClimateWins-Weather-Prediction.git
cd ClimateWins-Weather-Prediction
