Project Write Up


> subsamples <- createDataPartition(y=trainingset$classe, p=0.75, list=FALSE)
> subTraining <- trainingset[subsamples, ]
> subTesting <- trainingset[-subsamples, ]
> dim(subTraining)


subsamples <- createDataPartition(y=trainingset$classe, p=0.75, list=FALSE)
subTraining <- trainingset[subsamples, ] 
subTesting <- trainingset[-subsamples, ]
dim(subTraining)
head(subTraining)
dim(subTesting)
head(subTesting)


subsamples <- createDataPartition(y=trainingset$classe, p=0.75, list=FALSE)
subTraining <- trainingset[subsamples, ] 
subTesting <- trainingset[-subsamples, ]
dim(subTraining)
head(subTraining)
dim(subTesting)
head(subTesting)


