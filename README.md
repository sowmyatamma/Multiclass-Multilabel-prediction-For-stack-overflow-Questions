# Multiclass-Multilabel-prediction-For-stack-overflow-Questions

#### Goal: Given text for Questions, predict tags associated with them
#### Guidelines:
1. Pick the top 10 most occurring tags filter data for them and build your model for them 
2. You can expand your model later on 
3. Since there is no performance threshold and associated data given to you, you'll need to separate data in training/validation yourself 
4. Before directly jumping in with LSTM ( or any other model of your choice), explore this text data and see if any basic data cleaning is required.
5. Usage of Answers.csv is optional 
6. This is a multi-class - multilabel prediction problem, keep that in mind
#### About Dataset
This Dataset consists of three files
1. questions.csv: contain the title, body, creation date, closed date, score, and owner ID.
2. tags.csv: contains the tags for each id
3. answers.csv: contains the body, creation date, score, and owner ID for each of the answers to these questions.

