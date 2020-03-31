**Nieves et a. use the random forest machine learning method to predict what value globally?**

They use the Random Forest method to predict population density to identify the population distribution within countries on a finer scale than administrative boundaries

**Describe in detail how random forest works.**  

Random Forest is an ensemble which takes a series of machine learning models and combines them into a better model. They make decision trees from this random Forest and use them to identify OOB error for covariates, which is used to identify covariate importance and can be used to continually improve the random forest. 

**What is a dasymmetric population allocation?**

Dasymetric population allocation refers to making population data at a smaller scale. The researchers use gridcells in this work. It takes the census data and population counts from the administrative boundaries and allocates the counts into smaller sections within, making finer data. This is done by creating the weighted layer of population density using the Random Forest technique and applying to the layer of population data based on administrative boundaries. 

**Which geospatial covariates proved to be the most important when predicting global values of where humans reside?**
	
The authors found that Urban/suburban extents, Built environment and urban/suburban proxies, Climatic/environmental variables, Populated place coverage, Transportation networks work the most important covariates for predictin population density globally. They found that covariates relating to urban and topographical features were the most important covariates for prediction. 
