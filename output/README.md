# ADS Project 1:  R Notebook on the history of philosophy

### Output folder

phil_sentiments.csv (could not be pushed to repo due to size):

The phil_sentiments.csv is an intermediate csv file generated from the original history of philosophy dataset. Using NRC sentiment analysis, each sentence in the original corpus was scored with 8 emotions: anger, anticipation, disgust, fear, joy, sadness, and trust. 

Each row corresponds to one sentence. The following are the columns:

1. title - title of the work the sentence belongs to
2. author - author of the work
3. school - school of the work
4. sentence_str - the original sentence as a string
5. original_publication_date - when the work was published
6. sentences - tokenized sentence used to compute the sentiment
7. word.count - number of words in the sentence

The rest of the 8 columns correspond to the emotion scores.
