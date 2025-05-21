# Twitter-Analytics-Dashboard
This dashboard helps the Twitter understand their customers better. It helps the X Analysis know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. Thus since by using this dashboard they have identified this problem, they can further work on factors responsible for these unwanted mistakes.

Steps followed
Step 1 : Load data into Power BI Desktop, dataset is a Excel file.
Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
Step 4 : By transform editting done on the corresponding data with requriment for eg: date and time is coverted to year and quater in a separate column.
Step 5 : For calculating , null values were not taken into account
Step 6 : In the report view, under the view tab, theme was selected.
Step 7: Developed a chart that displays tweets with the highest engagement rates (top 10%). Include only those tweets that have received more than 50 likes and were posted on weekdays and this graph should work only between 3PM IST to 5 PM IST apart from that time we should not show this graph in dashboard itself as well as tweet character count should be below 30.
Step: 8 Builded a chart to identify the top 10 tweets by the sum of retweets and likes. Filter out tweets posted on weekends and show the user profile that posted each tweet and this graph should work only between 3PM IST to 5 PM IST apart from that time we should not show this graph in dashboard itself and the tweet impression should be even number and tweet date should be odd number as well as tweet word count be below 30

Step 9 : Created a line chart showing the trend of the average engagement rate over each month of the year. Separate the lines for tweets with media content and those without and this graph should work only between 3PM IST to 5 PM IST and 7 AM to 11AM apart from that time we should not show this graph in dashboard itself and the tweet engagement should be even number and tweet date should be odd number as well as tweet character count should be above 20 and need to remove tweet word which has letter 'S'.
A Four page report was created on Power BI Desktop & it was then published to Power BI Service.
