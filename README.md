# HackerRank-MySql-Solution
HackerRank MySql  All Problem Solution


Q.1 Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.
Ans:- SELECT * FROM CITY WHERE POPULATION > 100000 AND COUNTRYCODE="USA";

Q2.Query the NAME field for all American cities in the CITY table with populations larger than 120000. The CountryCode for America is USA.
Ans: SELECT NAME FROM CITY WHERE POPULATION >120000 AND COUNTRYCODE="USA";

Q3.Query all columns (attributes) for every row in the CITY table.
Ans: SELECT * FROM CITY;

Q4.Query all columns for a city in CITY with the ID 1661.
Ans: SELECT * FROM CITY WHERE ID=1661;

Q5.Query all attributes of every Japanese city in the CITY table. The COUNTRYCODE for Japan is JPN.
Ans: SELECT * FROM CITY WHERE COUNTRYCODE="JPN";

Q6.Query the names of all the Japanese cities in the CITY table. The COUNTRYCODE for Japan is JPN.
Ans:SELECT NAME FROM CITY WHERE COUNTRYCODE="JPN";

Q7.Query a list of CITY and STATE from the STATION table.
Ans: SELECT CITY,NAME FROM STATION;

Q8.Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer.
Ans: SELECT DISTINCT(CITY) FROM STATION WHERE MOD(ID,2)=0;
