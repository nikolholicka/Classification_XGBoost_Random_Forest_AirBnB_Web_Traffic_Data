# Classification Project with Airbnb data

### Which users are going to book a stay?

### Deliverables
* Jypyter Notebook
* Blogpost: [Evaluating Classification models](https://medium.com/@nikolh92/evaluating-classification-models-handy-function-for-diagnostics-b122f18ea03d)


### 1. About this project

Predicting whether new AirBnB users will make a booking based on their website behaviour with classification algorithms. Data was provided by AirBnB for Kaggle competition.

### 2. About the dataset

This dataset describes the users who made accounts on AirBnb between 2010 and 2014. It comes from a Kaggle competition. The data describes information gathered by website cookies, such as what browser and device the users are using as well as how they behave on the website, such as searching, viewing pages and using filters. 

### 3. Project objective

The aim of this project is to use classification models to predict whether a user will make a booking or not, based on the website browsing data, affiliate marketing and demographic information contained in the dataset.

The use of such classifier would be to improve targeted marketing in order to increase revenue for Airbnb, as well as provide insight into what makes users make a booking.

### 4. Notebook overview

1) Data exporation, joining tables, cleaning data
2) EDA - data exploration and visualisation
3) Upsampling data with SMOTE
4) PCA - feature reduction
5) Modelling - Random forest (baseline model), XGBoost, AdaBoost
6) Validating best performing model