Project Write Up

It was hypothesized
Summary

The purpose of this project was to build a machine learning algorithm to predict activity from activity monitors. Machine learning algorithms tested were classification decision trees and random forest methods. Additionally, 



> subsamples <- createDataPartition(y=trainingset$classe, p=0.75, list=FALSE)
> subTraining <- trainingset[subsamples, ]
> subTesting <- trainingset[-subsamples, ]
> dim(subTraining)


