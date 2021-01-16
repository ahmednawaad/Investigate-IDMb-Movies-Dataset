## Introduction

> This is IDMb Movies Data set containing 10866 rows and 21 columns every row represent a movie and the columns represent the movies information like (imdb_id, popularity, budget, revenue, original_title, cast, homepage, director, tagline, keywords, overview, runtime, genres, production_companies, release_date, vote_count, vote_average, release_year, budget_adj, revenue_adj)

### There are lots of questions to answer from this data
> TimeLine Questions
- 1- Are the movies increase with time or decrease?
- 2- are the profits increase with time or decrease?
- 3- Are the rateing increase with time or decrease?
- 4- Which genre is produced more with time?

> Other question
- 5- what factors affecting movies' high rating?
- 6- what is largest genre produced from 1960 to 2015?
- 7- What is the genre gain more profit?
- 8- which genre is preferred(Gain high vote)?
- 9- which director movies is preferred(Gain high vote)?
- 10- Who is the director movies gain more profit?
- 11- which runtime movies is preferred(Gain high vote)?
- 12- which runtime movies gain more profit?


## Conclusions

> This is IDMb Movies Data set  cleaned containing
- 10865 rows every row represent a movie and and  16 columns represent the movies information like (imdb_id,	popularity,	original_title,	cast,	director,	keywords,	runtime,	genres,	production_companies,	release_date,	vote_count,	vote_average,	budget_adj,	revenue_adj,	genre, Profit)

> After Exploratory Data Analysis :
>>TimeLine analysis
- The number of movies increases with time from 32 movies in 1960 to 700 in 2014.
- The Profits increases with time from 7.977407e+08 dollar in 1960 to 1.750957e+10 dollar in 2015.
- The Average Vote decrease with time from 6.325 in 1960 to 5.885692 in 2015.
- From 2010 to 2015 Drama, Family, Adventure and Science fiction gain more production.
- And Animation, Forgien, western, and music gain less production with time.
>>> Other EDA.
- The vote increase with:
 - Popularity
 - Vote count
 - Movie budget
- The largest produced genre is Drama with 4760 Movie.
- The least produced genre is Western with 165 Movie.
- Advanture, Action and comdy gain the maximum profit.
- The preferred genre is Documentary with averge vote 6.9.
- The top voted movies reated to
 - Mark Cousins | 9.20
 - Derek Frankowski | 8.80
 - David Mallet | 8.70
 - Curt Morgan | 8.50
 - Saul Swimmer | 8.50
- The directors movies gain more profit
 - Steven Spielberg 1.312603e+10
 - Peter Jackson 5.645492e+09
 - Robert Zemeckis 4.335995e+09
 - Chris Columbus 4.171046e+09
 - Michael Bay 3.958676e+09
- The high run time values are preferred
- And the runtime around 162 minutes gives high profit

> Limitions
- Data given from 1960 to 2015
- There are null values in budget_adj, revenue_adj,	profit and Run time.
- preferred Value calculated as high voting
- Dollar value not the same from 1960 to 2015

> published at
- https://github.com/ahmednawaad/Investigate-IDMb-Movies-Dataset
