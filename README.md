# Instagram_Interaction_Insights_Analysis

Introduction
- Analyzed Instagram post data, including metadata (hashtags, mentions, posting date), features (likes, comments, captions), and post types (videos/photos).
- Goal: Identify high-impact factors influencing user engagement (likes and comments).
- Approach:
1. Data cleansing and translation
2. Linear regression modeling
3. Providing actionable insights for influencers

Data Processing Workflow
1. Data Reading
2. Data Cleaning
3. Dummy Coding
4. Creating New Variables:
   - emoji_count: Number of emojis used in captions
   - Post_Activity_Intensity: People tagged by post length
   - Has_URL: Number of URLs used
5. Data Conversions

Analysis and Findings
- Regression Models:
- Likes and Comments: Determined the impact of different variables.
- Weekdays vs. Weekends: Weekdays showed better engagement than weekends.
- Micro-Influencers (<50,000 followers) vs. Macro-Influencers (≥50,000 followers):
- Macro-influencers: Focus on post timing.
- Micro-influencers: Use medium-length captions and tag users.

Insights:
- Thoughtful, high-quality posts increase engagement.
- Emojis should be minimal and hashtags relevant.
- Pictures perform better than videos.

Conclusions and Recommendations
1. Optimize posting time for maximum engagement.
2. Quality content creation is key to audience retention.
3. Use actionable strategies based on the audience type (micro or macro influencers).

Technologies Used
- Python
- Linear Regression Modeling (OLS)

  This cell demonstrates a specific analysis step or process
  




![Screenshot 2025-01-26 131520](https://github.com/user-attachments/assets/1713cbb5-7ade-4513-a962-ffee48eac333)
