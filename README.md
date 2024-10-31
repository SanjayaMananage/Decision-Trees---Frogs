# Decision-Trees---Frogs

I consider the Frogs data set in library “DAAG” in R set([https://cran.r-project.org/web/packages/DAAG/DAAG.pdf](https://cran.r-project.org/web/packages/DAAG/DAAG.pdf)). This dataset consists of 212 sites of the Snowy Mountain area of New South Wales, Australia. Each site was surveyed to understand the distribution of the Southern Corroboree frog. The variables are available as a dataset in R via the package “DAAG”. This data set is created for prediction of whether frogs were found or not. I take "pres.abs " as the binary response variable and consider all predictors as quantitative variables also take all the data as training data. 

Additionally For all the models I use leave-one-out cross-validation (LOOCV) to compute the estimated test MSE.
