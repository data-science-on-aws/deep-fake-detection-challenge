## Step 1. Create and Activate an AWS Account
* https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/ 

## Step 2. Apply AWS Credits (If Applicable)
* https://aws.amazon.com/awscredits/  

## Step 3. Create an S3 Bucket
* How to [Create an S3 Bucket](https://docs.aws.amazon.com/AmazonS3/latest/user-guide/create-bucket.html)

## Step 4. Choose a Region
* Review the [Regions](https://docs.aws.amazon.com/general/latest/gr/rande.html#sagemaker_region) supported by Amazon SageMaker 

## Step 5. Manage/Increase SageMaker Service Limits
* Review the [Default Service Limits](https://docs.aws.amazon.com/general/latest/gr/sagemaker.html#limits_sagemaker) for Amazon SageMaker Service Limits
* Request a [Limit Increase](https://docs.aws.amazon.com/servicequotas/latest/userguide/request-quota-increase.html)

## Step 6. Create a SageMaker Notebook
* Select an [Instance Type](https://aws.amazon.com/sagemaker/pricing/instance-types/)
* Select “Create a New IAM Role”
* Select the S3 Bucket Created Above
* Select “Jupyter” or “JupyterLab” to Launch the Notebook
* Connect to a Public or Private GitHub or GitLab repo using [these](git-integration.md) instructions.

## Step 7. Train a Model using SageMaker Notebooks
### TensorFlow
* [**Sample TensorFlow Notebook**](tensorflow/) using Distributed TensorFlow and SageMaker.

### PyTorch
* [**Sample PyTorch Notebook**](pytorch/) using Distributed PyTorch and SageMaker.

### MXNet
* [**Sample MXNet Notebook**](mxnet/) using Distributed MXNet and SageMaker.

### Other
* To adapt a custom training script to SageMaker, please follow [**these instructions**](https://sagemaker.readthedocs.io/en/stable/using_tf.html#adapting-your-local-tensorflow-script).

## Step 8. Submit your Notebook and Trained Model to Kaggle
* **Challenge Page**:  [https://deepfakedetectionchallenge.ai/](https://deepfakedetectionchallenge.ai/)
* **Kaggle Page**:  [https://www.kaggle.com/c/deepfake-detection-challenge](https://www.kaggle.com/c/deepfake-detection-challenge)
* **Introduction**:  [https://www.kaggle.com/robikscube/kaggle-deepfake-detection-introduction](https://www.kaggle.com/robikscube/kaggle-deepfake-detection-introduction)
* **Starter Kit**:  [https://www.kaggle.com/gpreda/deepfake-starter-kit](https://www.kaggle.com/gpreda/deepfake-starter-kit)

## Extras
### AWS AI Blog
* [https://aws.amazon.com/blogs/machine-learning/aws-supports-the-deepfake-detection-challenge-with-competition-data-and-aws-credits/](https://aws.amazon.com/blogs/machine-learning/aws-supports-the-deepfake-detection-challenge-with-competition-data-and-aws-credits/)

### Introduction to SageMaker Instance Types
* List of [SageMaker Instance Types](https://aws.amazon.com/sagemaker/pricing/instance-types/)
* Check to Comply with Kaggle [Competition Code Requirements](https://www.kaggle.com/c/deepfake-detection-challenge/overview/code-requirements)

### Noteboook Examples using Tensorflow + Keras
* https://docs.aws.amazon.com/sagemaker/latest/dg/tf.html

### Notebook Examples using PyTorch
* https://docs.aws.amazon.com/sagemaker/latest/dg/pytorch.html

### Notebook Examples using MXNet
* https://docs.aws.amazon.com/sagemaker/latest/dg/mxnet.html

### Extend the SageMaker Docker Images [TODO]
* Convert the Notebook to a `train.py` File in Docker Image
* Run this **Sample Notebook TODO**
* Run the Docker Image as a SageMaker Training Job

### Extend the Deep Learning AMIs
* AWS [Deep Learning AMIs](https://docs.aws.amazon.com/dlami/latest/devguide/what-is-dlami.html)
