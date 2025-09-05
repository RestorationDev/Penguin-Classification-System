# Penguin Classification and Analysis 

This project analyzes the Palmer Penguins dataset to explore species differences and build predictive models. It combines statistical tests, visualization, and machine learning for a complete workflow.

Key Steps

	•	Data Cleaning: Removed irrelevant columns, handled missing values, and encoded categorical features.
	•	Exploratory Analysis:
	•	Grouped statistics by island and species
	•	Scatterplots, histograms, boxplots, and 3D visualizations
	•	Correlation heatmap to identify relationships between features
	•	Statistical Tests:
	•	ANOVA (Analysis of Variance): Confirmed significant differences between species for culmen length/depth, flipper length, and body mass.
	•	Feature separation scores to select best predictors.
	•	Machine Learning Models:
	•	Logistic Regression – accuracy ~97%
	•	k-NN Classifier – tuned with cross-validation, accuracy ~93%
	•	Support Vector Machine (SVM) – grid search for optimal C, accuracy ~97%
	•	Decision region plots to visualize model boundaries per island

Highlights

	•	ANOVA showed species differ significantly in key body measurements.
	•	Regression and classifiers achieved strong performance in predicting species.
	•	Demonstrates a pipeline from data cleaning → visualization → statistical testing → ML modeling.
