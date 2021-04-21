# Goal
The goal is to build serveral data visualizations and ML models that can predict used car pricing. The ML models are then compared with each other on accuracy and parsimony. 

# Data
The dataset is scraped from web used car listings. The rows are around 1,000. There are 45 car features such as year, make, model, mpg, horsepower, int color, ext color, AWD etc.

# Language and Main Libraries
R is the language used in this analysis.\
\
Hmisc, dplyr, ggplot2, caret, randomForest, caTools are the main libraries used.

# KNN Imputation
There were many missing values in original columns such as mpg and horsepower. Decided to use KNN imputations to fill in the missing values.
Intuitively, a BMW 3 series should have similar mpg/horsepower to another 3 series, if they are similar in other dimensions.

# Data Visualization
I used ggplot2 to make some data viz before jumping into ML.\
\
1: Boxplot of different BMW model pricing:  https://ibb.co/n1wCgMn \
2: Depreciation trend line:  https://ibb.co/PCpHCWN  \
3: Price and Mileage correlation:  https://ibb.co/X3RVb6y \
4: Inventory Distribution by Car Year:  https://ibb.co/w40vzyP \
5: Price Against Imperfections:  https://ibb.co/PFHsrtt

# Random Forest Model
