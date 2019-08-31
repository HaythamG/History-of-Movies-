Although the start of the history of film is not clearly defined, the commercial, public screening of ten of Lumière brothers' short films in Paris on 28 December 1895 can be regarded as the breakthrough of projected cinematographic motion pictures. There had been earlier cinematographic results and screenings but these lacked either the quality or the momentum that propelled the cinematography Lumière into a worldwide success.

Soon film production companies and studios were established all over the world. The first decade of motion picture saw film moving from a novelty to an established mass entertainment industry. 


In the first PART, I attempted at narrating the story of film by performing an extensive exploratory data analysis on Movies Metadata collected from TMDB. I also built two extremely minimalist predictive models to predict movie revenue and movie success and visualize which features influence the output (revenue and success respectively).

In this PART, I will try to do some analysis and build the following:
- Data wrangling to process, transforming and mapping data from one "raw" data form into another format with the intent of making it more appropriate and valuable for a variety of downstream purposes such as analytics.
- Exploratory Data Analysis (EDA): to analyzing data sets, to summarize their main characteristics, often with visual methods use 
- A Regression that can predict the revenue of a particular movie.
- A Classification that identifies if a movie will be a hit or will make the producers lose money.


In the second, part of my Project on Movie Data Analysis and Recommendation Systems. I will attempt at implementing a few recommendation algorithms (content based, popularity based and collaborative filtering) and try to build an ensemble of these models to come up with our final recommendation system. With us, we have two MovieLens datasets.
- The Full Dataset: Consists of 26,000,000 ratings and 750,000 tag applications applied to 45,000 movies by 270,000 users. Includes tag genome data with 12 million relevance scores across 1,100 tags.
- The Small Dataset: Comprises of 100,000 ratings and 1,300 tag applications applied to 9,000 movies by 700 users.
I will build a Simple Recommender using movies from the Full Dataset whereas all personalized recommender systems will make use of the small dataset (due to the computing power I possess being very limited). As a first step, I will build my simple recommender system.
