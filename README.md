# Covid19-data-extraction-functions
Ipython Notebook for the Kaggle competition [COVID-19 Open Research Dataset Challenge](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge).
The aim of this repository is to provide some quality of life functions in order to extract relevant information from papers, focusing on text data. 

The notebook includes a filtering process for papers containing specific words, an extractor of sections currently set up for the Conclusions section, a countword that excludes irrelevant words and finally a text summarizer. 
This [code](https://www.kaggle.com/saga21/cord-19-data-extraction-functions/data) hosted in Kaggle.

## Kaggle competition description
From the competition [homepage](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge):
> In response to the COVID-19 pandemic, the White House and a coalition of leading research groups have prepared the COVID-19 Open Research Dataset (CORD-19). CORD-19 is a resource of over 63,000 scholarly articles, including over 51,000 with full text, about COVID-19, SARS-CoV-2, and related coronaviruses. 
> This freely available dataset is provided to the global research community to apply recent advances in natural language processing and other AI techniques to generate new insights in support of the ongoing fight against this infectious disease. 
> There is a growing urgency for these approaches because of the rapid acceleration in new coronavirus literature, making it difficult for the medical research community to keep up.

## Table of contents
1. Filter papers by word occurrences
2. Extract the conclusions section
3. Most common words in conclusions by topic
4. Text summarization

### Dependencies
- [IPython](http://ipython.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [SciKit-Learn](https://scikit-learn.org/stable/)
- [SciPy](https://www.scipy.org/)
- [SpaCy](https://spacy.io/)
- [Natural Language Toolkit](https://www.nltk.org/)
- [Matplotlib](https://matplotlib.org/)

## Contributors
Patrick Sánchez Galea ([Kaggle profile](https://www.kaggle.com/saga21))


