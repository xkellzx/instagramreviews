# instagramreviews

Tableau Public Dashboard Link: https://public.tableau.com/views/instagramreviews/Dashboard2?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

This project involves text mining, data cleaning, data visualizations, and dashboards. Using a dataset with app reviews of multiple apps, I wanted to compare how each app differs in their reviews. Some may have more positive reviews while others may have more negative reviews. 

First, I utilized the tm library in R to find the frequency of each word in all of the reviews for each app's spreadsheet. I also filtered out common English words and focused on only the top 100 words. After comparing them, I discovered that they had very similar top words with one of these words being "Instagram." This made me confused as I wondered why every app would be that connected to Instagram. I then looked closer at the data itself, and I quickly realized that all the reviews, even in those labeled as other apps, were Instagram reviews. This was made obvious through wording and mentioning Instagram app features. I decided to just use this data to look further into only Instagram's reviews.

Using Tableau, I created a bubble map to easily showcase words that had a higher frequency. I then separated words into positive vs negative, manually, using green to show good reviews and red to show bad reviews. I sorted the map to have higher frequency words/bigger bubbles to appear in the middle of the map. 

Next was created the dashboard. I mimiced a phone screen display and inserted the visualization on the screen. Then, using thumbs up and thumbs down icons, I created buttons that would filter the bubble map. Clicking the green thumbs up button would filter the bubble map to only show positive words, and the red thumbs down button would show only negative words. Through this dashboard, it can easily be seen that Instagram has more good reviews than bad reviews.

Dataset from Kaggle: https://www.kaggle.com/datasets/odins0n/top-20-play-store-app-reviews-daily-update

Personal Project by Kelly Zeng
