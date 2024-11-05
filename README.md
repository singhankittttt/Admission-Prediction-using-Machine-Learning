# Admission-Prediction-using-Machine-Learning
<p>
  1. Objective: 
  -> The project aims to predict the likelihood of a student's admission to various colleges based on their academic metrics and rankings.

2.Data Used:

. The dataset includes columns such as:
. 10th Marks: Scores in 10th-grade exams.
. 12th Marks: Scores in 12th-grade exams.
. 12th Division: Division ranking in 12th grade.
. AIEEE Rank: All India Engineering Entrance Examination rank.
. College: Target label for predicting which college the student may get admitted to.

3.Data Preprocessing:

. The data is preprocessed by encoding categorical variables (like college names) and separating features (X) and target labels (y).
. Label encoding is used to convert college names into numerical codes for compatibility with machine learning models.

4.Exploratory Data Analysis (EDA):

. Visualization techniques (e.g., histograms and density plots) are used to analyze the distribution of student marks and ranks.
. Plots are created for features like 10th marks, 12th marks, 12th division, and AIEEE rank.

5.Machine Learning Models Used:

. XGBoost Classifier: A gradient boosting classifier, tuned for multi-class classification, to predict admission probability across multiple colleges.
. Decision Tree Classifier: A simpler model used as an alternative to XGBoost for comparison of accuracy and efficiency.

6.Model Evaluation:

. Models are evaluated based on their accuracy scores on the test data.
. The Decision Tree Classifier achieved a higher accuracy (96%) compared to the XGBoost Classifier (75%).

7.Prediction Functionality:

. The project includes functionality to predict college admission based on user-inputted academic details.
. For example, based on inputs like 10th and 12th marks, division, and AIEEE rank, the model predicts the probable college for admission.

8.Results Visualization:

. The project uses a confusion matrix to compare predicted versus actual outcomes, allowing
  for a visual understanding of model performance across colleges.
  
9. Libraries and Tools:

 -> The project utilizes several Python libraries, including:
   . pandas and numpy for data handling.
   . matplotlib and seaborn for visualization.
   . scikit-learn for model building and evaluation.
   . XGBoost for implementing the XGBoost Classifier.
   
10. Conclusion:

. The project demonstrates a machine learning approach to predict college admissions based on academic records.
. It highlights the comparison between different models and shows how these predictions
  can aid in decision-making for prospective students.
</p>
