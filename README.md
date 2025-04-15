# TIKTOK-POSTS-ANALYSIS-AND-ENGAGEMENT-INSIGHTS

# TABLE OF CONTENTS
- [REAL TIME TIKTOK POSTS ANALYSIS AND ENGAGEMENT INSIGHTS](#real-time-tiktok-posts-and-engagement-insights)
- [DATA SOURCE & EXTRACTION PROCESS](#data-source-&-extraction-process)
- [TOOLS](#tools)
- [DATA PROCESSING](#data-processing)
- [SKILLS DEMONSTRATED](#skills-demonstrated)
- [DATA ANALYSIS AND VISUALIZATION](#data-analysis-and-visualization)
- [DATA VISUALIZATION](#data-visualization)
- [ANSWERS TO BUSINESS PROBLEMS](#answers-to-business-problems)
- [INSIGHTS](#insights)
- [LIMITATIONS](#limitations)
- [RECOMMENDATIONS](#recommendations)
  
# REAL TIME TIKTOK POSTS ANALYSIS AND ENGAGEMENT INSIGHTS
Since launching my TikTok content journey in October 2024, I have maintained a data-driven approach to track the performance of my posts. Using an automated Power BI dashboard that updates in real-time, I analyzed engagement metrics to understand what content resonates most with my audience. Key performance indicators (KPIs) such as total views, average engagement, engagement rate, and average playtime were closely monitored to guide strategic content decisions.

# DATA SOURCE & EXTRACTION PROCESS
The dataset used in this analysis was sourced from TikTok through the ScrapTik API. Data extraction and processing were performed using Python, and the final output was saved as a CSV file for analysis.
Below is an overview of the steps taken to ensure the dataset remains up-to-date with both existing and new posts:

* API Request: A request was sent to the TikTok API endpoint using my unique user_id to retrieve post data.

* Read Existing Data: The script first reads from the existing CSV file and identifies already stored posts using their post_id.
![TT python](https://github.com/user-attachments/assets/c9330ea3-cd45-4df6-b183-54d82f242e41)

* Fetch New Data: A JSON request is made to retrieve additional data from the TikTok profile, if available.
![TT python2](https://github.com/user-attachments/assets/3c091870-0e79-4acb-ac90-b88d8a05fe6c)

* Update and Merge: Existing posts are updated with any new metrics, and new posts are appended to the dataset.
![TT python3](https://github.com/user-attachments/assets/b42c93e0-96b3-4355-9160-833b28de00ee)

* Data Formatting: The updated and newly fetched posts are processed and formatted uniformly.

* Save as CSV: The final, merged dataset is saved as a CSV file for further analysis in Power BI.
![TT python4](https://github.com/user-attachments/assets/54d8c788-de0c-421e-b37d-33db94ff51fe)

# TOOLS
Python: This was used requesting for the data from Tiktok, transforming, updating and converting the data from Json to CSV file
Power BI: Employed for the main analysis and data visualization, enabling the extraction of key insights through DAX measures and visual tools.

# DATA PROCESSING
Data Preparation in Power BI:
After loading the cleaned data into Power BI, the following transformations and enhancements were made:

* Date column breakdown: Date was extracted from Date/Time column
![TT date column](https://github.com/user-attachments/assets/158ceaf3-6534-4701-aab8-412be94ebe29)
* Duration column: Duration was changed from milliseconds to HH:MM:SS (Total Play Time)
* Creation of some new columns for dax formulars:
     Engagement Rate per post column
  ![TT eng column](https://github.com/user-attachments/assets/4bc183e4-2c18-431e-9e4c-1371079df6cc)
  
     Duration Bin and view bin column
![TT view bin col](https://github.com/user-attachments/assets/194d821d-14d4-421a-b237-7f8b7ffa1b04)

# SKILLS DEMONSTRATED
This analysis involved multiple data processing and analytical techniques, including:

Data Scraping & Transformation: Scraing data, converting it to Csv and cleaning it in PowerBI.
Data Processing & Cleaning: Structuring data using Power Query.
Data Analysis & Quick Measures: Creating meaningful insights with DAX measures in Power BI.
Visualization & Reporting: Presenting findings in a clear and actionable format.
Critical Thinking & Problem-Solving: uncovering the types of TikTok content that drive the highest engagement and identifying patterns in user interactions.

# DATA ANALYSIS AND VISUALIZATION
The analysis reveals several key insights related to the posts performances

## Key Performance Indicators (KPIs)
* Total Posts (123):
Shows consistent content creation and effort over six months, laying the foundation for audience growth.
![TT total post](https://github.com/user-attachments/assets/b5a5d5cf-c6c7-40f1-8d7e-972e3940450a)

* Total Views (1,000,000):
A strong indicator of reach—demonstrates successful visibility and potential virality of the content.
![TT total views](https://github.com/user-attachments/assets/fd333911-e272-422f-8a65-d190bb91032a)

* Average Engagement (688.48):
On average, each post attracted nearly 700 combined likes, comments, and shares—pointing to good interaction levels.
![TT avg eng](https://github.com/user-attachments/assets/3ec8762b-aaa8-4a06-b70d-777391cc880c)

* Total Likes (74,000):
Likes alone account for a significant portion of engagement, signaling positive reception from viewers.
![TT total likes](https://github.com/user-attachments/assets/72645e15-dec8-4a57-bd44-2fa4a85bd4a8)

* Engagement Rate (7.71%):
Above-average engagement rate (compared to TikTok’s typical 3–6%), suggesting the content resonates with the target audience.
![TT eng rate](https://github.com/user-attachments/assets/e1c8935d-5aae-4c28-80d1-0bd43ddf27c3)

* Average Playtime (1 min 59 secs):
Indicates strong viewer retention, especially for a platform known for short-form content.
![TT avg pt](https://github.com/user-attachments/assets/bdc4c9fe-e4ef-41b2-956b-a957c1e62255)

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
![TT eng by des](https://github.com/user-attachments/assets/fa923d67-dda7-4e9f-bc3d-bf0c9dbb6076)

### Views vs Duration (Matrix Chart)
* Videos Over 3 Minutes (42,628 views):
Long-form videos had the highest view count—suggesting TikTok users are willing to watch longer educational or storytelling content.

* 2–3 Minutes (134 views):
Significantly fewer views, possibly due to poor structure or lack of value depth for this middle-range length.

💡 This reveals that video length plays a major role in visibility and should be optimized accordingly.
![TT matrix](https://github.com/user-attachments/assets/22e0a01e-72a6-4712-acbc-bd0bd358cdea)

### Engagement Rate Trend (By Month & Year)
* Nov 2024 (8.06%) – Strong start in content journey.

* Jan 2025 (7.62%) – Slight drop; could be due to holiday season or algorithm shifts.

* Apr 2025 (10.93%) – Spike in engagement, likely due to highly relevant or viral posts.

📌 Monitoring month-over-month trends helps identify peak seasons and high-performing content styles.
![TT eng by yr ](https://github.com/user-attachments/assets/71335f6a-0490-4ecf-8688-211744a42f1f)

### Engagement by Day of the Week
* Monday (24,000) & Thursday (22,000):
These are peak days for audience activity. Posting on these days can maximize reach and interaction.

* Sunday (1,000):
Lowest engagement—content posted on Sundays might need to be rescheduled or boosted.

🗓️ Ideal posting days: Monday & Thursday.
![TT eng by week](https://github.com/user-attachments/assets/25138068-cec4-47ff-a76c-8eb50415655a)

### Correlation Between Views and Video Duration
* Pearson Correlation = 0.37:
A moderate positive correlation means that longer videos tend to receive more views.

💡 Viewers are more engaged when videos are longer, especially if the content is insightful or storytelling-driven.

Note: Calculated manually using Pearson’s formula, as Power BI does not currently support the CORR() function natively.
![TT view vs durt](https://github.com/user-attachments/assets/245fbd2d-c5ba-4d41-8166-0a1affe30dc9)

### Top 5 Most Liked Posts
* "Skills to Learn as a Data Analyst" (13,000 likes):
Educational, career-focused content clearly resonates most.

Other posts that combine relatable stories, clear tips, and personal experience also performed well.
![TT likes by desc](https://github.com/user-attachments/assets/4e9244ac-13a7-46a1-bfe4-4018bf49b1d9)

### Total Engagement by Hour of Day
* 11 AM (41,000) & 12 Noon (24,000):
Best-performing hours—viewers are highly active around late mornings to midday.

* 1 PM (890):
A noticeable drop—suggesting lower attention span post-lunch.

⏱️ Optimal posting time: between 9 AM and 12 PM.
![TT hr by eng](https://github.com/user-attachments/assets/7eb6bc9c-fdb6-41fa-beb0-245a49474a5a)

### Top 3 Posts by Engagement Rate (Per Post)
* "Post with No Caption" (0.74):
Surprisingly, captionless content drew more engagement—possibly due to curiosity or authenticity.

* "Grocery Shopping" (0.15) & "Let Me Know" (0.14):
Lifestyle or casual content might perform better with clearer CTA or targeted storytelling.

# DATA VISUALIZATION

# ANSWERS TO BUSINESS PROBLEMS 
Using the analysis from the dataset
### Business Question 1: Identify the types of content that generate the highest engagement rate
From the analysis of the top-performing posts, the types of content that generated the highest engagement rate were:

* Educational & Career-Oriented Content:
      "Skills to Learn as a Data Analyst" had the highest engagement (15,000 interactions).
      "How to Become a Data Analyst by April 2025" and "Getting My First Job on Upwork" also ranked high in both engagement rate and total likes.

* Authentic & Relatable Stories:
      Posts that involved personal experiences (like getting jobs or wins as a data analyst) had higher resonance and emotional connection with viewers.
      Captionless or Casual Content: Interestingly, "Post with No Caption" had the highest engagement rate per view (0.74), suggesting that simplicity and intrigue may also drive audience actions.

### Business Question 2: Discover patterns that lead to higher likes, comments, shares, and views
📊 Observed Patterns:
⏰ By Time of Day
* Best Posting Time:
     11 AM generated the highest engagement (41,000), followed by 12 Noon (24,000). Engagement significantly dropped after 1 PM, suggesting late morning is optimal.

📅 By Day of the Week
* Top Days:
    Monday and Thursday had the highest engagement, indicating these are the most active days for your audience.

⏱️ By Video Duration
* Longer Videos Perform Better:
    Videos over 3 minutes received 42,628 views, the highest across all durations. Videos between 2–3 minutes performed the worst (only 134 views).

🔄 Correlation Insight
A moderate positive correlation (0.37) was found between video duration and view count, meaning longer videos tend to receive more views.

### Business Question 3: Determine effective strategies to increase audience engagement
* Double Down on Educational Content:
    Posts that offer tips, career guidance, and skills advice get higher interaction—create more of these.

* Use Strategic Posting Times:
    Post between 9 AM and 12 PM, especially on Mondays and Thursdays, to maximize engagement.

* Prioritize Long-Form Videos (3+ minutes):
    These drive more views and allow deeper storytelling, which can boost shares and likes.

* Test Simpler Content Styles:
    Posts without captions or casual formats can perform surprisingly well. Use A/B testing to balance between structured and natural content.

* Incorporate Personal Stories:
   Sharing your journey (e.g., first job wins, struggles, milestones) creates relatability and encourages engagement.

* Highlight CTAs in Captions:
  Encourage audience interaction with clear call-to-actions like “Comment your thoughts” or “Tag a friend learning data.”

# INSIGHTS 
* Content Type Drives Engagement
    * Educational and career-focused posts like “Skills to Learn as a Data Analyst” and “How to Become a Data Analyst by April 2025” consistently ranked highest in 
      engagement and views.
    * Personal storytelling content, such as “Getting My First Job on Upwork”, also resonated well with your audience.
    * Interestingly, the “Post with No Caption” recorded the highest engagement rate (0.74), showing that curiosity-driven or minimalist posts may perform exceptionally 
      well.

*  Longer Videos Attract More Views
     * Videos over 3 minutes received 42,628 views, the highest across all durations.
     * A Pearson correlation coefficient of 0.37 suggests a moderate positive relationship between video duration and view count—longer videos tend to gain more attention.

* Best Posting Times and Days
    * Monday (24K engagements) and Thursday (22K) had the highest engagement rates by day of the week.
    * 11 AM is the best-performing hour, followed by 12 Noon and 9 AM, indicating that mid-morning is peak activity time for your audience.

* Engagement Trends Over Time
    * Engagement rate peaked at 8.06% in November 2024, dipped slightly in January, and then increased to 10.93% by April 2025. This trend suggests that content quality or 
      topic relevance improved over time.

# LIMITATIONS
* The analysis focuses on likes, comments, shares, and views. It does not include follower growth, saves, watch-through rate, or audience demographics, which are key for a deeper understanding.

* While the correlation of 0.37 is useful, it only measures linear relationships. Non-linear relationships between video attributes and engagement may have been missed.

* Since the dashboard updates in real-time, metrics can shift daily, making it necessary to freeze data points when presenting or comparing over time.

* The analysis did not fully separate the effects of captions, hashtags, or sound usage, which are known to impact discoverability and engagement.

# RECOMMENDATIONS
* Continue to create content around career advice, data skills, and freelancing stories, as these clearly drive engagement.

* Post content between 9 AM – 12 PM, especially on Mondays and Thursdays, to align with peak user activity.

* Keep creating videos over 3 minutes—they not only drive higher views but also give you more room to educate, engage, and build trust.

* Experiment with different caption lengths, tones, and CTA styles to determine what boosts engagement per post.

* Explore Data Beyond Engagement: Which are Follower growth over time, Audience retention, Most effective sound trends, Performance of posts by format (e.g., storytelling vs. tutorial)

* Implement a snapshot report at the start of each month to track changes and prevent real-time data shifts from skewing insights.


