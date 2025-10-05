# beats-by-dre-externship
Consumer insights project for Beat by Dre: end-to-end data pipeline from review scraping to sentiment analysis and strategic recommendations.

# Beat by Dre Externship: Consumer Insights Analytics

**Summary**  
Consumer insights project for Beat by Dre — an end-to-end data analytics pipeline covering data collection, cleaning, exploratory analysis, sentiment modeling, and AI-assisted insight generation to inform brand strategy.

---

## 📘 Project Overview
This project was completed as part of the **Consumer Insights Data Analytics Externship** with **Beat by Dre**.  
The objective was to strengthen analytical proficiency by working with real consumer feedback data and turning raw product reviews into actionable insights.

### Main goals
- Collect and prepare large-scale Amazon review data for Beats products.  
- Perform **Exploratory Data Analysis (EDA)** to identify sentiment patterns and emerging themes.  
- Apply **Natural Language Processing (NLP)** techniques to classify sentiment and extract keywords.  
- Generate **AI-driven insights** and **strategic recommendations** related to product perception and marketing.

---

## 🧠 Methodology

| Stage | Description | Libraries / Tools |
|-------|--------------|-------------------|
| **Data Collection** | Scraped Amazon product reviews using API calls and `BeautifulSoup4`; ensured consistency across product lines. | `requests`, `beautifulsoup4`, `pandas` |
| **Data Cleaning** | Removed noise, standardized text, filtered missing values, and normalized ratings. | `pandas`, `numpy` |
| **Exploratory Data Analysis** | Visualized review distributions, product ratings, and keyword frequencies. | `matplotlib`, `seaborn` |
| **Sentiment Analysis** | Used `NLTK` and `Scikit-learn` to build a polarity model distinguishing positive and negative sentiment. | `nltk`, `scikit-learn` |
| **AI-Generated Insights** | Leveraged LLM-based summarization to synthesize themes from large text corpora. | `openai`, `nltk` |
| **Recommendations** | Interpreted results to provide brand-level strategic guidance. | Narrative + visualization |


## 📊 Key Results

- **Dataset size:** ~1,000 Amazon reviews across 10 products (including Beats and key competitors)  
- **Sentiment distribution:** 92.6 % positive, 5.0 % neutral, 2.4 % negative  
- **Positive themes:** *sound quality*, *comfort*, *design aesthetics*  
- **Negative drivers:** *battery life*, *price*, *durability concerns*  
- **AI-generated summaries** highlighted that most positive reviews emphasized brand reputation and comfort, while negative feedback focused on price–performance balance and longevity.

_This project was created for educational purposes during the Beats by Dre Consumer Insights Externship.
All data were collected and analyzed solely for learning and non-commercial research use._
