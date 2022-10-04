# book-scraping-into-Data-Base
Scrape data Directly Into sqllite DB browser and then retreive data with queries
# Used Libraries
bs4, csv, requests, sqlite3
# Task
Design and create a database for scraping All books for each category using DB Browser for sqllite from this web site (http://books.toscrape.com/).
1- create books & categories table.
2- create notebook to scrap data and save data in the database.
3- create another notebook to answer some questions using SQL Language.
	01) Write a sql query to get books that has rate >=3 and has 'Mr' in its name.
	02) Write a sql query to get books that has rate >=3 or price > 20.
	03) Write a sql query to get books that has rate not 3.
	04) Write a sql query to get books that has price between 10 and 40 and has rate 3 or 4 or 1.
	05) Write a sql query to get the top 5 most expensive books (order books desc with price column and then limit the result to the first 5).
	06) Write a sql query to get the 3rd 10 books in the books table order first by rate desc and then by price asc.
	07) Write a sql query to add a new category in categories table and add 5 books to this category in books table with title, rate and price.
	08) Write a sql query to update book's rate to 3 that thier price < 20£.
	09) Write a sql query to delete all books that have price > 50£ and has rate <= 2.
	10) Write a sql query to count the number of books that have 'Secret' in thier names and price between 10£ and 25£.
	11) Write a sql query to get the minimum & maximum price for all the books that have rate 5.
	12) Write a sql query to calculate the avg price for all the books that have rate 5.
	13) Write a sql query to sum all book's price that have rate 2 and price between 10 and 40
	14) Write a sql query to join both books & categories table into one new table containing book_name & category_name & book_rate and book_price.
	15) Write a sql query to calculate how many books each rate has and have price between 20£ and 30£.
	16) Write a sql query to calculate how many books each category has having count > 10.
	17) Write a sql query to get all books with category_name='Music' using subquery.
4- Export Database to CSV File and use pandas to read this CSV.
