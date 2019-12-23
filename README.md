## Step 1. Create and activate an AWS Account
* https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/ 

## Step 2. Apply the AWS Credits
* https://aws.amazon.com/awscredits/  

## Step 3. Create a S3 Bucket
* How to [create a S3 bucket](https://docs.aws.amazon.com/AmazonS3/latest/user-guide/create-bucket.html)

## Step 4. Choose your Region
* Amazon SageMaker [supported regions](https://docs.aws.amazon.com/general/latest/gr/rande.html#sagemaker_region)

## Introduction to SageMaker Instance Types
* List of [SageMaker Instance Types](https://aws.amazon.com/sagemaker/pricing/instance-types/)
* Check to comply with Kaggle competition code requirements https://www.kaggle.com/c/deepfake-detection-challenge/overview/code-requirements

## Alternative to Amazon SageMaker: Introduction to Deep Learning AMIs
* AWS [Deep Learning AMIs](https://docs.aws.amazon.com/dlami/latest/devguide/what-is-dlami.html)

## Step 5. Manage/increase SageMaker Service Limits
* Check [default Amazon SageMaker Service Limits](https://docs.aws.amazon.com/general/latest/gr/sagemaker.html#limits_sagemaker)
* How to [request quota increase](https://docs.aws.amazon.com/servicequotas/latest/userguide/request-quota-increase.html)

## Step 6. Create a SageMaker Notebook
* Select [Instance Type](https://aws.amazon.com/sagemaker/pricing/instance-types/)
* Select “Create a New IAM Role”
* Select the S3 Bucket Created Above
* Select “Jupyter” or “JupyterLab” to Launch the Notebook
* Connect to GitHub/GitLab repo to access notebooks (Follow the instructions [here](https://aws.amazon.com/blogs/machine-learning/amazon-sagemaker-notebooks-now-support-git-integration-for-increased-persistence-collaboration-and-reproducibility/) to connect to a private GitHub/GitLab repo!)
* See this [sample notebook]() that uses the Amazon Customer Reviews Dataset

## Noteboook examples using Tensorflow/Keras
* 

## Notebook examples using PyTorch
* https://docs.aws.amazon.com/sagemaker/latest/dg/pytorch.html

## Step 7. Run the Notebook

## Step 8. Convert the Notebook to a Docker Image
* TODO:  Figure out these instructions

## Step 9. Run the Docker Image as a SageMaker Training Job

### Option 1 - on a Single Node / Instance

### Option 2 - on a Multiple Nodes / Instances

### Fully Replicated - Full Copy from S3 Bucket to Each Node / Instance
* TODO:  Add images from doc

### Sharded by S3 Key - Different Chunks of Data Copied from S3 Bucket to Each Node / Instance
* TODO:  Add images from doc

## Step 10. Submit your notebook 
* https://deepfakedetectionchallenge.ai/
