# Student Performance Prediction: Theory & Practical Examinations

## **Project Overview**
This project analyzes and predicts student performance in theory and practical examinations using a dataset containing 20 features, including demographics, study habits, attendance, and academic activities. The main goal is to classify students as Pass or Fail and identify key factors influencing performance. Data-driven insights can help educators implement targeted interventions to support at-risk students.

---

## **Dataset**
- **Source:** [Kaggle – Student Performance Factors Dataset](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)  
- **Features:** 20 features including Age, Gender, Hours_Studied, Attendance, Assignments_Completed, and Exam Scores.  
- **Records:** [Insert number of rows]  

---

## **Key Steps**
1. **Data Preprocessing**
   - Handling missing values and duplicates
   - Encoding categorical variables
   - Feature scaling using StandardScaler

2. **Exploratory Data Analysis (EDA)**
   - Visualizations: Heatmaps, Pairplots, Histograms, Boxplots, Scatterplots
   - Insights: Study hours, attendance, and assignment completion strongly influence performance

3. **Model Building**
   - **Random Forest Classifier:** Feature importance and preliminary classification
   - **Deep Learning MLP Model:** Multi-layer perceptron with 2 hidden layers and dropout regularization

4. **Model Evaluation**
   - Metrics: Accuracy, Loss, Confusion Matrix, ROC Curve, AUC
   - Visualization of training performance (loss & accuracy per epoch)

---

## **Deep Learning Model Architecture**
- Input Layer: 18–20 features
- Hidden Layer 1: 64 neurons, ReLU, Dropout 0.3
- Hidden Layer 2: 32 neurons, ReLU, Dropout 0.3
- Output Layer: 1 neuron, Sigmoid activation
- Optimizer: Adam | Loss: Binary Crossentropy | Epochs: 100 | Batch Size: 16

---

## **Results**
- High predictive accuracy and AUC score
- Key features influencing performance: Hours Studied, Attendance, Assignments Completed
- Visualizations confirm model reliability and feature importance

---

## **Technologies & Libraries**
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## **Usage**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-performance-prediction.git
