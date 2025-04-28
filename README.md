# 2020_Twitter_Sentiment_Analysis

Analysis of Tweets about the 2020 presidential debate from October 15th until election day.

## Case Study
Document outlining case study available at ________ and rubric available at ______. Instructions available under Repoduction Instructions section.

## Software and Platform Section
Language: Python (Jupyter Notebook) <br>
Packages: Pandas, NLTK, Matplotlib, Scipy <br>
Platform: Windows, Mac <br>

## Directory
2020_Twitter_Sentiment_Analysis/ <br>
├── SCRIPTS/ <br>
│   ├── 1_data_cleaning.ipynb <br>
│   ├── 2_initial_data_exploration.ipynb <br>
│   ├── 3_natural_language_processing.ipynb <br>
│   ├── 4_data_analysis.ipynb <br>
│   ├── 4_data_analysis_2 <br>
├── DATA/ <br>
│   ├── candidate_sentiment_summary <br>
│   ├── compressed_data <br>
│   ├── debate_tweets.csv <br>
│   ├── debate_tweets_cleaned.csv <br>
│   ├── debate_tweets_with_sentiment.csv <br>
│   ├── compressed_data.csv.gz <br>
├── OUTPUT/ <br>
│   ├── before_after_debate_sentiment_analysis.png <br>
│   ├── swing_state_sentiment_analysis.png <br>
│   ├── interaction_plot_sentiment_analysis.png <br>
├── LICENSE.md <br>
├── README.md <br>

## Reproduction Instructions

Step 1: Download [dataset]([url](https://www.kaggle.com/datasets/manchunhui/us-election-2020-tweets)) from Kaggle and run the first initial code blocks in SCRIPTS/1_data_cleaning.ipynb. Alternatively, you can simply use the debate_tweets_cleaning.csv file for analysis. <br>
Step 2: Run the 2_initial_data_exploration.ipynb. This will conduct basic data exploration. <br>
Step 3: Run 3_natural_language_processing.ipynb. Run each of the code blocks in order, which saves the sentiment to the 'Compound_Score' column of the the csv file debate_tweets_with_sentiment.csv. <br>
Step 4: Run 4_data_analysis.ipynb. Run each code block in order. The first t-test look for changes in likes from before the debate to after. The second T-test looks at the changes in sentiment from before the debate to after. The final code block conducts as ANOVA. <br>
