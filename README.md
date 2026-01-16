# Spotify-Data-Analysis

🎧 Spotify Data Analysis | Power BI Project

📌 Project Objective
Analyze Spotify music streaming data to understand listening trends, popular artists, hit songs, and user behavior using interactive Power BI dashboards.

📊 Key Business Questions
Which artists & songs are most streamed?

How do energy, danceability, and tempo affect popularity?

Which genres dominate Spotify?

How does music preference change year-wise?

What features make a song a hit?

🧾 Dataset Used
Spotify Tracks Dataset (Realistic Public Data)
Columns included:

Track Name

Artist

Album

Genre

Release Year

Popularity Score

Streams

Danceability

Energy

Loudness

Tempo

Duration (ms)

(Source: Kaggle / Public Spotify API inspired data)

📈 Power BI Dashboards (Pages)

🔹 1. Overview Dashboard
Total Streams

Total Artists

Total Tracks

Average Popularity

Top Genres (Bar Chart)

🔹 2. Artist & Song Analysis
Top 10 Artists by Streams

Top 10 Songs

Artist-wise Popularity (Tree Map)

🔹 3. Audio Features Analysis
Danceability vs Popularity

Energy vs Streams

Tempo Distribution

Duration Analysis

🔹 4. Trend Analysis
Year-wise Song Releases

Popularity Trend Over Time

Genre Growth Analysis

🛠 Tools & Skills Used
Power BI

Power Query (Data Cleaning)

DAX Measures

Data Modeling

Data Visualization

Business Insights

📌 DAX Measures

Total Streams = SUM(Spotify[Streams])

Average Popularity = AVERAGE(Spotify[Popularity])

Top Artist Streams =
CALCULATE(
    SUM(Spotify[Streams]),
    ALLEXCEPT(Spotify, Spotify[Artist])
)

💡 Key Insights
High danceability & energy songs tend to be more popular

Pop & Hip-Hop dominate total streams

Consistent growth in music releases after 2015

A small number of artists generate a large share of streams

🖼 Dashboard Design
Dark Spotify-themed UI (Black + Green)

Interactive slicers (Year, Genre, Artist)

Clean KPI cards

Mobile-friendly layout
