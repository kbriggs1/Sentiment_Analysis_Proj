# Sentiment_Analysis_Proj

# Purpose: 

Setiment Analysis focuses on determining the sentiment of a particular topic discusses in a language. The majority of previous sentiment analysis used were on topics that discussed customer service reviews and nothing from the clinical domain. There are different contexts in which sentiment can be analyzed from. For instance, sentiment from the customer review perspective would look very different from a clinical narrative perspective. Therefore the purpose of this project is to perform a preliminary exploratory sentiment analysis on 6/1,304 clinical narratives extracted from the 2014 De-Identification longitudinal data corpus from Harvard University's medical study that analyzed predictive risk factors of Cardiac Artery Disease in diabetic patients. 

# Methods: 

Text Material: Data was extracted from the Harvard University's DBMI Data Portal: https://dbmi.hms.harvard.edu/. The documents within this portal will serve as the main source for analysis. 

Analysis for Sentiment Analysis of the Datasets will be performed through Python 3.7(Jupyter Notebook), along with the Natural Language Toolkit (NLTK). 
  Two of NLTK tools will be used: 
    The "Vader Sentiment Analysis" tool which creates positive, negative, and neutral sentiment scores of a provided text. 
    The "Word_Tokenize" tokenizer took which breaks down a text into sequences of smaller parts/words. 

# Research Goals:

The goal of this research project is to perform an exploratory sentiment analysis on the provided 6 clinical narratives. I will identify, in each each paragraph, the sentiment within each sentence of the clinical notes. To begin I will explain the necessary downloads and extractions necessary to begin the analysis, then I will upload and display the narratives I will be anaylyzing. 

   # Research Questions:
        How can NLTK be used to analyze clinical narratives when it so generally used for customer reviews or novels? 
        
        What lexical characteristics are most frequently used in clinical text?
        
        What can be revealed through the clinical narratives from calculating the sentiment per paragraph? 
        
        For analysis of this clincial corpus, when can sentiment analysis show us about the relationship between a clincian and their patient? 
        
        



