## **Audience Clustering, Sentiment Analysis & Visualization**


Clustering is a critical element of marketing to allow grouping of audiences with similar tastes and profiles to optimize organizational investments to target them.  This clustering is not about the recommender system (for which I have a separate notebook and deep-dive) but rather about being able to understand audience groups.

In the notebook that you can find by clicking [here](https://github.com/ArijitChakrabarti/Clustering-Sentiment-Analysis-Visualization-Arijit/blob/main/K%20Means%20Clustering,Sentiment%20Analysis,%20Visualisation.ipynb) - I have considered 6 clusters (you can try more or less as per your understanding of the data-set) and visualised their groups.

At the same time - with the amount of unstructured reviews and posts that we see online - I used the Afinn library to do a sentiment analysis.  With just a few lines of code - it is able to parse across 3,000+ words in its data-base and output a sentiment score where the more positive the score - the better the sentiment and the more negative the score the worse the sentiment. 

Citation: -   Finn Årup Nielsen, “A new ANEW: evaluation of a word list for sentiment analysis in microblogs”, Proceedings of the ESWC2011 Workshop on ‘Making Sense of Microposts’: Big things come in small packages. Volume 718 in CEUR Workshop Proceedings: 93-98. 2011 May. Matthew Rowe, Milan Stankovic, Aba-Sah Dadzie, Mariann Hardey (editors).  

Infact you can explore further as it is able to score the sentiment analysis across multiple languages.
