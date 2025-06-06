# Games_Sales_Analysis
This is an analysis of Sales Report for Games Across the Continent.

## Table View
+ Below are the table view for the data to be analysed. The first 5 Rows are displayed
- These are the first five Records

  |Rank|	Name|	Platform	|Year|	Genre	|Publisher	|NA_Sales|	EU_Sales|	JP_Sales|	Other_Sales	|Global_Sales|
  |-----|------|---------|-------|-------|--------|--------|---------|---------|---------|---------|
  |1|	Wii |Sports|	Wii	|2006|	Sports|	Nintendo|	41.49|	29.02|	3.77|	8.46|	82.74|
  |2|	Super Mario Bros.|	NES|	1985|	Platform|	Nintendo|	29.08|	3.58|	6.81|	0.77|	40.24|
  |3|	Mario Kart Wii|	Wii|	2008|	Racing|	Nintendo|	15.85|	12.88|	3.79|	3.31|	35.82|
  |4|	Wii| Sports Resort|	Wii|	2009|	Sports|	Nintendo|	15.75|	11.01|	3.28|	2.96|	33|
  |5|	Pokemon Red/Pokemon| Blue|	GB|	1996|	Role-Playing|	Nintendo|	11.27|	8.89|	10.22|	1|	31.37|

## Data Insights
> In the analysis, we saw that the highest sales is from Nintendo where total revenue across continent is about 17.81K Dollars.
> This is an interesing visual

## SQL Queries

```SQL
SELECT * FROM games;
```
```SQL
SELECT name FROM games;
```
```SQL
SELECT EU_sales, JP_Sales FROM games;
```
```SQL
SELECT COUNT (publishers) FROM games
where publisher = 'Nintendo';
```
```SQL
SELECT SUM (NA_Sales) FROM games
GROUP BY publisher;
```

## Visualization
### Dashboard
![Screenshot (353)](https://github.com/user-attachments/assets/47504bf6-c6f2-4569-91a4-467e65387566)

[To view Dashboard, Click Here](https://ibb.co/7NZqMz46)


