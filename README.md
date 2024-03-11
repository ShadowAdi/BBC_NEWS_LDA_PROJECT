# **topic_modelling_on-_BBC_articles**

### **Dataset**
The Dataset Was Taken From Kaggle...`BBC News Aricle Dataset`.
CSV File is also in `BBC News Train.csv Folder`.

Topic modeling has been done using LSA and LDA algorithms, after vectorizing the text in three different ways:

(1) after normal cleaning of the text corpus (punctuation removal, stopword removal, etc.),

(2) with term frequency filter,

(3) count-vectorizer.

### **Conclusions**
## **EDA Conclusion :**
* Most of the content length lies between 0-5000 but some cases the length extends upto 25,000.

* The most articles are in the business and sports categories, followed by politics, entertainment, and technology.

* The term "said" appears the most in all article.


## **Model Conclusion :**
* Even though the LSA model did segregate the contents into five topic but the result was very bad, there were mixed up words in each topic.

* So we won't be considering the LSA, and start of with LDA.

* Best log likelihood Score for the LDA model is -649716.062235419.

* LDA model Perplexity on train data is 1601.6094311751326.

*We successfully categorised the contents using the LDA method by analysing the common words related for each category.*


