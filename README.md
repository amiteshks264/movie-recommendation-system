# movie-recommendation-system

This is a movie recommender model developed using Machine Learning.

The ML model can be seen in the .jpynb file.

The steps involved in developing the model were :--
1) Importing the required libraries
     (a) numpy
     (b) pandas
     (c) sklearn
     (d) nltk

2) Importing the dataset
3) Data pre-processing which involved data cleaning and data merging .
4) For the data to be fed to the ML algorithm data vectorization is done.
5) Now the recommendation for the movies are given based on cosine distance between the vectors.

Now we developed a website form of the model to present its working using Pycharm in which the libraries used were streamlit , pandas , pickle and requests.
In that we made use of tmdb API to fetch the posters of the movies.

The python code for the website can be seen in the .py file.

Here are a few visuals of the working of the website:--

The website looks as follows--
<img width="756" alt="image" src="https://github.com/amiteshks264/movie-recommendation-system/assets/105868193/1a899f20-77d5-4150-a4ea-195fe0eceded">

When one clicks on the movie name the list appears from where the movie can be selected for which the recommendation are to be made--
<img width="734" alt="image" src="https://github.com/amiteshks264/movie-recommendation-system/assets/105868193/c215c678-199d-4555-be64-d256c6347cb1">

When you click on the recommend button the results are displayed as shown--
