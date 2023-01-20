# toxic_comment_classifier

## Current Process:
Explored the data and handled missing values, by dropping NaN comments and the volume of such cases was low and will not have  detrimental effect on the size of data.

Reused the text cleaning function from one of my previous work in NLP for academics

Split the dataset into train and test subsets with a 70/30 ratio and implemented TfIdfVecotrization to convert text to numbers

Implemented RandomForestClassifier on each target label and printed the respective metrics like accuracy, roc score and the classification matrix

## Possible Enhancements:
Due to time and CPU limitations some the default RandomForestClassifier was implemented

More advanced neural network techniques such as BERT and LSTM can be applied

Tried to keep the implementation simple hence skipped lemmatization and analysis for n-grams

Detailed text cleaning step may be required

### PS- I have added the comments for each step implemented in the notebook




