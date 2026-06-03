# Crop Recommendation System using Machine Learning

## Overview

The Crop Recommendation System is a machine learning-based application designed to recommend the most suitable crop for cultivation based on soil nutrients and environmental conditions. The system analyzes various agricultural parameters and predicts the optimal crop to improve productivity and support data-driven farming decisions.

## Problem Statement

Selecting the appropriate crop for cultivation is a critical decision in agriculture. Farmers often face challenges in choosing crops that are compatible with soil conditions and climate factors. This project aims to assist farmers by providing crop recommendations using machine learning techniques.

## Dataset Description

The dataset contains agricultural and environmental attributes used for crop prediction.

### Features

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH Value
- Rainfall

### Target Variable

- Crop Label

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Analysis
5. Model Training
6. Model Evaluation
7. Crop Prediction

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Process

### Data Preprocessing

- Loaded and inspected the dataset
- Checked for missing values
- Performed data cleaning
- Prepared features and target variables

### Exploratory Data Analysis

- Statistical summary of the dataset
- Correlation analysis
- Data visualization using plots and heatmaps

### Model Training

The dataset was split into training and testing sets. Machine learning algorithms were trained and evaluated to identify the best-performing model.

### Model Evaluation

Performance was evaluated using classification metrics and accuracy scores.

## Results

- Achieved an accuracy of **99.36%**
- Successfully predicted suitable crops based on soil and environmental conditions
- Demonstrated the effectiveness of machine learning in agricultural decision-making

## Project Structure

```text
Crop-Recommendation-System/
│
├── Crop_recommendation.csv
├── crop-recommendation-99-36-accuracy.ipynb
├── README.md
├── requirements.txt
└── screenshots/
```

## Installation

Clone the repository:

```bash
git clone https://github.com/surya675-git/crop-recommendation-system.git
```

Navigate to the project directory:

```bash
cd crop-recommendation-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
crop-recommendation-99-36-accuracy.ipynb
```

and run all cells.

## Applications

- Smart Agriculture
- Precision Farming
- Crop Yield Optimization
- Agricultural Decision Support Systems

## Future Enhancements

- Deploy the model as a web application using Streamlit or Flask
- Integrate real-time weather APIs
- Develop a mobile application for farmers
- Add fertilizer recommendation functionality
- Support multilingual interfaces

## Author

**Surya**

## License

This project is intended for educational and research purposes.
