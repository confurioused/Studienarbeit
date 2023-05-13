
"Workhorse.ipynb" is used to iterate through dataset and save manual and automatic annotations, can be used for signal analysis and plotting
"MetricfromCSV.ipynb" reads manual and automatic annotation from csv to calculate and save metrics 
"centers.ipynb" reads manual and automatic annotation from csv and calculates the "center of gravity" of the LM starttimes 
"displayMetrics.ipynb" reads metrics from csv for analysis purposes 
"MetricfromCSV.ipynb" is used to test and display metrics using custom signals 
"Metadata.ipynb" is used to analyse the given metadata of the dataset for demographic 

The files can be run in any order as long as the required .csv exist. The cells should be run in the given order.


"centerdiffs.csv" is a list of diffrences in "center of gravity" calculated by "centers.ipynb"
"includedFiles.csv" are all the files that were used in this work


the metrics in csv files is always saved and read according to "metricNames":
metricNames = ["TP","TN","FP","FN","F1","k","Spez","Prec","Sens","Acc","NPV","SF1","Sk","SSpez","SPrec","SSens","SAcc","SNPV","mLMcount","aLMcount","mPLMcount","aPLMcount","realmPLMcount","realaPLMcount","OneToX","XToOne","LMStartDistribution_mean","LMEndDistribution_mean","LMStartDistribution_std","LMEndDistribution_std","mFourRecurringViolations","aFourRecurringViolations","doubleOverCount","doubleUnderCount","overcountedPLM","OneToXOvercount","TPTimeViolationsOvercount","XToOneUndercount","TPTimeViolationsUndercount","undercountedPLM","K","Krel","mPLMph","aPLMph"]

