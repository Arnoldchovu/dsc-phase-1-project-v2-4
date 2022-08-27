Microsoft is known for its dominance in the technology sector. Its innovations in computers, computer software, and mobile operating systems have set it apart as one of the leading companies in the ever-changing world of technology. Through these changing times, Microsoft is looking to expand its business horizon into the movie industry by building and managing its movie business. However, the company does not know to run the movie business. Running such an intense program without enough knowledge will be unsuccessful and record losses for the company. After careful consideration, the company hires a data scientist to collect the relevant information about the movie industry and present the findings to the management. The company is looking to make data-driven decisions based on these findings’ insights. The company tasks the data scientists to use data analysis to provide the management team with enough relevant information to enhance their understanding of the movie industry and the steps they will take to succeed. 
This project requires understanding the movie industry’s aspects and applying the knowledge to Microsoft's challenge. The challenge will require assessing the situation Microsoft is in and the resources available for the project to be successful. This project aims to provide Microsoft with enough knowledge to traverse the movie industry and produce successful movies for domestic and foreign markets. 


DATA UNDERSTANDING
This being a data science project, data is an essential aspect that will determine the success of this analysis. Furthermore, this project’s result is to develop data-driven recommendations for Microsoft that will enhance its business acumen. We are presented with four data sets from four companies, i.e., Box Office Mojo, IMDB, Rotten Tomatoes, The Movies DB, and The Numbers. All the data sets provide further insight for this project and enhance the understanding of the movie industry.
Box Office Mojo Data
This data set contains data between 2010 and 2018 describing a movie, the production studio, and the domestic and foreign gross. The gross domestic column represents the amount of gross sales made by the studio domestically. The foreign gross column describes the amount of sales made around the world. The data will need some cleaning and type conversion of the foreign gross column so that it can be ready for analysis and plotting. 
IMDB Data
The IMDB data comes as a database containing movie details, including directors, writers, and other relevant information. The database is connected using movie IDs and person IDs representing the people who worked on the movies in different roles. The directors of the movies refer to the directors’ of the movies. This data also provides the genres of the movies, average ratings, and the number of votes for every movie. Joining the various tables will need some work and some duplicate removal methods. Some columns will be dropped since they contain some missing values or have irrelevant information.
Rotten Tomatoes Review Data
This data contains the reviews of different movies, the review’s critics and publisher, and the review’s date. In this case, this data set was not of much help because it did not have the movie’s name being reviewed, which renders the review null.
Rotten Tomatoes Movie Info Data
This data set contains the synopsis, the TV rating, genre, director, writer, theaters release date, DVD release date, currency, box office runtime, and studio of the movies. However, most columns have multiple missing values that hinder the data analysis. In addition, some columns are irrelevant in the analysis to be conducted in this project. For instance, the synopsis columns, the TV rating, theatre and DVD release date, currency, office runtime, and studio columns either have multiple missing values or have irrelevant content. 
The Movie DB Data
This data set contains movies, genres, release dates, vote counts, and the vote average. This data set will provide relevant information on the popularity of movies and the number of votes they got from the database. 
The Numbers Data
This data set contains relevant information about movie budgets and their domestic and foreign gross sales. This data clearly shows the movie’s profit domestically and worldwide. This information can project the movies that have done well domestically and worldwide. Also, the data shows the relation between the budget and the profits that a movie can make. The dataset does not contain any missing values, but some of their columns will need type casting. 

UNDERSTANDING THE QUESTIONS
The questions for this analysis are driven to improve the understanding of the movie industry. Since the industry has numerous aspects determining the movie’s success, we will investigate three aspects that Microsoft can use to its advantage as an upcoming studio. The questions are:
Does the budget of the movie affect the profits of the film?
Which studio will present significant competition to Microsoft’s studio?
What are the genres the company should invest in?
 
DATA PREPARATION
Select Data
After carefully analyzing the provided data sets, I chose the data from The Numbers, IMDB, and The Box Office Mojo. These data sets were selected according to the questions they answered in this analysis. The Numbers’ data set provides insights into the relationship between the budget for a movie and the profits it garners. The domestic and foreign gross columns against the budget column show the movie’s budget used and the profit it has garnered.  The Box Office Mojo data provides insight into the best studio that will present competition against Microsoft’s upcoming studio. Finally, the IMDB data set contains relevant information that will assist in understanding the ratings of the genres produced by other studios. This will enable Microsoft to target the production of highly rated genres to match the ratings. 
DATA CLEANING
Data cleaning of the data sets was the lengthiest task of this analysis. The choice of the three data sets had to be broken down into the relevant columns that will assist in answering the selected questions. Since some data sets contain missing values, efficient methods for dealing with the missing values will be critical to maintaining the integrity and validity of the data. In addition, some data sets’ quality must be improved to ensure the accuracy of the results. 

DATA ANALYSIS
The analysis of the data was result oriented. In other words, it targeted answering the relevant questions for the company. The analysis mainly compared if the appropriate columns create insight and understanding of the data provided. 
Question 1
Analyzing the budget and profit data from The Number’s data set will provide an understanding of the relationship between budget and profit. I started by creating a pair plot to understand the relationship between the columns. Then dropped, the unnecessary columns to allow for easy plotting.  

The above plots depict the domestic and foreign gross relationship against the movie’s budget. The success of the movie sales does not depend on the film’s budget. However, it is observed that many movies have been produced with $200 million and made a significant profit. Some films used a very high budget and counted losses since they did not break even. The budget does not determine the success of the movie being produced. 
Question 2
There are numerous studios in the movie industry, and they have a record of producing blockbuster movies. Since Microsoft is new in the business, it is advisable to identify its competitors and understand its production process. This will provide insight into Microsoft’s production process and other fundamentals. The relevant studios can see this plot as they made the highest gross sales over the years.


Question 3
Understanding the genres with the highest rating will narrow the production choice for the company. However, Microsoft should produce various genres to satisfy the market. In this case, the IMDB data provided the best comparison of the genres, and we plotted the top ten and bottom ten genres according to the ratings. 




CONCLUSION
In conclusion, entering the movie industry is a task that requires data insight to ensure the right decisions are made. Microsoft needs a better understanding of the industry by investigating several aspects that will provide insight into its success. Using the data from Box Office Mojo, IMDB, and The Numbers, an analysis was conducted to understand Microsoft’s industry better. After cleaning and analyzing the data, we can see the relationship between the budget and the gross sales made by studios. The competition from other studios and the insight on genres Microsoft should aim at producing. Further investigations can be carried out to ensure they have more information and insight into the industry.
