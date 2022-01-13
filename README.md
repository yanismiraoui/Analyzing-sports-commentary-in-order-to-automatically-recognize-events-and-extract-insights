<h1> Analyzing sports commentary in order to automatically recognize events and extract insights </h1>
:arrow_right: This repo regroups the code done to investigate how we can use multiple different Natural Language Processing techniques and methods in order to automatically recognize the main actions in sports events. The aim was to extract insights by analyzing live sport commentaries from different sources and by classifying these major actions.


<h2 align="left"> DATA: :card_index_dividers: </h2>

- **events.csv** : main data file used for our analysis
- **events_cleaned.csv** : cleaned version of the main data file
- **events_sentiment** : portion of the main data file used for sentiment analysis
- **livescore30000.csv** : data scraped from the website livescore.com
- **pred_livescore30000.csv** : predictions made on the dataset scraped from livescore.com
- **pred_livescore30000_true.csv** : predictions made on the dataset scraped from livescore.com along with the true labels
- **dictionary.txt** : description of the different event types and their label
- **transcript_paralympic.txt** : transcript example of the live commentaries from the Paralympic 2021

<h2 align="left"> NOTEBOOKS: :books: </h2>

- **transcription_evaluation.ipynb** : transcribe the audio data using the Google Spech-to-Text API and evaluate its quality
- **data_analysis_xgboost.ipynb** : explore the distribution of the dataset and to perform a first analysis of the data
- **baseline_svm.ipynb** : build an SVM model carefully folllowing the methods used in the baseline
- **otherclassifiers.ipynb** : build other classification models using the same methods and cleaning processes
- **scrape_and_evaluation_commentaries.ipynb** : scrape the live commentaries of a sample of football games from livescore.com and evaluate the performance of our model on this unseen dataset
- **simple_bert_collab.ipynb** : build a BERT classification model using Google Collab
- **sentiment_bert_collab.ipynb** : analyze if sentiment analysis could help detect main events using Google Collab
- **grahics.ipynb** : build the graphics that will be presented in the research report

<br />


 :link: <a  style="display: inline;"  href="http://35.232.26.227:8050/"> Website of the demo
  
 :link: <a  style="display: inline;"  href="https://github.com/yanismiraoui/dash-models"> Github repository of the demo
  
