we use to automatically selected the number of features chosen by RFE, this can be achived by performancing cross-validation of diffrent numbers of features as we did in the previous selection and automatically
selecting the number of features that resulted in the beat mean score, The RFECV class  is configured just like RFE class regarding the choice of the algorithm that is wrapped.
in this problem , we can see the RFE that uses a decision tree and automatically slected a number of features and then fits a decision tree on the selected features achives a classification accuracy of about
88.6 percent.
