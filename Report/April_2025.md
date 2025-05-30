# TIKTOK-POSTS-ANALYSIS-AND-ENGAGEMENT-INSIGHTS

# TABLE OF CONTENTS
- [DATA ANALYSIS AND VISUALIZATION](#data-analysis-and-visualization)
- [DATA VISUALIZATION](#data-visualization)
- [ANSWERS TO BUSINESS PROBLEMS](#answers-to-business-problems)
- [INSIGHTS](#insights)
- [LIMITATIONS](#limitations)
- [RECOMMENDATIONS](#recommendations)
  
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
![TT eng rate by des](https://github.com/user-attachments/assets/df32a7ed-4479-45ce-8ff3-40d3e380752d)

# DATA VISUALIZATION
![My tt dashboard](https://github.com/user-attachments/assets/a7a20412-fae9-4a5d-9031-019087b66898)

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

