# Forecasting Pizza Prices using Predictive Analytics
This project aims to forecast pizza prices using multiple linear regression, decision tree and random forest models. The project focuses on developing accurate prediction models by analyzing various factors such as diameter, topping, size, company, extra cheese, extra mushrooms and extra sauce. The data is pre-processed and analyzed to identify patterns and features that can be used to predict pizza prices accurately. The performance of the models is evaluated using standard regression metrics such as mean absolute error, mean squared error, root mean squared error, training score and testing score. The results of the project will be helpful for the pizza industry to predict prices accurately and make informed business decisions. 

# Table of Contents
-  [General Info](<#general-information>)
-  [Technologies Used](#technologies-used)
-  [Setup](#setup)
-  [Features](#features)
-  [Usage](#usage)
-  [Project Status](#project-status)
-  [Room for Improvement](#room-for-improvement)

# General Information
The food industry has been growing rapidly in recent years, with various companies competing to provide customers with the best quality products at an affordable price. The problem addressed in this project is the difficulty that pizza restaurant owners and managers face in determining the optimal price for their products due to the various factors that affect pizza prices. In addition to providing insights on the key factors that contribute to pizza prices, this project also aims to develop accurate predictive models for forecasting prices. By leveraging machine learning algorithms such as Random Forest, Decision Tree and Multiple Regression, we can build models that take into account various criteria such as pizza diameter, topping, variants and size and accurately forecast prices.

# Technologies Used
Python libraries: Scikit-learn, Numpy, Pandas, Matplotlib, Seaborn, Statmodels, Yellowbrick

# Setup
The project requirements/dependencies are listed in the import statements at the beginning of the code:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - sklearn
  - Statmodels
  - Yellowbrick

To set up your local environment and get started with the project, you need to follow these steps:

1. Install Python on your computer if you haven't already done so. You can download Python from the official website:https://www.python.org/downloads/.
   
2. Open a command prompt or terminal window and navigate to the directory where you want to store the project files.

3. Clone the project repository using Git or download the project files directly from the repository.

4. Install the required dependencies by running the following commands in your command prompt or terminal window: pip install numpy pandas matplotlib seaborn sklearn statmodels yellowbricks.

5. Once the dependencies are installed, you can open the Jupyter Notebook file containing the project code and run the code cells to execute the project.

# Features
  - The Random Forest Regression’s accuracy is 93% for the data. Also, the MAE score is very low, which means that it is the best model to choose when compared to the other two models.
  - In Decision Tree, this method is overfitted as it got more accuracy in train data and lower in test data.
  - In the pizza price prediction dataset, attribute such as diameter is the important factor in the increase of pizza price. Other attributes like variant, extra_cheese, extra_mushrooms and extra_sauce are the other factors affecting the prices too.

# Usage
This analysis provides useful insights for the pizza companies to set optimal prices and improve their sales strategies. Companies can use this information to understand customer preferences and adapt their pricing and product offerings accordingly. For instance, they can consider offering more chicken toppings, which are the most popular and adjust the pricing of their toppings to align with customer demand. Additionally, they can focus on promoting the most popular pizza variants such as meat lovers and double mix pizzas. Finally, it is essential for companies to keep an eye on their prices and the prices charged by their competitors to remain competitive in the market.

# Project Status
Project is: Complete

# Room for Improvement
To further improve the forecasting of pizza prices using predictive analytics, several aspects can be considered. Firstly, incorporating additional features such as location, seasonality, customer demographics and promotional activities could enhance the accuracy of the models. Secondly, collecting more comprehensive and high-quality data from diverse sources and expanding the time period covered can provide a better understanding of the market. Exploring advanced modeling techniques like ensemble methods or deep learning algorithms could potentially improve prediction accuracy. Lastly, conducting thorough model evaluation and comparison using different performance metrics can validate the models and guide decision-making. By addressing these areas, the project can enhance its predictive capabilities and provide valuable insights for pricing strategies in the pizza industry.
