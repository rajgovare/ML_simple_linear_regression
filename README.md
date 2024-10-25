---

# Simple Linear Regression Model  

## Overview  
This project showcases the development of a **Simple Linear Regression model** using Python along with the `scikit-learn` library.
The objective is to predict students' scores based on the number of hours they studied.  

---

## Methodology  
1. **Data Collection**:  
   - The dataset is accessed from the URL: [http://bit.ly/w-data](http://bit.ly/w-data).  
   - It consists of two attributes:  
     - **Hours**: Number of hours a student studied.  
     - **Scores**: Marks scored by the student.  

2. **Data Preprocessing**:  
   - Separates the dataset into **independent features** (`x`) and **dependent labels** (`y`).
   - The dataset is split into **80% training data** and **20% test data** using `train_test_split`.  

3. **Data Visualization**:  
   - A **scatter plot** is drawn to display the relationship between study hours and obtained scores.  
   - This visualization helps in identifying any linear trend in the data.  

4. **Model Training**:  
   - A **Linear Regression model** is instantiated using `scikit-learn`.  
   - The model is trained on the training data to find the relationship between `Hours` and `Scores`.  
   - The **regression coefficient** (slope) and **intercept** are printed for better understanding of the model’s behavior.  

5. **Prediction**:  
   - The trained model is utilized to predict the scores on the test dataset.  
   - A **regression line** is overlaid on the scatter plot to visualize the model’s fit.  

6. **Evaluation**:  
   - The model’s performance is measured using **Mean Absolute Error (MAE)** to gauge the prediction accuracy.  

---

## Requirements  
To run this project, make sure the following packages are installed:

```bash
pip install pandas matplotlib scikit-learn
```

---

## Results  
This project produces the following outputs:  
- The **regression coefficient** (slope) and **intercept** of the trained model.  
- A **table** showing a comparison between actual and predicted scores for the test set.  
- The **Mean Absolute Error (MAE)**, which indicates the model's prediction error.  

---
