# Content-Based-Movie-Recommmeder-System
[Link to the App](https://mrs-hg.herokuapp.com/)




## About the Project
- It is a content based movie recommender system.
- It is made by using Cosine Similarity.
- It recommend items to the user by using the similarity of items.
- It identifies the similarity between the movies based on their descriptions, genre, director, etc.
- The details o the movies (title, genre, poster, etc) are fetched using an API by [TMDB](https://www.themoviedb.org/documentation/api) and using the IMDB id of the movie in the API.


### Salient Features
- It will recommend TOP 5 most similar movies with respect to the searched movie.
- Not only movie names will going to display after hitting then "Recommend" button, respective movie poster will also get displayed.
 


### Build With
- Framework - Streamlit 
- API - TMDB
- Frontend - Streamlit Lib
- IDE - PyCharm
- Language - Python(3.10)

#### Note
Follow the "Getting Started" section, incase if you see application error in the above mentioned URL.




## Getting Started
To install and run the project on your local system, following are the requirements:




### Prerequisites
Get your API, by following the below steps:

- Create an account in https://www.themoviedb.org/ .
- Click on the ```API``` link from the left hand sidebar in your account settings and fill the details to apply for API key.
- If you are asked for the website URL, just give 'NA' if you do not have one.
- You will see the API key in your ```API``` sidebar once your request is approved.
- Download the ```similarity.pkl``` file from this [drive link](https://drive.google.com/file/d/1FC3fxLN-6P9ehHpIsKtjZ02k0pQySL6p/view?usp=sharing)


#### Note
```similarity.pkl``` file is too large, around 176MB. Github is not supporting files larger than 100MB, that's why I have uploaded it on [Google Drive](https://drive.google.com/file/d/1FC3fxLN-6P9ehHpIsKtjZ02k0pQySL6p/view?usp=sharing), so you can download it from there beacuse you'll be needing it while running the project.


## How To Run The project
- Clone or download this Repository to your local machine.
- Download the [TMDB credits dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv) as well.
- Install all the Libraries mentioned in the requirement.txt file, by running the following command
```bash
  pip install -r requirements.txt
```
- Get your API key from https://www.themoviedb.org/ by logging into your account.
- Replace the selected part with your api key in line no. 7 of  ```app.py``` file and save it.

  ![Papi](https://user-images.githubusercontent.com/77922607/170894218-04c1ec28-008f-4321-bf6d-07e79390d136.png)

- Open your terminal/command prompt from your project directory and run the below mentioned command.
```bash
  streamlit run app.py
```

![P1](https://user-images.githubusercontent.com/77922607/170894012-083defb1-e084-41f5-aef5-dfd9b27421c0.png)

- It automatically open the streamlit app on your default browser, or you can also view it through the Local URL link which is there your terminal/cmd prompt.

  ![P2](https://user-images.githubusercontent.com/77922607/170894077-6dfb9a04-f6f3-4cad-95ce-51d13047f37f.png)

- Yeah! Finally you are done.
- Now you can easily get the Top 5 most similar movies according to your search, by clicking on the reocmmend button.
 
 ![P3](https://user-images.githubusercontent.com/77922607/170894100-8b2c86ec-d4b8-4f08-a62c-ae13735eb4dc.png)

- That's it!


## Sources To Dataset

### TMDB Dataset
- [TMDB-5000-credits-csv_file](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv)
- [TMDB-5000-movies-csv_file](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

