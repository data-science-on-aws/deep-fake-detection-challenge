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
* https://aws.amazon.com/premiumsupport/knowledge-center/manage-service-limits/ 
ml.p3.* instance types use V100 (not P100!)
* See https://www.kaggle.com/c/deepfake-detection-challenge/overview/code-requirements

## Step 6. Create a SageMaker Notebook
* Select Instance Type (TODO:  describe the defaults)
* Select “Create a New IAM Role”
* Select the S3 Bucket Created Above
* Select “Jupyter” or “JupyterLab” to Launch the Notebook
* Connect to GitHub/GitLab Repo to Access Notebooks (TODO:  Private Repo?)
* Provide sample notebook that uses Amazon Customer Reviews Dataset in Public Repo, but also include Private Repo instructions
## Recommendations for using Tensorflow/Keras
## Recommendations for using PyTorch
* https://docs.aws.amazon.com/sagemaker/latest/dg/pytorch.html
## Run the Notebook
## Convert the Notebook to a Docker Image
* TODO:  Figure out these instructions
## Run the Docker Image as a SageMaker Training Job on a Single Node / Instance
## Run the Docker Image as a SageMaker Training Job on a Multiple Nodes / Instances
### Fully Replicated - Full Copy from S3 Bucket to Each Node / Instance
* TODO:  Add images from doc
### Sharded by S3 Key - Different Chunks of Data Copied from S3 Bucket to Each Node / Instance
* TODO:  Add images from doc
## Submit to https://deepfakedetectionchallenge.ai/
