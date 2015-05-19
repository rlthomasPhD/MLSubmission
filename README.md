Project Write Up


> subsamples <- createDataPartition(y=trainingset$classe, p=0.75, list=FALSE)
> subTraining <- trainingset[subsamples, ]
> subTesting <- trainingset[-subsamples, ]
> dim(subTraining)





