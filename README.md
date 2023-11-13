## Query a Digital Music Store Database

## Overview
The Chinook Database holds information about a music store, the aim is to assisting the Chinook team with understanding the media in their store, their customers and employees, and their invoice information.

## About the dataset

- The schema for the Chinook Database is below:

   ![screen-shot-2017-06-29-at-10 51 15-pm](https://github.com/hayasalman/Music-SQL-Database/assets/71796909/fb833f8a-9ead-4a14-8ca7-2f8ee367531e)
  
- Data source stored as DB file and can be accessed through this link : [Chinook Database](https://github.com/hayasalman/Music-SQL-Database/blob/main/chinook.db)

## Coding

- **Toolkit** : DB Browser for SQLite.
- Querying language: SQL.

## Approches & Methodologies

- Start by querying the database for exploring.
- Formed the questions that we are looking to answer that are :
  - First, we wanted to know which music genre is more popular among the German customers.
  - Also, we are curious to know if there are any differences in terms of the albums period.
  - If the chinook team is interested in finding out who's their best customer The customer who has spent the most money will be declared the best 
    customer, so they can reward him/her.
  - Find out the top 5 Jazz artists in this database.
- Build the queries that answer our questions by using different sql functions : aggregations , grouping, conditional filtering , joins and 
  subqueries.

 ## Business Insights

 *These insights are driven from the questions' answers we asked earlier*
 
- In Germany , obviously the popular music genre is rock music, followed by metal, latin and blues. whereas, we noticed that the other genres' 
  popularity are gradually decreasing.

- There are 240 albums with a period less than the average 393599.2121 in (millisecond) . While 107 albums its period beyond the average i 
  (milliseconds).

- The Chinook team's best customer is called “Helena Holý “ who existed in the Czech Republic and she spent 49.62$, followed by “Richard Cunningham” 
  from USA who spent 47.62$.

- The top five jazz artists are : “Miles Davis” who wrote about 37 songs, followed by Gene Krupa, Spyro Gyra, Antônio Carlos Jobim , and lastly 
  Incognito.

## Refrences

[Chinook Database Insights & Visualizations](https://github.com/hayasalman/Music-SQL-Database/blob/main/SQLProject.pdf)

[Chinook Database Queries](https://github.com/hayasalman/Music-SQL-Database/blob/main/SQL.txt)
  

     
