
<img src="healthy.png" width="1000">


# 🍽 Tasty Bytes Recipe Popularity Prediction Project🍴

## 📌 Overview

Welcome to the Tasty Bytes Recipe Popularity Prediction project! Our main objective is to predict recipes that will boost our website's traffic and ensure that these selections are correct 80% of the time.


<img src="website.png" width="1000">


## 🏢 Background

Founded in 2020, Tasty Bytes emerged during the Covid Pandemic as a beacon for food enthusiasts. Initially introduced as a recipe search engine, it later transitioned into a comprehensive culinary platform offering tailored meal plans. With the right recipe displayed on the homepage, we've seen traffic boosts of up to 40%, leading to higher subscription rates. Your role? Use data science magic to predict these traffic-boosting recipes!

## 🎯 Challenge

Predict recipes that lead to high traffic.
Aim for 80% accuracy in these predictions.
Craft and showcase a presentation with your findings and recommendations for the product team.
Compile a detailed report capturing your analytical journey, including the code, thought process, and decision-making narrative.

## 📊 Data Preparation:
- The data was meticulously cleaned, encoded, and prepared for modeling.
- Handling outliers and imputing values were executed based on well-thought-out strategies.

## 🤖 Model Development:
- **Baseline Model:** Logistic Regression was chosen as the baseline model due to its simplicity and interpretability for binary classification tasks.
- **Comparison Model:** Multiple models including a Voting Classifier and H2OGradientBoostingEstimator were explored.
- **Final Model:** The Extra Tree Classifier emerged as the superior model, showcasing excellent performance and efficiency.

## 📈 Model Evaluation:
- The evaluation phase employed key metrics like F1-Score, ROC-AUC, Precision, and Recall for a thorough evaluation.
- The Extra Tree Classifier excelled in most metrics and was chosen for production deployment.
  
## 💡 Recommendations:
- **Category Optimization:** It's advisable to minimize the display of categories negatively correlated with high traffic (e.g., beverages, chicken, breakfast), and instead, showcase more recipes from categories positively correlated with high traffic (e.g., potato, vegetables, pork, and high-protein recipes).
- **Difficulty Level:** Recipes with a slightly higher level of difficulty also show a positive correlation with high traffic, indicating a potential user preference for more challenging recipes.
- **Data Collection:** Collecting a larger dataset is recommended to bolster the model's accuracy.

## 🔮 Future Steps:
- Collecting a larger dataset to improve model accuracy.
- Engage in further analysis to continue enhancing recipe traffic prediction.

## 📜 Conclusion:
The project navigated from data preprocessing to model evaluation meticulously, leading to the selection of the Extra Tree Classifier for predicting high traffic recipes. The structured approach adopted not only meets the goal of accurately predicting high traffic recipes but also sets a pathway for future machine learning tasks within this domain. The recommendations provided aim to optimize the content showcased to users, enhancing user engagement and traffic on Tasty Bytes.


## 💻 Technology Stack 💻

Here's the list of primary libraries and tools utilized in this project, organized and categorized for better understanding:

### 📊 Data Manipulation and Analysis:
- **Pandas**: For data manipulation and analysis.
- **Numpy**: For numerical operations.

### 🎨 Data Visualization:
- **Matplotlib**: For plotting and data visualization.
- **Seaborn**: For statistical data visualization.

### 📈 Statistical Analysis:
- **Scipy**: For statistical analysis and hypothesis testing.

### 🤖 Machine Learning and Model Evaluation:
- **Scikit-Learn**: For various machine learning algorithms, model evaluation, and data preprocessing.
- **XGBoost**: For gradient boosting framework that provides an efficient implementation of this model.
  
### 🌲 Ensemble Methods:
- **ExtraTreesClassifier**: For implementing the Extra Trees algorithm.
- **RandomForestClassifier**: For implementing the Random Forest algorithm.
- **VotingClassifier**: For implementing the Voting Classifier algorithm.
- **GradientBoostingClassifier**: For implementing the Gradient Boosting algorithm.

### 🔄 Model Optimization:
- **GridSearchCV**: For hyperparameter tuning and model selection.

### 🌐 Auto Machine Learning:
- **H2O**: For automatic machine learning.

This structured list provides a clear depiction of the libraries and tools harnessed for different aspects of the project, making it easy to understand the technological foundation upon which the project is built.


## Authors ✍

Stephanie Gessler: https://github.com/steguess


<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/steguess"><img src="https://avatars.githubusercontent.com/u/86976901?v=4" width="100px;" alt="Stephanie Gessler"/><br /><sub><b>Stephanie Gessler</b></sub></a><br /><a href="https://github.com/codesandbox/codesandbox-client/commits?author=steguess" title="Frontend Developer">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

