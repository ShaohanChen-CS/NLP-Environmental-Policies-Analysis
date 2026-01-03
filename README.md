NLP & Environmental Policies Analysis

Shaohan Chen  
Sep. 2025 – Dec. 2025

Overview
This project applies Natural Language Processing (NLP) techniques to analyze public sentiment toward environmental policies on Reddit and compare it with corporate sustainability narratives from S&P 500 ESG reports.

Problem Statement
How do public attitudes toward environmental policies differ across sectors, and how do these perspectives compare with how corporations describe sustainability in official ESG reports?

Datasets
- Reddit Comments
  - Subreddits: `Environment`, `Climate`, `Sustainability`
  - Source: *Greenwashing on Reddit* (Kaggle)
- Corporate ESG Reports**
  - S&P 500 ESG Sustainability Reports Dataset (Kaggle)

Methods
- Text preprocessing with custom stopword removal
- Sentiment analysis using **VADER**
- Word clouds and frequency analysis for qualitative comparison
- Sector-level categorization by mapping keywords to S&P 500 sectors
- Statistical aggregation of sentiment scores across sectors

Key Analyses & Visualizations
- Word clouds comparing public discourse vs. corporate ESG language
- Word frequency distributions for Reddit comments
- Scatter plots analyzing relationships between sentiment and ESG scores
- Sector-level sentiment breakdown (Technology, Materials, Utilities, Industrials, Real Estate)

Results & Insights
- Public sentiment is generally positive across environmental topics, with 'Sustainability' showing the highest positivity.
- 'Technology, Materials, and Utilities' consistently receive favorable sentiment.
- 'Industrials and Real Estate' trend more negatively in climate and environment-related discussions.
- Corporate ESG narratives tend to use more optimistic and standardized language compared to Reddit discourse.

Tools & Libraries
- Python
- NLTK / VADER
- Pandas, Matplotlib
- WordCloud
