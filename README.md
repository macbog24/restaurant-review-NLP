# restaurant-review-NLP
1.	Code environment
a.	Python 3.7 via Jupyter Notebooks was used to create this solution.
Word cloud inspiration: https://courses.cognitiveclass.ai/courses/course-v1:CognitiveClass+DV0101EN+v1/courseware/89227024130b43f684d95376901b65c8/e7c36d2c4c6840fe8b81b97147ea9c16/
LDA Inspiration: https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/
TextBlob: https://textblob.readthedocs.io/en/dev/quickstart.html

2.	Data exploration
a.	What is the source of this data?
https://www.yelp.com/dataset
b.	Overall data structure: how many rows and columns are in this dataset?
The merged data set has 1,283,301 rows and 23 columns, when we look at just restaurants in Illinois, and drop columns we aren’t going to use, we have 4,808 rows and 18 columns.
c.	List any data cleaning steps and assumptions you make in your NLP analysis:
The three data frames used were merged on the business ID. We are assuming the mayor only cares about the state of Illinois and restaurants, so that is all we look at in this analysis. 
