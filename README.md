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

![image](https://github.com/user-attachments/assets/90cec502-c8f6-4c32-8208-b075653d4136)

![image](https://github.com/user-attachments/assets/7b4ce4c4-33ea-4eff-944c-f8af8d77ac9c)

![image](https://github.com/user-attachments/assets/450328d8-81c4-4b22-8c83-4ca8f210bb8e)

![image](https://github.com/user-attachments/assets/66caaaf6-cfda-4b40-ad32-3134900e775c)

- CLEAN THE DATA
![image](https://github.com/user-attachments/assets/cd25a83b-7664-4f51-9de5-77e81feb45b6)

![image](https://github.com/user-attachments/assets/f320c47d-652c-468b-8476-4bb426660ef9)

![image](https://github.com/user-attachments/assets/022a6be3-ae4e-44b8-a3b0-f463a96da5cc)

- DUMMY CODING THE VARIABLES
![Screenshot 2025-01-26 132650](https://github.com/user-attachments/assets/129a3daf-fc2e-435a-a602-727fd4082cc6)

![image](https://github.com/user-attachments/assets/cf5eb3d0-7d00-459c-a9a8-44c97578cb8d)

![image](https://github.com/user-attachments/assets/a13a4889-df2c-4902-be66-57c51954cb00)

CALCULATIONG ZSCORE
![image](https://github.com/user-attachments/assets/cef6d54f-29c1-49c7-b526-1a9728856d94)

![image](https://github.com/user-attachments/assets/b4502233-e396-4c16-b6d5-f9dc2591a115)

- Correlation_matrix
![image](https://github.com/user-attachments/assets/d5d87c50-4634-42d9-bd24-52f61848525b)

- REGRESSION





