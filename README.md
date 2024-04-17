# COVID-19 Twitter Sentiment and Topic Analysis

## Objective

The goal of this project is to uncover public sentiment and the prevalent topics of discussion concerning COVID-19 on Twitter. Through this analysis, we aim to:
- Understand public reaction during a major global event.
- Help health officials and policymakers respond effectively to the ongoing public discourse.

## Tasks
This project involves several key tasks:
- Collecting Twitter data related to COVID-19.
- Performing sentiment analysis to determine the emotional tone of tweets.
- Conducting topic modeling to identify the main themes of discussion.
- Visualizing sentiment and topic trends over time.

## Data Preparation
We utilized `pandas` and `numpy` for data manipulation tasks such as loading, merging, and cleaning datasets to create a cohesive data source for analysis.

## Methodology

### Natural Language Processing (NLP)
For NLP tasks, we used:
- `nltk` and `gensim` for text preprocessing including tokenization, lemmatization, and stopword removal.
- `TextBlob` for basic sentiment analysis, quantifying tweet sentiments through polarity and subjectivity scores.

### Topic Modeling
- We applied Latent Dirichlet Allocation (LDA) using `gensim` to identify dominant topics within the tweets and characterize the discussion themes.

### Sentiment Analysis
- Sentiment analysis was performed using `TextBlob`, focusing on calculating polarity and subjectivity scores for each tweet.

### Data Visualization
- Visualization was done using `matplotlib.pyplot` and `seaborn` to represent sentiment trends and topic distributions over time, and to showcase correlations between different variables.

## Tools and Libraries Used
- Python
- Libraries: `pandas`, `numpy`, `nltk`, `gensim`, `TextBlob`, `matplotlib.pyplot`, `seaborn`

## Dependencies
- Ensure Python 3.6+ is installed.
- Required Python packages: `pandas`, `numpy`, `nltk`, `gensim`, `TextBlob`, `matplotlib`, `seaborn`
- Installation command: `pip install pandas numpy nltk gensim textblob matplotlib seaborn`

## Results and Insights

### Sentiment Polarity Over Time
Observed a cyclical nature of sentiment polarity over time, correlating key events like lockdown announcements with noticeable dips in sentiment, reflecting public concern.

### Dominant Discussion Topics
The analysis identified prevalent topics such as public health measures and outbreak updates, with the prominence of certain topics aligning with key pandemic events.

### Public Engagement and Sentiment
Tweets exhibiting extreme sentiments (highly positive or negative) tend to garner more engagement, indicating that emotionally charged tweets capture more public attention and interaction.

### Variability in Subjectivity
Fluctuations in subjectivity suggest shifts between factual reporting and opinionated content, with periods of high subjectivity often coinciding with heightened public emotions or reactions to major events.

## Conclusion
This project synthesized sentiment and topic trends to better understand public reactions during the pandemic. The insights derived are crucial for tailoring public health messages and policies to address public sentiment effectively.
