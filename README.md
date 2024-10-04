# Audible_Review-Python_and_Tableau
## Data cleaning in Python
I downloaded this dataset on audible from Kaggle.  I cleaned the data in Python and visualized and analysed it in Tableau. The data has information about the books on audible, their authors and narrators, their language, their length, their release date, the price, and the ratings given by readers.
During data cleaning, I did the following steps:
-	Removed unnecessary prefixes from the author and narrator columns.
-	Extracted numbers from the time column (which was originally a string column) using regex and converted it to integer.
-	Converted release date column to datetime.
-	Extracted the average rating and the number of ratings from the stars column.
-	Cleaned and converted price column to numeric
-	Formatted the author and narrator columns to display names properly with spaces between the first and last names.

## Analysis and Visualization in Tableau

-	Loaded the cleaned csv in Tableau
-	Made a bubble chart showing number of books in different languages.
-	Created a line chart showing the trend of books released over the years.
-	Created a scatter plot showing the relationship between the length and price of books for different languages.
-	Created a calculated column by concatenating two strings.
-	Created a bar chart showing the top 10 most rated books and their ratings.
-	Created a tree map showing the average rating of books by language.
-	Created a dual-axis chart showing top ten authors by total price and the number of books they have written. Also put up a context filter for language to make the chart interactive displaying top ten authors in different languages.
-	Created an audible review dashboard displaying the following:
1.	A header showing all the important summary metrics at the top.
2.	Top ten most rated authors and their ratings. 
3.	Used filter action to display all the books by the author when clicking on their name.
4.	The number of books written by top rated authors.
5.	The average price of books by top rated authors.
6.	The average length of books by the top-rated authors.
7.	Filters of language and date.

## Conclusion:
- The vast majority of audiobooks were in English, followed by German and Spanish.
- The number of books released had been steadily increasing from 2009 to 21 and fell in 2022.
- Generally, the lengthier books were more expensive. 
- Chinese books were by far both the lengthiest and most expensive.
- The most common ratings were 4 and 5.
- Urdu books were the highest rated of all languages.
