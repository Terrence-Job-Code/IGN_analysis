# IGN_analysis

A [link](https://docs.google.com/presentation/d/1lVIhrhQ7M6g5zLwVqGu788gTPC_VnexnX9l8myM8scg/edit?usp=sharing) to slides of the project.

This project had essentially two goals: 
1. To see if the writing of reviewers reflected their score
2. Create some machine learning models to see how well they could predict a score based on the writing.

An additional task was added to see if GPT-2 models could be used to generate reasonable text for a review, but this wasn't fully completed. 

For the webcrawlers that gathered the data and data cleaning, look at 
1. [scraping_ign_data.ipynb](https://github.com/Terrence-Job-Code/IGN_analysis/blob/master/scraping_ign_data.ipynb)
2. [cleaning_ign_data_testing.ipynb](https://github.com/Terrence-Job-Code/IGN_analysis/blob/master/cleaning_ign_data_testing.ipynb)

The data analysis was broken up into two files:
1. [starting_eda.ipynb](https://github.com/Terrence-Job-Code/IGN_analysis/blob/master/starting_eda.ipynb) investigates some basic metrics of the raw text that I've collected, effectively the score and text length. I do some quality checks as well to see how effective cleaning the text has been.
2. In [further_data_analysis.ipynb](https://github.com/Terrence-Job-Code/IGN_analysis/blob/master/further_data_analysis.ipynb) I use the TextBlob library to give a polarity and sentiment score to each review. 
