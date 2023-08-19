# Data-Transformation
Cleaning up messy data - my journey as an aspiring data scientist
As an aspiring data scientist, I wanted to get hands-on practice cleaning real-world data. I found this great dataset of 672 data science job postings but it was pretty untidy! 

Here's how I went about tidying it up:

First, I imported the data into Pandas and poked around to see what I was working with. There was an unnecessary index column, a couple duplicate rows, and inconsistent formatting. The location and job description columns especially needed some TLC. 

I started cleaning things up - dropped the index column, removed duplicates, split the company name from the ratings. Then I rolled up my sleeves for some feature engineering! I parsed the salary range into min, max and average salaries. The full location data was parsed into a new state column. And I rifled through the job descriptions to make columns indicating required skills like Python, SQL, AWS and machine learning. 

The trickiest part was trying to determine seniority level from the job title. I built a function to classify titles into senior, intermediate or junior. Not perfect, but a decent heuristic! 

After a full day's work, I ended up with a clean dataset ready for analysis! I exported it to a CSV file to share with other aspiring data scientists and start investigating things like salary ranges, top skills and companies. 

This project gave me great practice structurally cleaning real data. I got to flex my Pandas muscles and problem-solving abilities. Data cleaning isn't the flashiest job, but it's so foundational. I'm excited to level up these skills as I continue my data science journey!
