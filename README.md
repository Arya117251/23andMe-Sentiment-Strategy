🧬 23andMe Reddit Sentiment & Complaint Analysis
Analysis of Reddit posts and comments about 23andMe to uncover user pain points, sentiments, and trends. This project takes a data-driven approach to understand what users really think about 23andMe’s services, privacy, pricing, and support. Using real Reddit data, I performed text preprocessing, categorized complaints, visualized insights, and explored opportunities for improving customer experience.

🛠️ Tools & Libraries

Python 3 🐍
Pandas, NumPy → Data handling & preprocessing
Matplotlib, Squarify → Visualization & treemaps
Regex → Text cleaning
PRAW → Reddit API data extraction 💬
VADER, TextBlob, NLTK → Sentiment analysis & NLP 🧠
Jupyter Notebook → Interactive analysis 📝

🔬 Methodology

Data Handling

Loaded Reddit dataset

Removed missing or empty posts

Standardized text: lowercase, removed URLs, punctuation, numbers, and special characters

Feature Engineering

Created a clean_review field for standardized text

Defined complaint categories with trigger keywords: Privacy, Price, Accuracy, Customer Support, Waiting Time

Exploratory Analysis & Visualization

Counted occurrences of each complaint category

Flattened nested lists of complaints for analysis

Visualized results using treemap to show relative pain points

Insights

Most common complaints involve Privacy and Price

Treemap highlights categories where 23andMe could focus improvements

Can inform customer support strategies, product improvements, and transparency efforts

📊 Real-Life Applications

Customer Experience → Prioritize fixes and updates based on user complaints

Sentiment Monitoring → Track changes in user sentiment over time

Product Improvement → Data-backed insights for roadmap decisions

Social Listening → Quickly identify emerging issues on Reddit

✨ Future Improvements

Expand analysis to topic modeling or sentiment scoring

Use machine learning/NLP for automated complaint classification

Build an interactive dashboard for live Reddit monitoring

👤 Author

Arya Belhe
➗ Math Enthusiast | 💼 Aspiring Business Analyst | 📊 Data & Insights Explorer
