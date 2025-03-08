java c
CS 338 - Winter 2025
Assignment 2
March 4, 2025
In this assignment, you will continue to write queries for two databases, TPC-H and CHINOOK, but focusing on more advanced features. Both databases should already be set up on your machines. If they are not, please refer to the instructions in Assignment 1 for installation details.
Each question is worth 5 points, except for PARTI-Question #3, which is worth 10 points. The assignment is due on March 11, 2025, at 11:59 pm.
Please upload your answers as a single PDF file to the Assignment 2 folder on Learn Dropbox.
Note that submissions must be in PDF format only; any submission not meeting this requirement will receive 0 marks.
PART I: TPC-H Database:

Write SQL queries to answer the following:
1. How many European customers have a balance (column name is c acctbal) that is less than $8000.
2. Which region (Aisa, Europe...) supplies the most distinct parts.
3. What is the average time for shipping items by TRUCK.
FOLLOW UP. List the quantity and orderkey of all the items shipped by TRUCK which takes less than the above time.
Please note that this question requires addressing two queries.
4. List all the items which have NO discount and not sold to customer in EUROPE.
5. List name(s) of the customer(s) who has not place any orders.
6. List the (distinct) items which are ordered by the customers from the country where suppliers have the highest average balance.
7. Find the average price of all t代 写CS 338 - Winter 2025 Assignment 2SQL
代做程序编程语言he orders which contain no parts with size larger than 40.
8. List the name of the suppliers which supplies more than 5 parts along with the number of parts their supplied.
9. Find the names of all the distinct parts which receive the highest discount.
PART II: The CHINOOK database:

1. List the genre of tracks which is contained in the most playlist
2. Find audio tracks which have a length longer than the average length of all the audio tracks
3. Which playlist(s) contain the largest number of pop tracks
4. Find the number of employees live in the same city with each customer, sorted by descending order
5. Which artist(s) has the most tracks which can be classified to Jazz
6. Find the name of the German customer(s) who has paid the most in total without company name
7. List the name and age of the employees who support more than 5 customers.
Hint 1: You can use GETDATE() function to get the current date, and use an other function from last assignment to calculate ages.
Hint 2:   For more details on SQLite date functions, please visit SQLite Date Functions Documentation.
8. Find the manger who manages most employees but also being managed by someone else (Note: there are employees who do not have managers, i.e., there may be NULL values in ReportsTo column)
9. List the name of the artists with more than 5 tracks
10. Find the playlist(s) which contains most tracks by artist ”AC/DC”







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
