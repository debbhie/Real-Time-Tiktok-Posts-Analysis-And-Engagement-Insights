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
* Total Posts (123):
Shows consistent content creation and effort over six months, laying the foundation for audience growth.

* Total Views (1,000,000):
A strong indicator of reach—demonstrates successful visibility and potential virality of the content.

* Average Engagement (688.48):
On average, each post attracted nearly 700 combined likes, comments, and shares—pointing to good interaction levels.

* Total Likes (74,000):
Likes alone account for a significant portion of engagement, signaling positive reception from viewers.

* Engagement Rate (7.71%):
Above-average engagement rate (compared to TikTok’s typical 3–6%), suggesting the content resonates with the target audience.

* Average Playtime (1 min 59 secs):
Indicates strong viewer retention, especially for a platform known for short-form content.

Definitions Recap

* Engagement = Likes + Comments + Shares

* Engagement Rate = Engagement ÷ Views

### Top Performing Content by Engagement
* "Skills to Learn as a Data Analyst" (15,000):
This post performed exceptionally well—likely because it delivers practical, career-advancing value.

* "How to Become a Data Analyst by April 2025" (10,000):
Timely and goal-oriented, this content probably motivated aspirants with a clear path and deadline.

* "Getting My First Job on Upwork" (6,000):
Relatable storytelling and proof of results can drive deeper audience connection and shares.

### Views vs Duration (Matrix Chart)
* Videos Over 3 Minutes (42,628 views):
Long-form videos had the highest view count—suggesting TikTok users are willing to watch longer educational or storytelling content.

* 2–3 Minutes (134 views):
Significantly fewer views, possibly due to poor structure or lack of value depth for this middle-range length.

💡 This reveals that video length plays a major role in visibility and should be optimized accordingly.

### Engagement Rate Trend (By Month & Year)
* Nov 2024 (8.06%) – Strong start in content journey.

* Jan 2025 (7.62%) – Slight drop; could be due to holiday season or algorithm shifts.

* Apr 2025 (10.93%) – Spike in engagement, likely due to highly relevant or viral posts.

📌 Monitoring month-over-month trends helps identify peak seasons and high-performing content styles.

### Engagement by Day of the Week
* Monday (24,000) & Thursday (22,000):
These are peak days for audience activity. Posting on these days can maximize reach and interaction.

* Sunday (1,000):
Lowest engagement—content posted on Sundays might need to be rescheduled or boosted.

🗓️ Ideal posting days: Monday & Thursday.

### Correlation Between Views and Video Duration
* Pearson Correlation = 0.37:
A moderate positive correlation means that longer videos tend to receive more views.

💡 Viewers are more engaged when videos are longer, especially if the content is insightful or storytelling-driven.

Note: Calculated manually using Pearson’s formula, as Power BI does not currently support the CORR() function natively.

### Top 5 Most Liked Posts
* "Skills to Learn as a Data Analyst" (13,000 likes):
Educational, career-focused content clearly resonates most.

Other posts that combine relatable stories, clear tips, and personal experience also performed well.

### Total Engagement by Hour of Day
* 11 AM (41,000) & 12 Noon (24,000):
Best-performing hours—viewers are highly active around late mornings to midday.

* 1 PM (890):
A noticeable drop—suggesting lower attention span post-lunch.

⏱️ Optimal posting time: between 9 AM and 12 PM.

### Top 3 Posts by Engagement Rate (Per Post)
* "Post with No Caption" (0.74):
Surprisingly, captionless content drew more engagement—possibly due to curiosity or authenticity.

* "Grocery Shopping" (0.15) & "Let Me Know" (0.14):
Lifestyle or casual content might perform better with clearer CTA or targeted storytelling.


