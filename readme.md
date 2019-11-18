# Readme
## Project 4

### Assignment:
Use NLP to glean topics from 2016 presidential debate transcripts.

### File Directory:
Please review the notebooks in sequential order (0,1,2,3). There are datasets that are manipulated, pickled, and then further used as you move notebook to notebook.

0_mongoDB_AWSEC2.ipynb
**notebook objective: get text data from kaggle, https://www.kaggle.com/kinguistics/2016-us-presidential-primary-debates/version/1, into MongoDB, run a few commands to confirm data looks right in Mongo.**

1_LSA_text_cleaning
**notebook objective: Cleaning corpus, initial LSA topic modeling**

2_LDA_lemmatization
**notebook objectives: lemmatize corpus, topic modeling second approach: LDA, topic model by a part of speech**

3_NMF_Kmeans
**notebook objectives: topic modeling third approach: NMF, topic model by individual clusters out of Kmeans**


`sami_project4_deck.pdf` contains the slides I created to summarize my findings. In that deck, there are also data visualizations I made by exporting data from my notebooks into Tableau.
