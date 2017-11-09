## Project: Predict diabetes based on diagnostic measurements
* Analysis of [Pima Indians Diabetes Data Set](https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes) to predict diabetes based on diagnostic measurements using various statistical learning techniques (linear model, tree-based methods and support vector machine)
* Implement an ROC curve interactive dashboard to show the optimal cut-off threshold based on a specific True Positive Rate or False Positive Rate criterion
* Technologies: R, shinnyApp, ggplot2, glmet, MASS, gbm

### List of files ###
* project.Rmd: The main project R markdown file to generate above analyses and charts. The time to knit the code should be about 2-3 minutes. In addition to the R packages, the code also relies on three external R code files listed above for plotting and model diagnosis.
* shinnyApp.R: The main app to run ROC curve interactive dashboard 
* shinnyApp/ui.R: R file to define UI for the interactive dashboard 
* shinnyApp/server.R: R file to define logic for the interactive dashboard 