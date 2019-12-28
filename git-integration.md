# Amazon SageMaker <> Git Integration

See also: 
* https://docs.aws.amazon.com/sagemaker/latest/dg/nbi-git-repo.html
* https://aws.amazon.com/blogs/machine-learning/git-integration-now-available-for-amazon-sagemaker-python-sdk/
* https://aws.amazon.com/blogs/machine-learning/amazon-sagemaker-notebooks-now-support-git-integration-for-increased-persistence-collaboration-and-reproducibility/

## 1. Go to the Amazon SageMaker console, and click on Git repositories > Add repository
![](img/git00.png)

## 2. Select GitHub/Other Git-based repo
![](img/git02.png)

### Provide the following information: 
* Amazon SageMaker repository name >> any repo name
* Git Repository URL >> URL to your repo
* Git credentials >> Create secret

![](img/git03.png)

* For Password, generate Github Personal Access Token with the relevant permissions:

![](img/git04.png)

* Add repository:

![](img/git05.png)

## 3. Create Amazon SageMaker Jupyter instance & attach Git

![](img/git06.png)

* Create notebook instance

![](img/git07.png)

* Select previously created Git repo

![](img/git08.png)

* Create notebook instance

![](img/git09.png)

## 4. Login to Jupyter instance

![](img/git10.png)
![](img/git11.png)
