Project Write Up

It was hypothesized


> subsamples <- createDataPartition(y=trainingset$classe, p=0.75, list=FALSE)
> subTraining <- trainingset[subsamples, ]
> subTesting <- trainingset[-subsamples, ]
> dim(subTraining)


