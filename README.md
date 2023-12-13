# youtube_creators_PowerBI_Project
# YouTube Channel Analysis with Power BI

This project is based on analyzing YouTube channel data using Power BI. The data is presented in a clear and understandable way, as you can see in the report. 

The main data source for this project is an Excel file named "Global YouTube Statistics.xlsx", which contains three sheets:

- The first sheet has information about individual YouTube creators, such as their channel name, category, country, subscribers, views, etc. This data was obtained from Kaggle.
- The second sheet has the daily subscriber count of the top 50 YouTube channels from December 10, 2021 to November 27, 2023. This data was scraped from Social Blade.
- The third sheet has the daily view count of the top 50 YouTube channels from December 10, 2021 to November 27, 2023. This data was also scraped from Social Blade.

You can download the Excel file from this link: https://github.com/priyansharya09/youtube_creators_PowerBI_Project/blob/main/Global%20YouTube%20Statistics.xlsx

To use this data in Power BI, you need to follow these steps:

1. Open the Excel file in Power BI and click on "Transform Data" to open the Power Query Editor.
2. In the Power Query Editor, go to the Transform tab and select the "date" column in the second and third sheets. Then, click on the drop-down arrow and select "Unpivot Other Columns".
3. Rename the second column as "youtubers" in both sheets. This will help you create a relationship between the sheets and the tables in Power BI.
4. Close and apply the changes in the Power Query Editor.
5. In Power BI, create a relationship between the three tables using the "youtubers" column as the key.
6. You can now create various visualizations and reports using the data. For tips and tricks on how to use Power BI, you can watch some tutorials on YouTube.
