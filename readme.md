
PLEASE READ CAREFULLY AS THERE CAN BE ISSUES WITH RUNNING THE 'notebook' 
mainly due to library conflict and some works witth other only with specific versions.


The main program which needs to be executed is the Jupyter notebook with file name:
'uk_train_reviews.ipynb',



5. 'uk_train_reviews.html
The html output of the 'sher_khan_okra_assignment.ipynb' so that in case jupyter notebook does not run or don't have time to run then one can check this file where every input and output is clearly visible along with graphs

7. train_reviews.json
File scrapped from trustpilot which is used as input for the jupyter notebook 

The main libraries used in this assesment are as follows:
pandas==1.2.0
os (no specified version)
string (no specified version)
re==2.2.1
nltk==3.5
numpy==1.21.0
gensim==3.8.3
spacy==3.1.0
pyLDAvis==2.1.2
matplotlib==3.3.2


If you run into issues related pyLDAvis then visit following urls for help as I found some issues and work arounds here:

1. https://github.com/bmabey/pyLDAvis/issues/144
related to
vis = pyLDAvis.gensim_models.prepare(lda_model, corpus, words)
it works only with pyldavis version 2.1.1
and pandas version 1.2

2.https://stackoverflow.com/questions/46379763/typeerror-object-of-type-complex-is-not-json-serializable-while-using-pyldavi
3. https://github.com/bmabey/pyLDAvis/issues/69
related to:
TypeError: Object of type complex is not JSON serializable pyldavis


4.https://stackoverflow.com/questions/50946003/modulenotfounderror-no-module-named-pyldavis-in-anaconda-spyder
5. https://github.com/bmabey/pyLDAvis/issues/131
related to:
ModuleNotFoundError: No module named 'pyLDAvis.gensim_models'_

