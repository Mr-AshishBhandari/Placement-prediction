# Placement-prediction


A machine learning project to predict student placement based on CGPA and IQ of students.



## Process for Machine learning Development life cycle
1. Data collection
2. Data preprocessing: Remove unnecessary columns, impute null values
3. EDA: Based on the data, the graph was  plotted,  gives the insight about the model to be used.
4. Scaling: Normalize the data into suitable ranges.
5. Model training: After EDA analysis , the model to be choosed is found to be linear. so, logistic regression is used as model
6. Model evaluation: The accuracy for the prediction is measured by accuracy_score
   
To use this project:

1. Clone the repository:

   ```bash
   git clone https://github.com/Mr-AshishBhandari/Placement-prediction.git
   cd Placement-prediction

2. Install the requirements:
     ```bash
     pip install -r requirements.txt

3. Run
     ```bash
     jupyter notebook model.ipynb
