# Hotel-Reviews
Exploring NLP modeling



## Data Cleaning for NLP Modeling Hotel Reviews

Customer reviews are vital in understanding how a company can focus its attention on maintaining and growing its customer base. This is especially important in the hospitality industry where customers’ brand loyalty relies on consistent, positive experiences for frequent travelers. Text data is time consuming to process and it can be difficult to get an understanding of subtle trends in the data without cross checking reviews to see if keywords are predictive of an overall rating.  To aid this effort I am going to analyze customer feedback from an internationally operating hotel company. My goal is to build a model that can predict an overall positive or negative rating, based on common keywords in review.  Once a reliable model has been developed I can deliver the keywords to company management teams responsible for improving customer experience. These insights will inform them as to what the hotels are doing well and where they can improve. 

In this post I am going to explore and clean the dataset in preparation for modeling. I use `Pandas` and `Matplotlib` to explore the data and clean up issues. I also use `SKLearn.feature_extraction.CountVectorizer` to parse the text reviews and add sparse matrices to the core data. In the follow up post I will compare several machine learning models to predict a positive or negative customer review based on their feedback and extract the relevant keywords for positive and negative reviews. 

This post can be found on my 
[Gitpage](www.russ-kibat.github.io/Hotel-Review-1). 
