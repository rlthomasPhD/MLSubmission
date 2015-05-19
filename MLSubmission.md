Project Write Up

It was hypothesized


> subsamples <- createDataPartition(y=trainingset$classe, p=0.75, list=FALSE)
> subTraining <- trainingset[subsamples, ]
> subTesting <- trainingset[-subsamples, ]
> dim(subTraining)



#The training data for this project are available here: [https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv]

#The test data are available here: [https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv]

#The data for this project come from this source: [http://groupware.les.inf.puc-rio.br/har]. If you use the document you create for this class for any purpose please cite them as they have been very generous in allowing their data to be used for this kind of assignment.

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


