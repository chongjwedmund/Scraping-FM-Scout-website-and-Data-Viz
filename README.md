# Python Project: Football Manager 2020
### 1. Use BeautifulSoup to find all players with value above £20M or wage above £75k per week
### 2. Data Cleaning 
### 3. Data Exploration and Visualisation
* Is the EPL the most valuable league in the world? 

### Web Scraping and Data Cleaning
* Perform scraping process across multiple web pages 
* Scraping function run twice, once for players with value above £20M, and once for players with wage above £75k per week to capture a union of both conditions 
* Perform initial data cleaning for tidy data before exporting. This ensures easier steps for subsequent data cleaning.  
* Export 2 csv files with same headers, to be outer joined in subsequent steps

### Data Cleaning

Many of the data cleaning steps have been done in the get_page( ) function.
* Removing usused columns 
* Removing non-numeric characters 
* Changing data type 
* Stripping of whitespace 
* Renaming column headers and 
* Splitting of combined columns 
<br><br>

Further refinement required. 
* Merging data frames
* Removing duplicates 
* Reindexing 
* Detecting and correcting outliers and anomalies 
<br><br>

Finally export clean file as csv. 

### Exploratory Data Analysis
* Who are the most expensive players? 
* Who are the highest paid players?
* Which club has the most number of players in this list? What is their median value?
* What is the demographic of the players in this list? How does player value vary with age? 
* What is the distribution of player value? 
* What is the distribution of wages? 
* How does player value vary with wage? 

Finally, is the EPL the most valuable league in the world?

### Conclusion
We have met the objectives of this project, demonstrating a grasp of web scraping using BeautifulSoup, as well as data cleaning, exploration and visualisation using numpy, pandas and matplotlib libraries. 
<br>

| Topic | Concepts applied in project |
| :-------- | :----------- |
| Web Scraping and File IO | - Data extraction across multiple pages in a single function using BeautifulSoup<br>- Use list comprehension to flatten nested lists<br>- Write table headings and data to file |
| Data Cleaning | - Removing usused columns<br>- Removing non-numeric characters<br>- Changing data type<br>- Stripping of whitespace<br>- Merging data frames<br>- Removing duplicates<br>- Reindexing<br>- Detecting and correcting outliers and anomalies<br>- Renaming column headers<br>- Splitting of combined columns |
| Data Exploration and Visualisation | - Use pandas and matplotlib libraries to uncover insights<br>- Pie Charts<br>- Barcharts<br>- Histogram<br>- Scatterplot| 

<br>
We also performed EDA to visualise data, answering some questions such as:  

* Who are the most expensive players? 
* Who are the highest paid players?
* Which club has the most number of players in this list? What is their median value?
* What is the demographic of the players in this list? How does player value vary with age? 
* What is the distribution of player value? 
* What is the distribution of wages? 
* How does player value vary with wage? 
<br>

We discover that, EPL players and clubs dominate rankings in 3 of the 4 comparisons, namely: 
* 12 of 20 most expensive players 
* 9 of 20 top clubs with most players in list
* 8 of 20 top clubs by median player value

Although EPL players only make up 2 of the 20 highest paid players, wage is hardly a good measure of value. The scatterplot of wage v value demonstrated that most EPL players are of high value yet do not draw the highest wages. Astronomical wages on mediocre players can be attributed to leagues or clubs splashing cash to attract talent. Moreover, EPL players make up more than a third of all players in the list. We hence conclude that the EPL is the most valuable league in the world. 
<br>
