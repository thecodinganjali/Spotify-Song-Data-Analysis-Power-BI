# Spotify-Song-Data-Analysis-Power-BI

<img src="https://github.com/thecodinganjali/Spotify-Song-Data-Analysis-Power-BI/assets/168422801/526bfed0-4304-4b2c-8557-debbfd70c3fc" width="300" height="200">

## Introduction

Welcome to the Spotify Song Analysis Dashboard project, where we dive deep into Spotify's song data to uncover key insights and trends. This dashboard is your go-to tool for understanding track performance, audience engagement, and streaming patterns on Spotify. With intuitive visualizations and powerful analytics, we provide stakeholders with actionable insights to optimize their strategies in the music industry.


## Project Objectives 💡

The Spotify Song Analysis Dashboard Project is designed to provide stakeholders with actionable insights into Spotify's song data, enabling them to make informed decisions and optimize strategies in the music industry. The main objectives of the project include:

1) Total Streams Analysis by Date and Track.
2) Artist Performance Analysis by Genre.
3) Stream Distribution by Region and Date.
4) Track Attributes Analysis.
5) Top Tracks by Total Streams.
6) Monthly Performance Metrics.
7) Playlist Effectiveness Analysis.
8) Summary Insights and Recommendations.


## Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Utilize Power Query Editor to identify and remove errors, replace missing values, and ensure data consistency. 
- Step 5 : Generate a calendar table using the CALENDAR function in DAX, specifying the date range from the minimum to the maximum date in the Spotify dataset.
- Step 6 : Utilize the ADDCOLUMNS function to add additional columns to the calendar table, such as Year, Quarter, Quarter(Q), Month, MonthName, Day of Week, and DayName.
- Step 7 : Design visualizations in Power BI Desktop to showcase insights derived from the Spotify dataset, utilizing the newly created calendar table for time-based analysis.
- Step 8 : Visual filters (Slicers) were added for four fields named "Grading date", "•	Processing Method" & "Region".
- Step 9 : Three card visuals were added to the canvas, one representing Total Streams , Tracks & average Streams.
- Step 10 : Visualize streaming trends over time using a Line Chart depicting Date vs. Sum of Streams.Explore monthly track performance and average streams through a matrix visualization.
                         Understand streaming patterns by day of the week with a stacked bar chart showing day versus streams.Enhance analysis with a multi-slicer for attributes like danceability, instrumentality, energy, and liveliness.

- Step 11 : In the report view, Incorporate the Spotify logo downloaded from the official source to reinforce brand identity and recognition

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://github.com/thecodinganjali/Spotify-Song-Data-Analysis-Power-BI/assets/168422801/86f56965-e0db-4bce-9ddf-202251b8e22b)

##  Visualization Tools

 1) Tool used: **Power BI**

 2) Dataset Used : [Spotify Song Analysis Dataset](https://github.com/thecodinganjali/Spotify-Song-Data-Analysis-Power-BI/blob/main/ONYXDA~1.XLS)


 ## Conclusion 

In summary, the Spotify Song Analysis Dashboard offers a comprehensive view of streaming metrics and facilitates easy data exploration through slicers. Visualizing long-term streaming trends and assessing monthly track performance enable stakeholders to gain valuable insights quickly. With its intuitive interface, this dashboard is a valuable tool for decision-making in the music industry.
