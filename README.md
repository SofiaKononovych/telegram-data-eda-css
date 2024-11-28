# telegram-data-eda-css
# Telegram Dataset Exploratory Data Analysis for Computational Science course (2024)

The aim of this project is to explore behavioral patterns from telegram messages, make data visualization and conclusions. 
Technologies used include NLP, sentiment analysis with 

## Collecting the dataset 

1. Use Telethon Library for API 
2. Extract the raw data using [https://github.com/SanGreel/telegram-data-collection](https://github.com/SanGreel/telegram-data-collection)
3. Merge data into datasets using [https://github.com/SanGreel/telegram-dialogs-analysis-v2](https://github.com/SanGreel/telegram-dialogs-analysis-v2)

After collecting and merging raw data we work with 4 .csv files: dialogs_data_all.csv, dialogs_users_all.csv, parsed_users.csv, 
test_hypothesis_data.csv

## Sources and references
1. [Ukrainian stopwords](https://github.com/skupriienko/Ukrainian-Stopwords/tree/master)
2. [Lemmatization dict and tone dict for Ukrainian](https://github.com/SanGreel/tone-dict-ukrainian/tree/master/dicts)


## EDA structure
1. Basic EDA
2. Analysis of data by time
3. How telegram activity indicates sleeping time
4. Conversation duration in different groups
5. Users data analysis
6. NLP
7. Sentiment Analysis
8. Behavioural Analysis by Gender
