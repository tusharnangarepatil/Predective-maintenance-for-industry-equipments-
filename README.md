
# Predictive Maintenance for Industrial Equipment

This project aims to design a machine learning solution that predicts machinery failure or maintenence needs based on sensor data, usage history , and environmental conditions.This solutionhelps maintain operational efficiency and reduces maintenence costs.


## Installation

Navigate to the project directory:

```bash
cd predictive_maintenance
```

Install the required packages:

```bash
pip install -r requirements.txt
```
    
## Usage

Prepare the Data : Make sure the Dataset is in the correct format as required by the project.

Run the training script : Execute the model training script using.
```bash
python main.py
```
Monitor predictions : Use the Dashboard to visualize failure of the equiment
## Steps

### Data Gathering:

https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification

### Data Transformation:

Encoding Categorical Variables : The Categorical features "Failure Type " and "Type" were Transformed into numerical values using the 'map' function.This Transformation was useful for enabling the model to interpret Categorical data. 

### Handling Imbalanced Data:

The dataset was biased towards the 'Non failure' class. 
The approch we used is UnderSampling using the algorithm RandomUnderSampler.

### Data Preprocessing:

The Processed Dataset was split into training (80%)
and (20%) sets, allowing the model to be trained and evaluated effectively. 

### Training and Testing:

Predictive maintenance Model is trained in RandomForestClassifier algorithm.

### DashBoard :
The Technology used for Dashboard and Deployment Streamlit 






