# Red Wine Quality Analysis  

![intro-1705570360](https://github.com/user-attachments/assets/151445aa-96c0-41fd-aa07-e2b4f4920c69)
- ![Image from](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.foodrepublic.com%2F1495854%2Fhow-long-unopened-red-wine-lasts%2F&psig=AOvVaw0pZrmdaFYvAHf-mZRoZQ63&ust=1739105109136000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCJjRp8WNtIsDFQAAAAAdAAAAABAE)

This project focuses on analyzing the quality of red wine using a dataset that includes various physicochemical properties and quality ratings. The primary objective is to identify key factors that influence wine quality and to develop predictive models that can estimate quality based on these attributes.

## Key Features:
- **Dataset**: The analysis utilizes a publicly available dataset containing attributes such as acidity, sugar, pH, alcohol content, and more, along with quality ratings on a scale from 3 to 8. 
  - [Dataset Link](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv)
  - 
| Attribute                | Description                                                                                                   |
|--------------------------|-------------------------------------------------------------------------------------------------              |
| **Fixed Acidity**        | The non-volatile acids in wine, primarily tartaric acid, which contribute to the wine's taste.                |
| **Volatile Acidity**     | The amount of acetic acid in wine, which can affect the aroma and flavor; high levels can indicate spoilage.  |
| **Citric Acid**          | A weak acid that can enhance freshness and flavor; often added to improve taste.                              |
| **Residual Sugar**       | The amount of sugar remaining after fermentation, which can affect sweetness and body.                        |
| **Chlorides**            | The level of salt in the wine, which can influence taste and mouthfeel.                                       |
| **Free Sulfur Dioxide**  | The amount of sulfur dioxide that is available to act as a preservative and antioxidant.                      |
| **Total Sulfur Dioxide** | The total amount of sulfur dioxide in the wine, including both free and bound forms.                          |
| **Density**              | The mass per unit volume of the wine, which can indicate sugar and alcohol content.                           |
| **pH**                   | A measure of acidity or alkalinity; affects taste, stability, and color of the wine.                          |
| **Sulphates**            | The level of sulfates, which can enhance flavor and stability; often associated with dryness.                 |
| **Alcohol**              | The percentage of alcohol by volume, which contributes to the body and flavor of the wine.                    |
| **Quality**              | A subjective rating of the wine's overall quality, typically on a scale from 3 to 8.                          |

    
- **Exploratory Data Analysis (EDA)**: Initial exploration includes visualizations and statistical summaries to understand the distribution of features and their relationships with wine quality.
- **Feature Engineering**: Relevant features are selected and transformed to enhance model performance.
- **Modeling**: Various machine learning algorithms, including regression and classification techniques, are employed to predict wine quality. Model performance is evaluated using metrics such as accuracy.
- **Insights**: The analysis reveals significant correlations between certain physicochemical properties such as citric acid, fixed acidity, density, total sulfur dioxide, and free sulfur dioxide and wine quality, providing valuable insights for winemakers and consumers alike.

This project serves as a comprehensive study of red wine quality, combining data analysis and machine learning to uncover patterns and make predictions.
