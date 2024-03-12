# movie-recommendation-system

This is a movie recommender model developed using Machine Learning.

The ML model can be seen in the .jpynb file.

The steps involved in developing the model were :--
1) Data Preparation:
     Imported necessary libraries: NumPy, Pandas, Scikit-learn, and NLTK.
     Loaded and preprocessed the dataset, including data cleaning and merging.
2) Feature Engineering:
     Vectorized data for ML algorithms.
3) Algorithm Implementation:
     Utilized cosine distance between vectors to recommend movies.
4) Web Interface:
     Created a user-friendly website using Streamlit, Pandas, Pickle, and Requests.
     Integrated the TMDB API to fetch movie posters.

The python code for the website can be seen in the .py file.

Here are a few visuals of the working of the website:--

The website looks as follows--
<img width="667" alt="image" src="https://github.com/amiteshks264/movie-recommendation-system/assets/105868193/7800c9e2-d344-4cf1-b37a-3c1077d10769">


When one clicks on the movie name the list appears from where the movie can be selected for which the recommendation are to be made--
<img width="629" alt="image" src="https://github.com/amiteshks264/movie-recommendation-system/assets/105868193/22cc59bf-8ad9-4489-a2d5-6f9de41e37bc">


When you click on the recommend button the results are displayed as shown--
