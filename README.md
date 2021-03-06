# Tanzania Water Pumps

# 1. Predicting Functional Status of Water Pumps in Tanzania

### In this project, I will apply Machine Learning predictor models to train the classifiers on the known labels and make predictions on the functional status of water pumps with unknown status.

# 2. Business Problem

### The majority access to clean water in Tanzania, it is through Water Pumps. According to 2015 Tanzania Water Point Mapping Data a significant portion of these water points are non-functional. 

### The Goal of these predictions is to decreases the overall cost for the Tanzanian Ministry of Water.

# 3. Data

### These data were collected from Driven Data and it is available here:

### https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/
 
### The dataset has about 59 thousand values and 39 variables.These data were analyzed based on parameters including: 

* Construction Year;
* Funder;
* Installer;
* Etc.

# 4. Methods and Models

### I decided to use multiple Machine Learning models to compare the results, which inclued:

* DecisionTreeClassifier
* RandomForestClassifier
* BaggingClassifier
* DecisionTreeClassifier
* AdaBoost
* GradientBoost
* XGboost (Final)

### I have also applied method such as:

* Confusion Matrix 
* ROC CURVE
* Parameter Grid Search

# 5. Final Results 

### After carefully analyzing the results, I decided to use XGboost as my predictor 

#### We achieved a final prediction accuracy of 0.79 for our test data, indicating predictions of functional status will on average be 79% correct.

# 6. Future Work 

#### To have a better predictor, we possible could have more accurate data with less unknown and NaN values
#### We could have a better data collection of the construction year, to undarstand the water pump lifetime
