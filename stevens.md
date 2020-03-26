**In the reading today (Stevens et al.) use a technique to produce a high resolution description of the distribution of human populations across the globe. What is the name of the technique and describe in general and basic terms how it works?**

The authors use a technique called Random Forest which combines a series of models into one larger model, taking the best parts of each one as weights. In this instance, the authors used a number of regression models which had the input of covariate data from census and remote sensing. They used a technique to identify which covariate models were most important and then excluded any features which made zero impact on the results of the model. 

**The random forest method used by the authors is a machine learning algorithm (ensemble method). In general terms, what is a machine learning algorithm? Within the context of this study what distinguishes a data science, machine learning method (such as random forest) from previous classical statistical approaches to describing and analyzing phenomenon and events?**

A machine learning algorithm is a technique to make predictions based on certain input features  using a set of data. They can be run continuously, being provided more data will allow the model created from machine learning algorithms to provide better results. These machine learning algorithms different from classic statistical methods through the use of Big Data: an enormous set of data that cannot be easily manipulated by humans due to sheer size and messiness. Machine learning algorithms are more able to interact with the data. 

**In the reading, the authors use a number of geospatial covariates as predictors in their machine learning method. What were these geospatial covariates and approximately how big of a data set did they represent (in general terms)? What is the significance of big data in the estimation of machine learning methods for inferring the correlates and drivers of human population distributions?**

The authors used many datasets for each of the three countries that their research touched upon. They used census data and remote-sensing data (raster and vector) and subdivided them into multiple administrative levels. The size of their collection of data was quite large, but they used techniques to eliminate less relevant covariates from their models. More data is helpful in machine learning methods’ estimations because it can add additional perspectives that may be relevant and decreases the likelihood of overfitting data. 

**The authors’ results present a remarkable improvement over previous geospatial descriptions at very high resolution, of the distribution of the human population. Within the context of human development in LMICs, what is the significance of having a highly accurate description of where each person is located across planet earth?**

Being aware of populations across the world is an essential component in many activities. In terms of epidemiology, it is important to know where people are so that they can record how many people could have been in contact with a disease. In terms of aid, governments need to know where most people are to maximize effectiveness of resources. In order to develop plans for anything, we must know where people are. 

**Within the context of human development in LMICs, what is the relevance to your area of investigation in having a highly accurate description of where each household and person is located across planet earth?**

My research deals with impoverished members of the informal economy. Generally, this is comprised of mostly the agricultural sector (eg. farmers). It is helpful to recognize where farmers are and access to resources such as roads and healthcare .
