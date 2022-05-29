<p align="center">

  <a href="" target="https://movies-res.herokuapp.com/">
    <img alt="Moonlit-Cinema-logo" height="150" alt="Moonlit-Cinema Logo" src="https://github.com/shaikharyan/movie/blob/main/media/mountain%20cinema%20film%20movie%20simple%20logo%20template%20.png/>
    <h1 align="center">Moonlit_Cinema</h1>
  </a>
  
</p>
<p align="center">
    <a href="(https://www.notion.so/Engage-Mentorship-Programme-0ac44abbe8894e1cb7792493aee5e4ce)">Documentation</a>
</p>
<p align="center">

  </a>
  <img src="https://img.shields.io/badge/Python-3.9-blueviolet" alt="Python">
  <img src="https://img.shields.io/badge/Framework-Flask-red" alt="Framework">
  <img src="https://img.shields.io/badge/Frontend-HTML/CSS/JS-green" alt="FrontEnd">
  <img src="https://img.shields.io/badge/API-TMDB-fcba03" alt="API">
</p>

<div align="center">
  </div>
It is a Moonlight themed Movie Recommender System based on Content Filtering using Machine Learning Model. This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews, recommended movies, etc. 

The movies can be easily found by using the auto-suggestion feature, which can handle and complete the trail of movie even with some typos. The results include a holistic review of the movie along with the sentiment analysis of the comments.



## Link to the application

Check out the live demo: https://movies-res.herokuapp.com/

Start by typing the movie you are looking for! Pick and Choose from the auto-suggestions.💬
Let us complete it for you! You will be good to go even though if you made some typo errors.
![Moonlit-Cinema demo](https://github.com/shaikharyan/movie/blob/main/media/Screenshot%202022-05-28%20at%208.46.18%20PM.png)
The results show the movie details along with Recommended Movies based on the selection. There are tags and genres into which each item is categorised by.
![Moonlit-Cinema demo](https://github.com/shaikharyan/movie/blob/main/media/Screenshot%202022-05-28%20at%208.46.56%20PM.png)

## 'Invalid Request' Error

If you're getting invalid request error in your application, kindly delete the browser cache and retry

## API 

The details of the movie are fetched through an API by TMDB, the movies can be tracked through their IMDB id. `beautifulsoup4` was used to get the reviews from the site by doing web scraping, the reviews are then feeded to the sentiment analyser.
I have not replaced my api key in the app for demonstration purpose.

## How to get the API key?

Create an account in https://www.themoviedb.org/, click on the `API` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your `API` sidebar once your request is approved.

# Features

Get Movie Recommendations with:

- Movie Details(overview, genre, release date, rating, runtime, top cast)
- Sentiment Analysis
- Content based Recommendation
- Auto-Suggested search Engine
- Speacial Moonlit Theme

Comments, Reviews, Rating, Recommendation, Suggestions all in One. Everything about a movie and more. 

# Getting Started

1. Clone this repository in your local system or download as zip and unpack the folder.
2. Install all the libraries mentioned in the [requirements.txt](https://github.com/shaikharyan/movie/blob/main/requirements.txt) file with the command `pip install -r requirements.txt`.
3. Replace YOUR_API_KEY in **both** the places (line no. 23 and 43) of `static/recommend.js` file.
4. Open your terminal/command prompt from your project directory and run the `main.py` file by executing the command `python main.py`.
5. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
6. Hurray! That's it.

### Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)


## Submit a feature request

If a similar feature request already exists, don't forget to leave a "+1".
If you add some more information such as your thoughts and vision about the feature, your comments will be embraced warmly :)


