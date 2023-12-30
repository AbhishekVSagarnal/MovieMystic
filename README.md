# MovieMystic
MovieMystic: Intelligent Movie Recommendation System -->
MovieMystic is an advanced movie recommendation system designed to enhance your cinematic experience. Leveraging state-of-the-art algorithms, this system analyzes user preferences, genre interests, and historical viewing patterns to provide personalized movie recommendations.

Key Features:
Smart Recommendation Engine: Utilizes a powerful recommendation engine based on collaborative filtering, ensuring accurate and tailored suggestions for every user.

Diverse Movie Database: Integrates seamlessly with The Movie Database (TMDb), offering access to a vast collection of movies from various genres.

User-Friendly Interface: A sleek and intuitive web interface built with Flask and Jinja2 makes exploring and discovering new movies a seamless experience.

Machine Learning Integration: Incorporates scikit-learn for machine learning capabilities, allowing the system to continuously adapt and improve recommendations based on user feedback.

Natural Language Processing: Implements NLTK for natural language processing, enhancing the system's understanding of user preferences and movie characteristics.

![Python](https://img.shields.io/badge/Python-3.8-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML/CSS/JS-green)
![API](https://img.shields.io/badge/API-TMDB-fcba03)

This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using `beautifulsoup4` and performed sentiment analysis on those reviews.

## Link to the application
If you can't find the movie you're searching for through auto-suggestions while typing, there's no need to worry. Simply type the name of the movie and press "enter". Even if you make some typos, it should still work fine.

## How to get the API key?

Create an account in https://www.themoviedb.org/, click on the `API` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your `API` sidebar once your request is approved.

## How to run the project?

1. Clone this repository in your local system.
2. Install all the libraries mentioned in the [requirements.txt](https://github.com/kishan0725/The-Movie-Cinema/blob/master/requirements.txt) file with the command `pip install -r requirements.txt`.
3. Replace YOUR_API_KEY at line no. 2 of `static/recommend.js` file.
4. Open your terminal/command prompt from your project directory and run the `main.py` file by executing the command `python main.py`.
5. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
6. Hurray! That's it.

### Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

