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
