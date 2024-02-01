# [NAME OF CLINIC REMOVED] Annual Prevention Plan

### Abstract
A variety of quantitative and qualitative methods were used to analyze the text from [CLINIC]’s 2022 annual prevention plan data collection. Of the 182 respondents, most were Junior [SERVICE MEMBERS] and those who had a longer connection to [LOCATION] and the [DOD SERVICE COMPONENT] reported more familiarity with the [CLINIC]. Suggestions to what else [CLINIC] Specialists can do to support [SERVICE MEMBERS] and their families were provided. The impression of the relationships [SERVICE MEMBERS] have with their children was more positive than the impressions with their significant others. A neutral sentiment was observed for command’s approach to family violence with most reporting not knowing their command’s approach.

### Design
A semi-structured interview question set was provided online via Qualtrics and answered by 182 respondents in the [NAME OF INSTALLATION] community. This data was collected to supplement [CLINIC]’s annual prevention plan. 

### Data
The question set contained 16 questions and responses were mostly provided as free text (i.e., not multiple choice or categorized responses). All features underwent data cleaning to allow the appropriate analysis depending on the feature. All analysis was performed in Python via Jupyter Notebooks to allow for reproducible analyses and syntax.

### Algorithms 
Feature Engineering: Questions 1, 2, 4, 6, 8, 12, and 16 were feature engineered to be numeric and coded. Varying corpi and document term matrices were created on questions 5, 7, 8, 9, 10, 11, 13, and 14 to allow for textual analysis. 

### Exploratory Analysis
Respondents were mostly Juniors (E1-E3), new to [LOCATION], and new to the [DOD]. Majority reported they think there are no child/domestic abuse problems in [LOCATION]. Respondents that were familiar with [CLINIC] services had a longer connection to the [DOD] and [LOCATION] compared to those who were not familiar. A world cloud was created to display the most common words to what respondents did know about [CLINIC] and their prevention services, which revealed a mostly accurate depiction of services.

### Textual Analysis
Topic modeling suggested classroom learning, campaigns, advertisements other than flyers, and command training and involvement would be beneficial from [CLINIC] Specialists. Sentiment analysis was performed on questions 10, 11, and 14. A more negative sentiment was found for the impression [SERVICE MEMBERS] have with their significant others than their children. A neutral sentiment was found for respondents’ command’s approach to family violence.

### Tools
Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn, NLTK, wordcloud, VADER sentiment, gensim

### Communication
The analyses for questions 1-16 can be observed in Enclosure 1.
