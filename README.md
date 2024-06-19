# India Road Accident Hotspot Area Prediction Using J48 Algorithm

This project aims to predict road accident hotspots in India using the J48 classification algorithm. The analysis is performed using WEKA and RapidMiner, leveraging a dataset of road accidents in India from 2017 to 2022.

## Project Overview

### Introduction
Road accidents pose a significant global concern, resulting in fatalities, injuries, and casualties. In India, road accidents have become increasingly prevalent each year. This study implements the J48 classification technique to build a model for predicting road accident hotspot areas in India.

### Objectives
- Predict road accident hotspots using the J48 algorithm.
- Analyze the factors contributing to road accidents.
- Improve road safety measures by identifying high-risk areas.

## Dataset

### Data Source
The dataset used in this project is ["Road Accident Severity in India"](https://www.kaggle.com/datasets/s3programmer/road-accident-severity-in-india) from Kaggle, covering the years 2017 to 2022. It includes details such as location, time, weather, road type, and vehicle information.

### Data Attributes
- **Numerical Attributes**:
  - Number of vehicles involved
  - Number of casualties
- **Nominal Attributes**:
  - Time of accident
  - Day of week
  - Age band of driver
  - Sex of driver
  - Educational level of driver
  - Type of vehicle
  - Weather conditions
  - Road surface conditions
  - Light conditions
  - Type of collision
  - And more...

## Methodology

### Data Understanding
- Analyzing the dataset structure and key characteristics.
- Evaluating data quality and preparing for analysis.

### Data Preparation
- **Data Cleaning**: Removing incorrect, incomplete, and inaccurate data. [Cleaned Data](https://github.com/Eisyatin/India-Road-Accident-Hotspot-Area-Prediction-using-J48-Algorithm/blob/main/RoadNew-cleaned.arff)
- **Handling Missing Values**: Using WEKA's "ReplaceMissingValues" filter.
- **Outlier Detection**: Using "InterquartileRange" and "RemoveWithValues" filters.
- **Data Transformation**: Discretization of numerical attributes and removal of unnecessary attributes.

### Model Development
- Implementing the J48 classification algorithm using WEKA.
- Evaluating model performance using cross-validation and percentage split.

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score

## Results and Analysis

### Model Performance
- The J48 algorithm achieved high accuracy in predicting accident hotspots.
- Accuracy improved after reducing the dataset to 20 most important attributes. [Reduced Data](https://github.com/Eisyatin/India-Road-Accident-Hotspot-Area-Prediction-using-J48-Algorithm/blob/main/RoadNew_reduced.arff)

### Visualizations
- Tree visualizer for best accuracy in cross-validation and percentage split.
- Bar graphs for evaluation results.

## How to Run the Project

### Requirements
- WEKA
- Microsoft Excel (for data preprocessing)

### Steps
1. **Data Preparation**:
   - Clean and preprocess the data using WEKA and Excel. [Processed Data](https://github.com/Eisyatin/India-Road-Accident-Hotspot-Area-Prediction-using-J48-Algorithm/blob/main/RoadNew-cleaned.arff)
2. **Model Training**:
   - Train the J48 model using the preprocessed dataset in WEKA.
3. **Evaluation**:
   - Evaluate the model using cross-validation and percentage split techniques.
4. **Visualization**:
   - Generate tree visualizations and performance metrics.

## Project Files and Structure

- **/data**: Contains the raw, cleaned, and reduced datasets.
- **/weka**: WEKA files including ARFF, models, and experiment settings.
- **/scripts**: Scripts for data preprocessing and custom analysis.
- **/results**: Visualizations, evaluation metrics, and analysis reports.
- **/docs**: Project report and related documentation.
- **/articles**: Contains the article detailing the project findings.

## Article

For more detailed information on the project findings, please refer to the article:
[India Road Accident Hotspot Area Prediction Using J48 Algorithm](https://github.com/Eisyatin/India-Road-Accident-Hotspot-Area-Prediction-using-J48-Algorithm/blob/main/India%20Road%20Accident%20Hotspot%20Area%20Prediction%20Using%20J48%20Algorithm.pdf)

## Team Members

- **Aina Farzana Binti Zulkifli** (2021817142)
- **Nur Eisyatin Radhiah Binti Annuar** (2021610238)
- **Siti Mukhlisah Binti Muskamal** (2022815898)
- **Yasmin Nabila Binti Othman** (2021619506)

Faculty of Computer and Mathematical Sciences,
Universiti Teknologi MARA (UiTM), Malaysia

## References

- Bahiru, T. K., et al. (2023). Mining Road Traffic Accident Data for Prediction of Accident Severity. 2023 International Conference on Intelligent Data Communication Technologies and Internet of Things (IDCIoT).
- Ghandour, A. J., et al. (2020). Analyzing factors associated with fatal road crashes: A machine learning approach. International Journal of Environmental Research and Public Health.
- Towards AI. (2019). How, When, and Why Should You Normalize / Standardize / Rescale Your Data.
- Kurika, A. E., et al. (2020). Predicting Factors of Vehicular Accidents using Machine Learning Algorithm. International Journal of Emerging Trends in Engineering Research.
- Mutalib, S. A. R. (2021). Predictive Analytics Applications with WEKA.
- Paul, A. K., et al. (2022). A Data-Driven Study to Investigate the Causes of Severity of Road Accidents.
- Posonia, A. M., et al. (2020). Machine learning-based diabetes prediction using decision tree J48. Proceedings of the 3rd International Conference on Intelligent Sustainable Systems.
- Viswanath, D., et al. (2021). A Road Accident Prediction Model Using Data Mining Techniques. Proceedings - 5th International Conference on Computing Methodologies and Communication.
- Amazon Web Services. What is Data Preparation - Data Preparation Explained.

---
