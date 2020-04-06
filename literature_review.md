# Assignment 2. Literature Review

Victor Tran

April 5th

**Introduction**

The purpose of this research is to identify the factors that lend itself to encouraging members of society to pursue occupations that fall under the informal economy. The vast majority of farms in LMIC’s are part of the informal economy. This investigation will focus on identifying what features are prevalent in communities where the majority of workers are in the informal economy. I will accomplish this research by 1) applying geospatial data science techniques to geospatial datasets that focus on information about citizens and their environment. 2) Calculating the impact that increasing or decreasing the features would have on the productivity of the national economy. 

**Human Development Topic**

The informal economy is defined as sectors of the national economy which are not recognized by the national government and do not follow business regulations, including paying taxes (Rozo & Wrinkler). Because of this, informal businesses are generally able to be more profitable because they do not need to pay fees or taxes and can sell goods at lower prices (Bougna & Nguimkeu). However, because there is no regulation, their negative impacts on society is a concern. Informal businesses can take advantage of their employees by paying lower wages, long hours, and less safety.
The vast majority of farms are considered part of the informal sector as well, since they are run by singular households (B et al). However, the informal economy is a symptom of the vast economic inequality that is found in LMIC’s. In rural areas of many countries, access to necessities such as education, roads, and healthcare is limited. Because of this, the opportunities of people who live in the rural sector are limited to jobs such as being a farmer (Bougna & Nguimkeu). With a limitation on opportunities comes a limit on human development in these countries where the informal economy represents a majority of the overall economy. 

In order to reduce the size of the informal economy, the features that are associated with it must be addressed. This is especially relevant to Cameroon since two thirds of their economy and 90% of workers are in the informal sector (Bougna & Nguimkeu). Additionally, massive economic inequality is found in Cameroon as well, particular in. northern Cameroon (B et al). Amartya Sen defines human development as the expansion of freedoms and elimination of unfreedoms. Identifying what features are the most related to the informal economy will allow Cameroon to increase opportunities for its citizens to expand their different job opportunities, maximizing human development.  Cameroon is an interesting case for the informal sector, because the large majority of the informal sector is not agriculture based. Only 6.87 per cent was found to be in the agriculture industry, based on the 2010 General Enterprise Census (Bougna & Nguimkeu) Roughly 90% of the informal economy is based in the commerce and service industry. 

This research following Sustainable Development Goal #5, economic inequality, since we are attempting to identify what is preventing members of Cameroon from joining the formal sector by enhancing their access to resources such as education, roads and hospitals. 

**Human Development Process**

There are many agents when considering the economy, such as the workers at the bottom of the hierarchal chain who provide their labor, the managerial positions who provide entrepreneurial skills, and the government officials who regulate the businesses. The informal economy generally deals with the rural sector because many of these “businesses” are family-run farms, not massive companies. In fact, 86% of the businesses in the informal economy are run by one or two employees. However, as mentioned before, Cameroon’s informal economy is comprised mostly of the commerce and service industries. This shows that informal economies are a complex system with millions of agents which cannot all be accounted for. 

One of the main reasons that members of the community join the informal sector is because there is a lack of access to necessary facilities such as schools and highways that prevents them from having higher opportunities (Gachassin et al). Because of this, they do not have the education to be competitive in a job market, leading them to participate in jobs that require minimal education for lower pay. 

