Predicting the outcome of football matches and optimizing team strategy; a machine learning approach 

Project Overview

This repository focuses on predicting the outcomes of English Premier League (EPL) matches using machine learning models. The project utilizes two different datasets to explore which features are important in predicting the outcome of EPL matches (either match outcome or team performance) and how feature selection impacts the performance of various machine learning models. By carefully selecting the most relevant features, this project aim to evaluate the performance of four different machine learning models (random forest, SVM, logistic regression and MLP) for match outcome predictions.

Installation Instructions
1.	Set up Jupyter Notebook or any Python IDE to run the .ipynb files.
2.	Install the required packages (libraries)
Usage Instructions
1.	Open the Notebooks:
o	To work with Dataset A, open Mariam prediction 2.ipynb.
o	To work with Dataset B, open My Project Notebook.ipynb.
2.	Run the Cells: Execute the cells sequentially to preprocess the data, select the most relevant features, train the models, and evaluate the performance.
3.	Experimentation: the EDA, feature selection methods, models, or parameters can be adjusted to explore different outcomes and refine the predictions.
   
Project Details

Dataset A

•	Notebook: My Project Notebook.ipynb

•	Data: This dataset comprises 10 seasons of historical EPL match statistics starting from 2014/2015 to 2023/2024, with an emphasis on match outcome metrics like goals, corners, cards, half-time results, full-time results and referees.

•	Models Used: Random Forest, Logistic Regression, SVM, and MLP.

•	Feature Selection: Focuses on identifying and selecting the most influential features that contribute to accurate match outcome predictions. 

•	Evaluation metrics: the metrics used in assessing the performance of the models include Accuracy, Precision, Recall, F1 Score, and AUC-ROC.

Dataset B

•	Notebook: My Project Notebook 2.ipynb

•	Data: This dataset was sourced from Kaggle, where it is available as part of a collection of football match data covering the top five European football leagues (EPL, La Liga, Serie A, Bundesliga, Ligue 1) from 2014/2015 to 2022/2023 season. This dataset includes 16,332 matches and 54 features, providing complete information on team performance, such as team names, scores, expected goals (xG), defense, midfield, attack, formation and team standing.

•	Models Used: Random Forest, Logistic Regression, SVM, and MLP.

•	Feature Selection: Concentrates on selecting features related to team form, standings, and contextual match information to improve prediction accuracy.

•	Evaluation metrics: the metrics used in assessing the performance of the models include Accuracy, Precision, Recall, F1 Score, and AUC-ROC.

Results

•	Dataset A: The Random Forest model achieved the highest accuracy, underscoring the importance of selecting key team metrics for improved predictions.

•	Dataset B: The Random Forest model again proved to be the most accurate, demonstrating the value of focusing on team performances during feature selection.

•	However, all models performed better with dataset B compared to A demonstrating that team performance features such as attack, defense and midfield are crucial in the outcome of football matches and can be used in optimising team strategy.

Contributing

Contributions to this project are welcome. Please modify the notebooks as needed and share improvements.
