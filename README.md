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
The dataset has **74112 rows** and **29 columns** which includes many features such as: number of beds, number of guests allowed, description, number of reviews, and many more. For a more detailed preview into the features and the data, see the dataset [here](https://www.kaggle.com/datasets/stevezhenghp/airbnb-price-prediction)

## 📑 **Data Dictionary**
  - **id** : Unique identifier for each Airbnb listing.
  - **log_price** : Logarithm of the price of the listing. It's common to use the logarithm 
                    to handle skewed price distributions.
  
  - **property_type** : Type of property.
  - **room_type** : Type of room available.
  - **amenities** : List of amenities provided.
  - **accommodates** : Number of guests that can be accomodated.
  - **bathrooms** : Number of bathrooms.
  - **bed_type** : Type of bed available.
  - **cancellation_policy** : Policy outlining the cancellation terms.
  - **cleaning_fee** : Fee charged for cleaning.
  - **city** : City where the Airbnb listing is located.
  - **description** : Textual description og the listing.
  - **first_review** : Date of the first review.
  - **host_has_profile_pic** : Binary indicator of whether the host has a profile picture.
  - **host_identity_verified** : Binary indicator of whether the host's identity is verified.
  - **host_response_rate** : Percentage of time the host responds to inquiries.
  - **host_since** : Date when the host joined Airbnb.
  - **instant_bookable** : Binary indicator of whether instant booking is available.
  - **last_review** : Date of the most recent review for the listing.
  - **latitude** : Geographic latitude of the listing.
  - **longitude** : Geographic longitude of the listing.
  - **name** : Name or title of the listing.
  - **neighbourhood** : Neighbourhood where the listing is located.
  - **number_of_reviews** : Total number of reviews for the listing.
  - **review_scores_rating** : Numeric rating summarizing the overall guest satisfaction.
  - **thumbnail_url** : URL of the thumbnail image of the listing.
  - **zipcode** : Postal code of the location of the listing.
  - **bedrooms** :  Number of bedrooms.
  - **beds** : Number of beds.

## 📈 **Model**
The business question falls into the category of supervised machine learning for predicting continuous values, so linear regression models were used.

## 🚀 **Getting Started**
If you would like to download and run all the data analysis and prediction models on your own machine, it is recommended to use to **Anaconda** and **Jupyter Notebook**. If you use Anaconda most of the packages used in this project are pre-installed.

## 🛠️ **Built With**
  - [Python 3](http://www.python.org/) - Main programming language used, done in Jupyter Notebook.
  - [Pandas](https://pandas.pydata.org/) - Main library used to manipulate the datasets.
  - [Scikit-learn](https://scikit-learn.org/stable/) - Main library used for machine learning.
  - [Matplotlib](https://matplotlib.org/) - Used for graph plots and visualizations.
  - [Python NLTK](https://www.nltk.org/) - Used during exploratory analysis to get further insights into the textual data.

## 🪪 **License**
This project is licensed under the [License](https://opensource.org/license/mit)



