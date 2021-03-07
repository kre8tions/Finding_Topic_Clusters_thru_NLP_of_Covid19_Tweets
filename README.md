# Finding Topic Clusters thru Natural Language Processing of Covid19 Tweets

2020 has been a unique year with the Coronavirus putting the world in lockdown, forcing us to adjust to “new normals” . There hasn’t been a time when people all over the world go into self-seclusion for an entire year such as we have done. Our goal is to work with twitter feeds scraped from March 30th to April 30th, 2020 and to see if we could explore some questions in this worldwide laboratory:

- What happens when we live in seclusion for an extended period of time?
- What behavioral challenges and changes occurred during this time?
- What new trends emerged, either positive or negative?
- Was there an increase in stress? Depression? Fear? Or Loneliness?
- Do people experience different stages in seclusion similar to the stages of grief? If so, what are
these stages?

The original data comes from from a kaggle dataset:  
https://www.kaggle.com/smid80/coronavirus-covid19-tweets

### Our Process:

* Prepping our data thru exploratory data analysis and data wrangling
* Cleaning, lemmatizing and tokenizing our text
* Vectorizing our processed text and start the natural learning process using scikit-learn and spaCy.
* Using KMeans Clustering to discover topical clusters
* Finally, extracting important topical keywords using Latent Dirichlet Allocation

![](https://github.com/kre8tions/Alex_Chung_Portfolio/blob/main/Images/NLP_of_Covid19_Tweets.jpg)
