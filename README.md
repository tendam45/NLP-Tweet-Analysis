# U.S. Senators' Tweets - NLP Analysis

This project analyzes tweets from U.S. Senators during the year 2020 using various natural language processing (NLP) techniques. We investigate sentiment trends, correlate tweet tone with election outcomes, and apply topic modeling to uncover prominent themes discussed during a politically significant year.

## 🔍 Objectives
- Perform sentiment analysis on senator tweets
- Explore relationships between sentiment and 2020 election outcomes
- Apply topic modeling to discover common themes
- Visualize word frequencies across parties and individuals

## 📦 Technologies & Libraries
- Python
- VADER Sentiment Analysis (NLTK)
- BERTopic (BERT + HDBSCAN)
- SentenceTransformers
- spaCy, WordNet Lemmatizer
- WordCloud
- Pandas, NumPy, Matplotlib, Seaborn

## 📊 Key Findings
- Tweets were largely neutral, but losing senators trended more negative.
- Republicans, on average, had slightly more positive sentiment.
- Major themes included COVID-19 relief, election integrity, and social justice.
- Regional and partisan variations were evident in both sentiment and topics.

## 📁 Project Structure
- `data/` - Raw and cleaned tweet + senator metadata
- `notebooks/` - Exploratory analysis, modeling workflows
- `scripts/` - Preprocessing, sentiment analysis, topic modeling
- `results/` - Visual outputs (word clouds, topic clusters)

## 🚀 Getting Started
1. Clone this repo
2. Install requirements: `pip install -r requirements.txt`
3. Run analysis notebooks or scripts


## 📌 Future Work
- Fine-tuned sentiment models for political context
- Incorporate sarcasm and irony detection
- Expand dataset to include broader political figures and timelines

## 📝 License
[MIT](LICENSE)

