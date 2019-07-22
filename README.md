# AirBnb-Seattle-Data-Study

This repository has all the code for project which is a part of term 2 of the Udacity Data Scientist nano-degree. 

# Projects : Predicting AirBnb listing price and other insights from AirBnb Seattle data

1. Installations

    This project was written in Python, using Jupyter Notebook on Google collab. The relevant Python packages for this project are as follows:
                                                                                                         
    numpy,
    pandas,
    matplotlib,
    sklearn,
    sklearn.model_selection (train_test_split),
    sklearn.preprocessing (StandardScaler),
    sklearn.metrics (R2_Score,mean_squared_error,make_scorer),
    sklearn.linear_model (LinearRegressor),
    sklearn.SVM (SVRegressor),
    sklearn.ensemble (RandomForestRegressor),
    sklearn.model_selection (RandomizedSearchCV, GridSearchCV),
    matplotlib.pyplot (plt),
    seaborn,
    nltk (vader_lexicon, SentimentIntensityAnalyzer),
    collections(counter),


2. Project Motivation

    Seattle AirBnB Dataset contains data about AirBnB listings in Seattle, calendar availability for each of these listings as well as user reviews on the listings. Using this dataset, I am going to attempt to answer the following business questions.

        a. Can we predict listing price using the available host and property information ?
        b. Can we find out the most important drivers to listing price?
        c. Are the factors influencing price also influence reviews?

3. File Descriptions

    This repo contains two files, called AirBnb_Seattle_Project.ipynb that contains the code and its html file. The blog post can be found [here](https://medium.com/akhil-anurag/seattle-airbnb-price-predictions-7966f0966940?)
    
4. Summary Result: 

    Analyzing the Seattle data, we can conclude:
    
        a. AirBnb listing price can be predicted using host and property features. Although we are able to get a model which can predict listing price, but there is room to improve this model further to support hosts and homeowners in deciding the best price
        b. Neighborhood groups play an important role in price determination along with property space
        c. Customer comments on the property is not determined by the factors which determines listings prices.

5. Licensing, Authors, Acknowledgements, etc.

    Seattle AirBnB data was obtained from Udacity. Other references are cited within the notebook.
