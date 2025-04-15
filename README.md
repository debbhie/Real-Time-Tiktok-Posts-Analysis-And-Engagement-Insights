# TIKTOK-POSTS-ANALYSIS-AND-ENGAGEMENT-INSIGHTS

# TABLE OF CONTENTS

# REAL TIME TIKTOK POSTS ANALYSIS AND ENGAGEMENT INSIGHTS
Since launching my TikTok content journey in October 2024, I have maintained a data-driven approach to track the performance of my posts. Using an automated Power BI dashboard that updates in real-time, I analyzed engagement metrics to understand what content resonates most with my audience. Key performance indicators (KPIs) such as total views, average engagement, engagement rate, and average playtime were closely monitored to guide strategic content decisions.

# DATA SOURCE & EXTRACTION PROCESS
The dataset used in this analysis was sourced from TikTok through the ScrapTik API. Data extraction and processing were performed using Python, and the final output was saved as a CSV file for analysis.
Below is an overview of the steps taken to ensure the dataset remains up-to-date with both existing and new posts:

* API Request: A request was sent to the TikTok API endpoint using my unique user_id to retrieve post data.

* Read Existing Data: The script first reads from the existing CSV file and identifies already stored posts using their post_id.

* Fetch New Data: A JSON request is made to retrieve additional data from the TikTok profile, if available.

* Update and Merge: Existing posts are updated with any new metrics, and new posts are appended to the dataset.

* Data Formatting: The updated and newly fetched posts are processed and formatted uniformly.

* Save as CSV: The final, merged dataset is saved as a CSV file for further analysis in Power BI.

# TOOLS
Python: This was used requesting for the data from Tiktok, transforming, updating and converting the data from Json to CSV file
Power BI: Employed for the main analysis and data visualization, enabling the extraction of key insights through DAX measures and visual tools.

# DATA PROCESSING
Data Preparation in Power BI:
After loading the cleaned data into Power BI, the following transformations and enhancements were made:

* Date column breakdown: Date was extracted from Date/Time column
* Duration column: Duration was changed from milliseconds to HH:MM:SS (Total Play Time)
* Creation of some new columns for dax formulars:
     Engagement Rate per post column.
     Duration Bin and view bin column

# SKILLS DEMONSTRATED
This analysis involved multiple data processing and analytical techniques, including:

Data Scraping & Transformation: Scraing data, converting it to Csv and cleaning it in PowerBI.
Data Processing & Cleaning: Structuring data using Power Query.
Data Analysis & Quick Measures: Creating meaningful insights with DAX measures in Power BI.
Visualization & Reporting: Presenting findings in a clear and actionable format.
Critical Thinking & Problem-Solving: uncovering the types of TikTok content that drive the highest engagement and identifying patterns in user interactions.

# OBJECTIVES/ PROBLEM STATEMENT
Business Problem
* Identify the types of content that generate the highest engagement rate

* Discover patterns that lead to higher likes, comments, shares, and views

* Determine effective strategies to increase audience engagement

# DATA ANALYSIS AND VISUALIZATION
The analysis reveals several key insights related to the posts performances
## Key Performance Indicators (KPIs)
* Total Posts: Over the course of 6months of content creation, 123 videos were posted(as of time of analysis)

* Total Views: 123 posts made generated a 1,000,000 views

* Average Engagement (Likes + Comments + Shares)on these post is 688.48

* Total Likes: The likes generated is 74,000

* Engagement Rate: for the contents shared is 7.71%

* Average Playtime: The average time people spend watching the video is 1 minute 59 seconds

 Definitions:

* Engagement = Likes + Comments + Shares

* Engagement Rate = (Likes + Comments + Shares) ÷ Views

### Top Performing Content by Engagement
Analyzing the top 10 posts based on total engagement: These are the contents that were performimh so high and pwople could relate with them 

"Skills to Learn as a Data Analyst" – 15,000 engagements

"How to Become a Data Analyst by April 2025" – 10,000 engagements

"Getting My First Job on Upwork" – 6,000 engagements

### Views vs Duration (Matrix Chart)
Content duration had a significant effect on views:

Videos over 3 minutes received the highest views at 42,628

2–3 minutes duration received the lowest at 134 views

### Engagement Rate Trend (By Month & Year)
Nov 2024: Highest engagement rate at 8.06%

Jan 2025: Dropped slightly to 7.62%

Apr 2025: Rebounded significantly to 10.93%

### Engagement by Day of the Week
Monday had the highest engagement at 24,000

Followed by Thursday with 22,000

Wednesday & Saturday: 11,000 each

Friday: 10,000

Tuesday: 5,000

Sunday: 1,000

### Correlation Between Views and Video Duration
The Pearson correlation coefficient was calculated to be 0.37

This indicates a moderate positive relationship between video duration and view count

Note: Calculated manually using Pearson’s formula, as Power BI does not currently support the CORR() function natively.

### Top 5 Most Liked Posts
"Skills to Learn as a Data Analyst" – 13,000 likes

"How to Become a Data Analyst by April 2025" – 8,700 likes

"Getting a Job on Upwork" – 5,500 likes

"Truth About Data Analysis Career and Job" – 3,100 likes

"Best Way to Learn Data Analysis" – 2,500 likes

### Total Engagement by Hour of Day
11 AM – 41,000 engagements

12 Noon – 24,000 engagements

9 AM – 16,000 engagements

1 PM – 890 engagements


### Top 3 Posts by Engagement Rate (Per Post)
"Post with No Caption" – Engagement rate: 0.74

"Grocery Shopping" – Engagement rate: 0.15

"Let Me Know" – Engagement rate: 0.14
