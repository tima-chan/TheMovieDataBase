# The Movie Database¶
## by Fatimah Ehab Farouk


## Dataset Overview

During this project, a movie dataset that contains metadata for all 45,000 movies listed in the Full MovieLens Dataset for movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages will be wrangled and analyzed visually, then presented in explanatory visualizations. You can check the Dataset on Kaggle from [here](https://www.kaggle.com/rounakbanik/the-movies-dataset?select=movies_metadata.csv).

### Structure and Dictionary

The whole dataset is one observational unit representing movies data. Each row represents 1 movie and the data related to it, while each column represents different movie features, such as *movie title, original language* and *production countries*.

- **adult**: Indicates if the movie is X-Rated or Adult. 
- **belongs_to_collection**: A stringified dictionary that gives information on the movie series the particular film belongs to. 
- **budget**: The budget of the movie in dollars. 
- **genres**: A stringified list of dictionaries that list out all the genres associated with the movie. 
- **homepage**: The Official Homepage of the move. 
- **id**: The ID of the move. 
- **imdb_id**: The IMDB ID of the movie. 
- **original_language**: The language in which the movie was originally shot in. 
- **original_title**: The original title of the movie. 
- **overview**: A brief blurb of the movie. 
- **popularity**: The Popularity Score assigned by TMDB. Learn more about how it's calculated [here](https://developers.themoviedb.org/3/getting-started/popularity).
- **poster_path**: The URL of the poster image. 
- **production_companies**: A stringified list of production companies involved with the making of the movie. 
- **production_countries**: A stringified list of countries where the movie was shot/produced in. 
- **release_date**: Theatrical Release Date of the movie. 
- **revenue**: The total revenue of the movie in dollars. 
- **runtime**: The runtime of the movie in minutes. 
- **spoken_languages**: A stringified list of spoken languages in the film. 
- **status**: The status of the movie (Released, To Be Released, Announced, etc.) 
- **tagline**: The tagline of the movie. 
- **title**: The Official Title of the movie. 
- **video**: Indicates if there is a video present of the movie with TMDB. 
- **vote_average**: The average rating of the movie. 
- **vote_count**: The number of votes by users, as counted by TMDB.
- **cast**: A stringified list of dictionaries consisting of cast names and the corresponding characters they played.
- **crew**: A stringified list of dictionaries consisting of crew names and the function they performed.

## Key Insights for Presentation
The presentation focuses on cultural aspects trying to answer the question of ***did filmmaking and cinema evolved culturally and socially since its beginning till recent years?*** I tried to reach an answer from 3 points of view:
- 1. Original Language in Films: the top languages represented in film.
- 2. Spoken Languages in Film: the number of languages spoken in films, which can represent culture diversity in cinema.
- 3. Gender in Film: how are women and men represented in filmmaking in cinema?

## Summary of Findings

Film industry evolved culturally over time to contain more languages and give more space to divese cultures to engage with it. However, women are underrepresented in cinema. They got to be more involved in the film industry, not just in filmmaking, but all roles, including cinematographers, film producers, film critics, and other film industry professions.

#### General Insights:
- The higher rating a film has doesn't necessarily mean the more popular or acclaimed. Even with the *enough* amount of voters, there isn't a proven relationship between rating and popularity in cinema.
- Many cultures are interested in cinema, but they lack popularity due to the barrier of language.
- There's a trend among people leaning towards recent movies, starting from 2000 to now, with a few exceptions.

#### Gender-study-related Insights:
- There's a wide gender gap between women and men filmmakers contributing in the industry. Reasons aren't clear which gives the space for another elaboration and usage of regression analysis.
- Women only began to direct films later than men, and only increased starting 2000.
- Films' ratings for both men and women have almost the same average, close minimum and maximum points, suggesting that the lack of women in film industry isn't due to their lack of skill or talent.



