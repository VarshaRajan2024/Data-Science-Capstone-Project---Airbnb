![image](https://pluspng.com/img-png/airbnb-logo-png-airbnb-logo-1600.png)



# **Airbnb Price Prediction**
What dictates Airbnb rental price in USA? Is it the
  - Number of beds?
  - Number of guests allowed?
  - Review score?
  - Cancellation policy?

## 📖 **Overview**
The business question: **What predicts Airbnb rental price in USA?**
The answer to this question provides interesting insights that can benefit a host looking to maximize their profits.

Before diving head first into the data and producing large correlation matrices, I always try to think of the question and get a sense of the features. Why am I doing this analysis? What’s the goal? What relationships between features and the target variable make sense?

## 📊 **Data**
The dataset has **74112 rows** and **29 columns** which includes many features such as: number of beds, number of guests allowed, description, number of reviews, and many more.

## 📑 **Data Dictionary**
  - `id` : Unique identifier for each Airbnb listing. (int64)
  - `log_price` : Logarithm of the price of the listing. It's common to use the logarithm to handle skewed price distributions. (float64)
  - `property_type` : Type of property. (object)
  - `room_type` : Type of room available. (object)
  - `amenities` : List of amenities provided. (object)
  - `accommodates` : Number of guests that can be accomodated. (int64)
  - `bathrooms` : Number of bathrooms. (float64)
  - `bed_type` : Type of bed available. (object)
  - `cancellation_policy` : Policy outlining the cancellation terms. (object)
  - `cleaning_fee` : Fee charged for cleaning. (bool)
  - `city` : City where the Airbnb listing is located. (object)
  - `description` : Textual description og the listing. (object)
  - `first_review` : Date of the first review. (object)
  - `host_has_profile_pic` : Binary indicator of whether the host has a profile picture. (object)
  - `host_identity_verified` : Binary indicator of whether the host's identity is verified. (object)
  - `host_response_rate` : Percentage of time the host responds to inquiries. (object)
  - `host_since` : Date when the host joined Airbnb. (object)
  - `instant_bookable` : Binary indicator of whether instant booking is available. (object)
  - `last_review` : Date of the most recent review for the listing. (object)
  - `latitude` : Geographic latitude of the listing. (float64)
  - `longitude` : Geographic longitude of the listing. (float64)
  - `name` : Name or title of the listing. (object)
  - `neighbourhood` : Neighbourhood where the listing is located. (object)
  - `number_of_reviews` : Total number of reviews for the listing. (int64)
  - `review_scores_rating` : Numeric rating summarizing the overall guest satisfaction. (float64)
  - `thumbnail_url` : URL of the thumbnail image of the listing. (object)
  - `zipcode` : Postal code of the location of the listing. (object)
  - `bedrooms` :  Number of bedrooms. (float64)
  - `beds` : Number of beds. (float64)

## 📈 **Model**
The business question falls into the category of supervised machine learning for predicting continuous values, so **Linear Regression** models are used as the baseline model. Other than that, advanced machine learning model like **Random Forest Regressor** and deep learning **Multi-Layer Perceptron/Neural Network** models are also used.

## 🚀 **Getting Started**
If you would like to download and run all the data analysis and prediction models on your own machine, it is recommended to use to **Anaconda** and **Jupyter Notebook**. If you use Anaconda most of the packages used in this project are pre-installed except the following:
 - [RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
 - Tensorflow

## 🛠️ **Built With**
  - [Python 3](http://www.python.org/) - Main programming language used, done in Jupyter Notebook.
  - [Pandas](https://pandas.pydata.org/) - Main library used to manipulate the datasets.
  - [Scikit-learn](https://scikit-learn.org/stable/) - Main library used for machine learning.
  - [Matplotlib](https://matplotlib.org/) - Used for graph plots and visualizations.
  - [Python NLTK](https://www.nltk.org/) - Used during exploratory analysis to get further insights into the textual data.

## 🪪 **License**
This project is licensed under the [License](https://opensource.org/license/mit)