**Geospatial Data Science Methods**
In terms of the datasets used by these models, they vary in the input, with some exclusively using household survey data and some relying on a mix of survey data, cellular data, and remote sensing data. Most of the research done in terms of the economy relies on survey data. In terms of Cameroon, most of the data sources were from the national census and government run surveys. The most used dataset was the National Household Surveys, which were used by all of the research which was done specifically in Cameroon. However, the data is from 1996 and 2007, so it could be quite outdated. Gachassin et al. considers the data from the national household surveys to be holistic and captures all perspectives of poverty. It has data about household composition, health, education, employment income, and other relevant statistics. Other Cameroon specific surveys include the General Enterprise Census which has information about employment and businesses. Most of the statistics regarding the informal sector is built from this data such as the distribution of informal businesses and specializations of industries within certain regions (Bougna & Nguimkeu).
In addition to survey and census data, there is also tangentially related research related to the unemployment rate, poverty zones, and agglomeration economies that relied on more modern geospatial Data Science datasets such as call detail records and remote sensing data. Call detail records come from cellular companies willing to share the data and remote sensing data is easily available through sources such as OpenStreetMap. In addition, household survey data, Sundsoy et al. used the call detail records from a leading operator in an undisclosed Southeastern Asian country and matched it with 76,000 participants of the household survey. A plethora of types of data were present in the call detail records such as the nearest tower, number of contacts, number of text messages and phone calls per contact, internet usage, etc. Such data could be used to identify the movement patterns and the level of social interactions of phone users. 

Another type of data is remote sensing data. These are geospatial datasets collected automatically from a distance using devices such as satellites. From this, information regarding the physical features of environments can obtained, such as distance to riverways and streets, level of vegetation, and land usage of grids as small as 1 km x 1km. Steele et al. uses remote sensing data to create mappings of areas of poverty in countries. He found that a combination of call detail records and remote sensing data was most effective rather just call detail records or remote sensing data. Berchoux et al. also uses remote sensing data in addition to several sources of survey and census data to identify the physical features within the regions which are related to agricultural employment and poverty. 

Both types of data are essential: survey and census data are required to identify members of the informal economy and call detail records and remote sensing data can be used to identify the patterns shared between members of the informal economy. 

Since informal economies fall more in the realm of Economics rather than human development research, most research does not apply Data Science techniques but rather statistical models and equations to represent the situations. For example, Rozo & Wrinkler identify the pressure caused on the formal economy by internally displaced people who end up in the informal economy by using techniques such as analyzing the Columbian census counts and the counts of people being displaced from their district to calculate the Pressure Index. They then used these pressure indices to make statistic equations that model the effect internally displaced people have on production in the formal economy. 

Researchers such as B et al. and Korzeniewicz & Moran used economic statistical measures such as the Gini Index, which is used to measure the income distribution, to create mathematical models which show the level of economic inequality in Cameroon and South Asian countries, respectively. B et al. focuses on the rural side of Cameroon in their discussion while Korzeniewicz and Moran focused on the urban side of South Asian nations. 

There is a plethora of different data science techniques which could be helpful for having a better understanding of the informal economy and its employees. There are methods that uses a variety of inputs such as census data, CDR and remote sensing data that could be used to identify the importance of covariates in predicting being a member of the informal economy. 

Bengttson et al uses a combination of cellular data records and airplane ticket purchase information to create a feed-forward neural network to predict the unemployment rate in subnational regions. From this, they also identified the most important covariates connected to unemployment. 

Berchoux et al. used generalized linear models to identify the most important covariates related to agriculture employment. They clustered the regions based on urbanization and input 3000 communities based off of this clustering into the generalized linear model. They also used multilevel regression to control for variations within the communities such as differing socio-economic and ecological environments.

Steele et al. uses a hierarchal Bayesian model to identify areas of poverty based on remote sensing and call detail records. They log transformed their data to normalize it, and then used generalized linear models to identify the most important features related to poverty. They used techniques such as Akaike Information Criterion to choose the most effective GLM’s. After that, they input the top GLM’s into a hierarchal Bayesian geostatistical model to predict poverty levels at a finer scale than previously possible. 

Steves et al. uses Random Forest modeling to predict the population distribution of countries at a finer detail than was capable by the traditional census attempts. Random Forest models are a type of ensemble model, effective machine learning models which are the combination of a series of weaker machine learning models. They use a technique called bagging where only two thirds of the training data was used at any time. From this, they grew many trees and identified the importance of each covariate by identifying the out-of-bag error. 


**Discussion**

