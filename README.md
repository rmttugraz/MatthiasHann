# MatthiasHann
This is the repository for the investigation "Use and limitations of various metrics to assess the quality of extreme sparse datasets in geotechnics".
The repository show different files. First the PDF "detailed information and interpretation" with more detailed presentation of the data sets and discussion of the results. Here alle algorithm-metric p-value tables and normalized standard deviation tables are discussed. The "Interpretation and Recommendation" and "Conclusion" is the same as stated in the scientific paper. The files "Classifier.rar" and "Regression.rar" contains the whole data sets, codes and histogram results for the investigation. The folders are numbered by the same order as in the PDF "detailed information and interpretation" explained. Also the folders are named by the titile of the scientific paper, which data set was used for the investiagion.
Every folder contains the .xlsx or .csv files with the original data set of the used scientific paper. Sometimes, there is also a preprocessed file, where the data set was preprocessed before implementing into the python code. Also the original scientific paper the folder are named after are situated there.
Also a other folder called "Calculation" is situated there. Here the three python codes for the investigation are situated. The "classifier_fit" and "regression_fit" code prepares the data set, calculates the loop and fitting the probability distributions by the package fitter. In the "classifier_std" and "regression_std" the tables with the normalized standard deviation are calculated based on the results of the "classifier_fit" and "regression_fit" code. The "Histogram" code only plots the histograms of the algorithm-metric distribuions. The folder histogram contains all histograms of this code.
