# Sentiment_Analysis_Proj

# Purpose: 

Sentiment Analysis focuses on determining the sentiment of a particular topic discussed in a natural language (English, Spanish, etc). The majority of sentiment analysis studies are on topics that discuss customer service reviews rather than from the clinical domain. There are different contexts in which sentiment can be analyzed from. For instance, sentiment from the customer review perspective would look very different from a clinical narrative perspective. Therefore the purpose of this project is to perform a preliminary exploratory sentiment analysis on 6/1,304 clinical narratives extracted from the 2014 De-Identification longitudinal data corpus from Harvard University's medical study that analyzed predictive risk factors of Cardiac Artery Disease in diabetic patients. Through this exploratory analysis, I will determine if there are possible biases/judgements held by clinicians towards their patients, either from their current health status or medical history. The data from this study can be used for further studies to look further into whether medical bias could be instrumental in influencing treatment methods for patients. 

# Methods: 

Text Material: Data was extracted from the Harvard University's DBMI Data Portal: https://dbmi.hms.harvard.edu/. The documents within this portal will serve as the main source for analysis. 

Analysis for Sentiment Analysis of the Datasets will be performed through Python 3.7(Jupyter Notebook), along with the Natural Language Toolkit (NLTK). 
    
  # Two of NLTK tools will be used: 
    
    The "Vader Sentiment Analysis" tool which creates positive, negative, and neutral sentiment scores of a provided text. 
    
    The "Word_Tokenize" tokenizer tool which breaks down a text into sequences of smaller parts/words. 

# Research Goals:

The goal of this research project is to perform an exploratory sentiment analysis on the provided 6 clinical narratives. I will identify, in each each paragraph, the sentiment within each sentence of the clinical notes to determine if there is a pattern of medical biases by clinicians towards patients based on their medical history and/or current health status. To begin I will explain the necessary downloads and extractions needed to begin the analysis, then I will upload and display the narratives I will be anaylyzing. 

   # Research Questions:
        What is the quality of NLTK when used to assess clinial text when it is so generally used for customer reviews or novels? 
        
        What lexical characteristics are most frequently used in clinical text?
        
        What can be revealed through the clinical narratives from calculating the sentiment per paragraph? 
        
        For analysis of this clincial corpus, what can sentiment analysis show us about the judgment of a clincian on their patients' medical history and current health status? 
 
# Expected Result: 

Since this project is only a preliminary study with 6 narratives, the results will be open to larger experimentation. However, possible results to consider are intended to assess whether there are any clincial biases/judgments held by clinicians towards their patients depending on the patients' medical histories and/or current health statuses. Any evidence of this will help contribute to further medical studies on examining the relationship between medical biases and treatment methods. 
        