Cameroon qualifies as a proper subject for this study since it is a LMIC. The vast majority of its income comes from the informal economy, meaning that its informal sector is an essential aspect of its financial growth. 

There has been much research into the rural sector of LMIC that utilize geospatial data science methods, but there has not been much research into the urban sector of the informal economy. There are entirely different jobs found in cities that are connected to the informal economy. In addition to standard jobs such as running small mom-and-pop shops, Illegitimate markets such as sweatshops should be considered when looking at the informal economy as a whole. The rural sector is vastly different in the types of features they have such as access to roads and healthcare. Therefore, there will likely be unique differences for workers in the urban sector of the informal economy where access to infrastructure and distance to buildings is high (Todaro). In terms of data, CDR would most likely be more helpful when studying the urban sector since generally there are more cellular towers in cities and there would be more data to use. Cities in Cameroon that have the highest income inequality will be of interest such as those in northern Cameroon, which has one of the highest poverty gap indices (B et al.) Furthermore, Todaro investigates rural-urban migration, where people such as farmers move to cities in search of jobs. The types of jobs which they would qualify for would mostly be in the informal economy. Therefore, it may be helpful to either expand the informal economy in cities so there are more available jobs or reducing informal economy related features in rural areas so they will become more qualified for formal jobs. 

Once we understand the features that are connected to the urban sector in the informal economy, government officials can use this knowledge to make economic policies that could reduce the strains that force people to work in the informal economy. 

Central Research Question: What geological features are correlated with likelihood of a member of the urban sector in Cameroon having an occupation in the informal sector and what are the impacts on the overall economy when these features are adjusted either towards or against members joining the informal sector. 

**References**

[1]Bougna Lonla, T., & Nguimkeu, P. (2018, July). Spatial and sectoral heterogeneity of occupational choice in Cameroon (Technical Report No. WPS8515). Washington D.C., US: World Bank Group

[2]Berchoux, T., Watmough, G. R., Johnson, F. A., Hutton, C. W., & Atkinson, P. M. (2019). Collective influence of household and community capitals on agricultural employment as a measure of rural poverty in the Mahanadi Delta, India. Ambio, 49, 281-298. https://doi.org/10.1007/

[3]B, E.-N., Léandre, B., & Saumik, P. (2010, November). Accounting for heterogeneity in growth incidence in Cameroon (Technical Report No. WPS5464). Washington D.C., USA: World Bank.

[4]Gachassin, M., Najman, B., & Raballand, G. (2010, February). The Impact of roads on poverty reduction: A case study of Cameroon (Technical Report No. WPS5209). Washington D.C., USA: World Bank.

[5]Korzeniewicz, R. P., & Moran, T. P. (2005). Theorizing the relationship between inequality and economic growth. Theory and Society, 34, 277-316. https://doi.org/10.1007/s11186-005-4575-6 

[6]Rozo, S., & Wrinkler, H. (2019, October). Is informality good for business? The impacts of IDP inflows on formal firms (Technical Report No. WPS9035). Washington D.C., USA: World Bank.

[7]Steele, J. E., Sundsoy, P. R., Pezzulo, C., Alegana, V. A., Bird, T. J., Blumenstock, J., . . . Bengtsson, L. (2017). Mapping poverty using mobile phone and sattelite data. Journal of the Royal Society Interface, 14(127). http://doi.org/10.1098/rsif.2016.0690 

[8]Stevens, F. R., Gaughan, A. E., Linard, C., & Tatem, A. J. (2015). Mapping using random forests with remotely-sensed and ancillary data. PLoS ONE. https://doi.org/10.1371/journal.pone.0107042 

[9]Sundsoy, P., Bjelland, J., Jahani, E., Wetter, E., & Bengtsson, L. (2017). Towards real-time 
prediction of unemployment and profession. Social Informatics, 14-23. https://doi.org/10.1007/ 
978-3-319-67256-4_2

[10]Todaro, M. P. (1969). A model of labor migration and urban unemployment in less developed countries. The American Economic Review, 59(1), 138-148.
