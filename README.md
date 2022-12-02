# House-Price-Pridiction
* I'VE TRAINED MODEL USING **LINEAR REGRESSION, DECISION TREES, RANDOM FOREST, SVM and KNN**.<br>
* I've found out that **RANDOM FOREST** classifies the best as it had better accuracy and predicted almost the same.<br>
* I've calculated **training, testing, validation accuracies** for all classifiers.<br>
* Then made a table to compare the estimated values and acutal values for each classifier.<br>
* Have also plotted graphs between estimated and actual values <br>

## Process:
<br>
1. Imported libraries<br>
2. Data exploration and Data cleaning<br>
3. Data visualization<br>
4. Correlation between features<br>
5. Splitting the data<br>
6. Training the model using:<br>
> 1. Linear regression<br>
> 2. Decision Tree<br>
> 3. Random forest<br>
> 4. SVM<br>
> 5. KNN<br>

## Comparision:
<br>
|----------------------------- |error-------------|-------train accuracy--------|------cross val score------|
<br>
|Linear regression--------- | 0.170------------|----------0.564--------------|------------0.545-----------|
<br>
|Decision tree-------------- | 0.238------------|----------0.966--------------|------------0.483-----------|
<br>
|Random forest------------ | 0.159------------|----------0.940--------------|------------0.689-----------|
<br>
|SVM------------------------ | 0.197------------|----------0.560--------------|------------0.536-----------|
<br>
|KNN------------------------ | 0.166------------|----------0.784--------------|------------0.558-----------|
<br>
|---------------------------------------------------------------------------------------------------------------|<br>

**ERROR:** As we can see that Random forest has least error percentage, in terms of errors RANDOM FOREST IS BEST.<br>
**Train accuracy:** In terms of training accuracy decision trees were best. Then random forest. <br>
**validation score:** The validation score was best for Random forest again.<br>
<br>
<br>
So, I think that **RANDOM FOREST** has classified best among the others as it had least error and had highest accuracies in training and validation
