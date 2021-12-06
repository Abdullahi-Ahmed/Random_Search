## About This Repo

This repo Contains a list of Data preprocessing and Explanatory Data Analysis. Some frequent questions were answered and invites you to explore more questions for insights.  
But focus in this repo is The hyper-parameter we used  

#### Random Search
By now you have use Grid search hyper-parameters and maybe it become your de facto optimizer since you inherited from your lecturer no doublt it serves the purpose But am here to let you know otherwise.

According to the ![Journal of Machine Learning Research 13 (2012) 281-305] https://www.jmlr.org/papers/volume13/bergstra12a/bergstra12a.pdf

Random search are more efficient than grid search for hyper-parameter optimization  in several learning algorithm cases on many data sets as shown in Journal of Machine Learning Research 13 (2012) 281-305. 
In this research paper the analysis of the hyper-parameter response funtion suggests that random search are more efficient because not all hyper-parameters are equally important to tune which in Grid search all the hyper-parameter are equally important to tune thus allocate too many trials to the exploration of dimensions that even do not matter and thus suffer from poor coverage in dimensions that are important also require alot of computational resource to accomplish a task then random search found better models and require less computational resource.
