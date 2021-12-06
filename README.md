## About This Repo

This repo have Explanatory Data Analysis. Some frequent questions were answered and invites you to explore more questions for insights.  
But  the focus in this repo is The hyper-parameter we used.  

#### Random Search
By now you have use Grid search hyper-parameters and maybe it become your de facto optimizer since you inherited from your lecturer no doublt it serves the purpose But am here to let you know otherwise.

According to the Journal of Machine Learning Research 13 (2012) 281-305. https://www.jmlr.org/papers/volume13/bergstra12a/bergstra12a.pdf

     Grid search experiments are more efficient because not all hyper-parameters are equally important to tune. Grid search experimnts allocote too many trials to the exploration of dimensions that do not matter and suffer from poor coverage in dimensions that are important. Compared with the grid search experiments of Larochelle et al. (2007), random search found better models in most cases and required less computational time.
    Random experiments are also easier to carry out than grid experiments for practical reasons
    related to the statistical independence of every trial.
    • The experiment can be stopped any time and the trials form a complete experiment.
    
    • If extra computers become available, new trials can be added to an experiment without having
      to adjust the grid and commit to a much larger experiment.
      
    • Every trial can be carried out asynchronously.
    
    • If the computer carrying out a trial fails for any reason, its trial can be either abandoned or
      restarted without jeopardizing the experiment.

###### To simplify the Above paper
I will use betting game to simplify the Random search.
Let's say you let 100 people bet a game outcome and within this 100 people five people know the game outcome (they've time-traveled from the future) but you have no idea who these time-travers are. with random search you random pick samples from the population and then focus on the ones that have a promising result than grid search where you focus on the all populations which is time cosuming and may endup with the same result as random search. Hope you understand better as my mind tries to explains.


