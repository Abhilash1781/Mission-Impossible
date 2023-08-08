## Project
A NLP project focusing on sentiment analysis of the IMDB reviews of the movie "MISSION IMPOSSIBLE - DEAD RECKONING (2023)

## About the movie 
<img src="https://github.com/Abhilash1781/Mission-Impossible/assets/72621930/121877e1-ba69-49b9-8642-a084e3e3fec5" alt="Image" width="300">

Mission: Impossible – Dead Reckoning Part One is a 2023 American spy action film directed by Christopher McQuarrie starring Tom Cruise, Hayley Atwell, Rebecca Ferguson etc. 

## Dataset
I scrapped 957 IMDB reviews of the movie (as of 6th august 2023) with the help of Selenium and Scrapy. 
The following data were extracted :
1) Date on which review posted
2) Name of the Author
3) Rating	(out of 10)
4) Title of the review
5) Review
6) Review Link

Link to the review page : https://www.imdb.com/title/tt9603212/reviews/?ref_=tt_ql_2

## Pre-processing
The reviews which had not rating were removed . 


## Word cloud
![mi word cloud](https://github.com/Abhilash1781/Mission-Impossible/assets/72621930/674c8363-fd6f-43c4-b731-3cf73c62cc55)

## Sentiment Analysis
Implemented three models such as:
1) VADER (Valence Aware Dictionary and sEntiment Reasoner)
2) RoBERTa ( Robustly Optimized BERT Pre-training Approach )
3) Bert Base Multilingual Uncased Model
n
## Applications

1) Sentiment analysis can help movie studios and producers undertstand audience reactions to their films.
2) It provides insights into the general public's opinion about a movie, which can be used to aggregate movies and generate scores.
3) Can be used in psychological studies human and in analysing the emotional impact of movies on reviews.
