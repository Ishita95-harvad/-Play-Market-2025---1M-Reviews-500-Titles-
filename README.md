# -Play-Market-2025---1M-Reviews-500-Titles-

**About Dataset**

📊 Play Market 2025 - 1M Reviews, 550+ Titles

This dataset provides cleaned and structured data from the Google Play Market, featuring over 1 million user reviews, detailed metadata for 335 games and 217 applications, and processed fields for advanced analysis.

**🧾 Dataset Contents**

**apps_info.csv**

**Metadata for mobile applications, including:**

app_id: Unique identifier

app_name: Name of the app

description: Cleaned full description

score: Average user rating (0–5)

ratings_count: The number of people who rated the app(int)

downloads: Download count (int)

content_rating: Audience rating (e.g., Everyone, Teen)

section: App section/category

categories: Comma-separated genre tags

**apps_reviews.csv**

**User review data for apps:**

app_id: Links to apps_info.csv

review_text: Cleaned review text

review_score: Star rating (1–5)

review_date: Standardized timestamp

helpful_count: Upvote count for review

**games_info.csv**

**Metadata for mobile games, including:**

game_id: Unique identifier

game_name: Name of the game

description: Cleaned full description

score: Average user rating (0–5)

ratings_count: The number of people who rated the game (int)

downloads: Download count (int)

content_rating: Audience rating

section: Game section/category

categories: Comma-separated genre tags

**games_reviews.csv**

**User review data for games:**

game_id: Links to games_info.csv

review_text: Cleaned review text

review_score: Star rating (1–5)

review_date: Standardized timestamp

helpful_count: Upvote count for review

**📦 Dataset Summary**

-🧠 Cleaned and ready-to-use for NLP, sentiment analysis, or recommendation systems

-🧩 Multi-source: Games and Apps handled separately

-📅 Temporal component: All reviews include review dates

**🔢 Statistics**

📦 Applications: 217

📦 Games: 335

✍️ Total Reviews: 1,000,000+
