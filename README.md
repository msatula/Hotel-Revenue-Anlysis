# Hotel Revenue Data Analysis Dashboard
This is an interactive data report & visualization of hotel revenue using data collected from 2018 to 2020, hosted on my own SQL database. It served as my introduction to developing my own database and creating dashboards in Power BI. This project was created by following along with a tutorial YouTube video, linked below.

## Tech 
- `SQL`
- `Microsoft SQL Server Management Studio`
- `Power BI`

## Questions to Explore
- Is hotel revenue growing by the year?
- Should we increase the parking lot size?
- What trends are in the data?

## The Process
First, I used SQL Server Management Studio (SSMS) to host and connect to my own SQL database on my local computer. 

After importing the csv data files into SSMS, I wrote SQL queries using the UNION and JOIN operators to combine the several data tables. Here, it was also determined how revenue would be calculated as a new column in the data. 

Then, the database was connected to Power BI and imported using the previously written SQL queries. Power BI's data transformation tool was also used to add the aforementioned new column to represent revenue earned.

Multiple visualization tools were used to represent and summarize the data. Several statistics were displayed via trend graphs over time, such as average daily revenue, total nights spent, and car spaces. A line chart was used to plot revenue over time. A summary matrix was added to show data by year and by hotel type. A donut graph showcasing revenue per hotel type was also added. Then, I added several interactive filters to filter data by date ranges, the hotel type, and country. 

## How it could be improved
- Stronger focus on data cleaning -- Data cleaning wasn't the goal of this project, but could've resulted in incorrect data
- More timely data -- The dataset contains data from only a subset of 2020, which could result in misinterpretation.

## To open
1. Download `HotelRevenue.pbix`
2. Open the file in Power BI

## Video


## Sources
- Data used: <a href="https://github.com/msatula/Hotel-Revenue-Anlysis/blob/main/hotel_revenue_historical_full-2.xlsx">Data download</a>
- Tutorial followed: <a href="https://www.youtube.com/watch?v=S2zBHmkRbhY">Youtube link</a>
