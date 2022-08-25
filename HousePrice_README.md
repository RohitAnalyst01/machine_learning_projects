**ABOUT**

This prediction model is done on USA House Price data which is a csv file and attached in this repository. The focus of this project is to get predictions from our model i.e. House Price
from existing features i.e. 'Avg. Area Income', 'Avg. Area House Age', 'Avg. Area Number of Rooms','Avg. Area Number of Bedrooms', 'Area Population', 'Price', 'Address'. Stages like data cleaning and wrangling was eliminated from the process as the dataset was already trailored so, that the machine learning models can fits well.

**LIBRARIES USED**

* Sickitlearn (Sklearn): Its a machine learning library used for classification, regression, data manipulation etc. In this project, it was used to deploy the linear regression model and evaluation of models.
* Matplolib and Seaborn: Graphical modules used for the visualization. In this project scatter plot was used to visualize the correlation between test data and calculated prediction data. Also, Distplot was also used for distribution of the residuals or differece between the predicted and test data to evaluate the models.
* Pandas: used for reading the dataset file.
* NumPy: used to data manipulation.

**Conclusion**

the linear regression model works well as the difference between both values ie. test and predicted were less and shows a normal or gaussian curve. Also, while plotting on scatter graph, the datapoints aligned in the straight line which prooves the linear relationship. Furthermore, the evaluation matrics shows ie, absolute mean error (82288.22251914942), mean squared error (102278.82922290897), square root mean squared error the result of 10460958907.208977 whic depicts the performace of the model.
