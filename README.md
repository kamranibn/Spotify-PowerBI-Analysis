# Spotify-PowerBI-Analysis
Spotify Music Trends Analysis Dashboard


📌 Business Requirement
Spotify stakeholders (music analysts, playlist managers, and marketing teams) need a consolidated dashboard to monitor song and artist performance across different dimensions.
Based on the screens provided, the business requires:
Overview Page
Track KPIs like Total Songs, Distinct Artists, Average Popularity, Avg Duration.
Compare Explicit vs Non-Explicit Songs and see their share.
Analyze Songs by Album Type (single, album, compilation).
View Distinct Songs and Avg Popularity by Year.
Trend analysis of Avg Popularity & Distinct Songs by Month.
Highlight Top Songs & Top Artists by Popularity.
Artist Page
Show Top Artists by Popularity.
Compare Tracks per Album and Songs by Artist.
Provide drill-down to artist-level data (songs, release date, avg popularity, avg position, duration).
Support identifying artists with consistent hits and #1 positions.
Songs Page
Rank Top Songs by Popularity.
Show Tracks per Song (Album/Single distribution).
Compare Songs by Song Count.
Provide detailed table with song name, release date, distinct artists, avg popularity, position, duration per year.

📌 Problem Statement
Currently, Spotify’s raw “Top 50” dataset is limited to lists and rankings, making it difficult for stakeholders to see patterns and take insights quickly.
From the screens, the key problems solved are:
No clear KPI monitoring → Dashboard provides quick summary of total songs, artists, popularity, duration, etc.
Lack of explicit vs non-explicit analysis → Users can compare how explicit songs perform vs non-explicit.
Difficulty in tracking song/album distribution → Visuals show breakdown by album type and release year.
Trend visibility missing → Popularity and distinct songs trends are shown over time (monthly & yearly).
Artist vs Song level insights not connected → Drill-down pages for Artists and Songs connect overview insights to detailed records.
Decision-making gaps → Marketing and curation teams can now identify which artists/songs to promote, trends to follow, and which content resonates with audiences.





⚙️ Tech Stack:
Power BI – for data visualization and dashboard design,
DAX queries i got from Chat gpt to make measures,
Microsoft Excel / CSV – for initial data storage and import



📊 Data Source:

The dataset used for this dashboard was obtained from Kaggle. It includes details such as song title, artist, album type, release year, duration, popularity score, and explicit content tags.

💡 Key Insights:
Total Songs: 789 distinct songs by 342 artists.
Average Duration: 3.28 minutes per song.
Average Popularity: 89.62, indicating a generally well-liked playlist.
Most Featured Artist: Taylor Swift with 85 tracks.

Top Popular Songs:
“I Wanna Be Yours” – 51K plays,
“Cruel Summer” – 50K plays,
“As It Was” – 35K plays,
Album Type Distribution: 36% singles, 34% albums, 30% compilations.
Trend by Year: Slight increase in song releases from 2023 (423 songs) to 2024 (452 songs).

Monthly Trends:
Highest distinct song additions in August (220) and November (202).
Average popularity dips mid-year but peaks around December, likely due to festive or holiday releases.
Explicit vs Non-Explicit: About 39% of tracks are explicit, 61% are non-explicit.

and Many other a lot of insights 



This Power BI dashboard provides an interactive view of the Spotify dataset, allowing users to explore music trends by artist, year, album type, and popularity metrics. It offers both summary metrics and detailed visual insights into the dynamics of modern music streaming.

Screenshot/Dem0
<img width="1171" height="655" alt="Spotify Dashboard screenshot" src="https://github.com/user-attachments/assets/e63621b4-f236-4916-b7e0-4b0993e1b0ac" />

