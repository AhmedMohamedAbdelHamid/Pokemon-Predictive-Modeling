# Pokémon Predictive Modeling (PPM)
The Pokémon Predictive Modeling (PPM) project is a robust machine learning initiative aimed at exploring the rich Pokémon dataset and predicting various aspects such as type, combat effectiveness, and evolution patterns. It serves as an engaging blend of data science, predictive analytics, and the beloved Pokémon universe.

This project was provided by the Arab Academy for Science, Technology and Maritime Transport (AAST).

# Features
- Comprehensive Dataset Analysis:
Detailed exploration of Pokémon attributes, including type, stats, and combat data.

- Type Prediction Models:
Machine learning models to predict Pokémon types based on attributes like attack, defense, and speed.

- Statistical Predictions:
Predict Pokémon base stats (e.g., HP, Attack) using regression techniques.

- Clustering and Grouping:
Uncover hidden patterns and clusters among Pokémon based on similarity in stats and characteristics.

- Interactive Visualizations:
Insights made accessible through interactive plots and graphs.

- Scalable and Modular Design:
Python scripts and notebooks for preprocessing, model training, and evaluation, designed to be modular and reusable.

# Database Schema
While this project focuses on predictive modeling, the dataset can be conceptualized as including the following key attributes:
- Pokémon ID & Name: Identifiers for unique Pokémon.
- Types (Primary/Secondary): Categorization of Pokémon into one or two types.
- Stats: Numerical attributes like HP, Attack, Defense, Speed, etc.
- Generation: Specifies the game generation a Pokémon belongs to.
- Legendary Status: Indicates whether a Pokémon is legendary.

# Responsibilities
1- Data Loading and Handling:

- Used pandas for data manipulation, including loading, cleaning, and preparing the Pokémon dataset for analysis and modeling.

2-Data Visualization:

- Utilized matplotlib.pyplot to create plots for exploratory data analysis (EDA), revealing trends, correlations, and insights in the dataset.

3- Data Preprocessing:

- Applied LabelEncoder to convert categorical variables (e.g., Pokémon types) into numeric format suitable for machine learning models.

- Standardized numerical features (e.g., stats like HP, Attack, Defense) using StandardScaler to improve model performance.

4- Feature Selection and Model Design:

- Implemented Lasso Regression for feature selection, identifying the most significant predictors while reducing overfitting.

5- Dataset Splitting:

- Used train_test_split to divide the dataset into training and testing subsets for unbiased model evaluation.

6- Model Training and Evaluation:

- Trained machine learning models and evaluated performance using metrics like accuracy, calculated with accuracy_score.

7- Pipeline Integration:

- Combined data preprocessing, feature engineering, and model training into a streamlined and reproducible workflow for predictive analysis.

# Dataset Overview
This project uses a Pokémon dataset comprising information on over 800 Pokémon. The dataset contains attributes such as name, type(s), base stats, and generation. It provides a perfect sandbox for implementing and evaluating various predictive models.

Source: Kaggle (https://www.kaggle.com/datasets/abcsds/pokemon)

Size: ~800 entries.

# License
None
