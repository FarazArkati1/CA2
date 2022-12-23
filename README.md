# The-Movie-Cinema

![Python](https://img.shields.io/badge/Python-3.8-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML/CSS/JS-green)
![API](https://img.shields.io/badge/API-TMDB-fcba03)

This program offers all the requested information about the desired movie, including a synopsis, the genre, the release date, the rating, the length, the top cast, reviews, suggested viewings, etc.


The movie information (title, genre, runtime, rating, poster, etc.) is retrieved using an API by TMDB, available at https://www.themoviedb.org/documentation/api. Using the IMDB id of the film in the API, I performed web scraping to obtain the user reviews submitted to the IMDB site using the user ID "beautifulsoup4". I then conducted sentiment analysis on those reviews.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using `beautifulsoup4` and performed sentiment analysis on those reviews.

## Link to the application

Don't worry if the movie that you are looking for is not auto-suggested. Just type the movie name and click on "enter". You will be good to go even though if you made some typo errors.

## 'Invalid Request' Error

## How to get the API key?

Create an account at https://www.themoviedb.org, select the 'API' link from the left sidebar in your account settings, then fill out all the necessary information to request an API key. If prompted for the website URL, simply respond "NA" if you don't know it. When your request is accepted, the API key will appear on your "API" sidebar.

## How to run the project?


1. Create a local copy of this repository.
2. Use the command "pip install -r requirements.txt" to install every library listed in the [requirements.txt] file.
3. Replace my_api_key in **both** the places (line no. 23 and 43) of `static/recommend.js` file.
4. The command "python main.py" may be used to launch the "main.py" file from your project directory's terminal or command prompt.

1. Clone this repository in your local system.
2. Install all the libraries mentioned in the file with the command `pip install -r requirements.txt`.
3. Replace YOUR_API_KEY in **both** the places (line no. 23 and 43) of `static/recommend.js` file.
4. Open your terminal/command prompt from your project directory and run the `main.py` file by executing the command `python main.py`.

5. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.

### Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

