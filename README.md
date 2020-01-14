[![](img/deep-fake-detection-challenge.png)](https://deepfakedetectionchallenge.ai/)

[![](img/kaggle.png)](https://www.kaggle.com/c/deepfake-detection-challenge)

### Kaggle Competition
[https://www.kaggle.com/robikscube/kaggle-deepfake-detection-introduction](https://www.kaggle.com/robikscube/kaggle-deepfake-detection-introduction)

### Deep Fake Starter Kit
[https://www.kaggle.com/gpreda/deepfake-starter-kit](https://www.kaggle.com/gpreda/deepfake-starter-kit)

### Competition Code Requirements
[https://www.kaggle.com/c/deepfake-detection-challenge/overview/code-requirements](https://www.kaggle.com/c/deepfake-detection-challenge/overview/code-requirements)

[https://aws.amazon.com/blogs/machine-learning/aws-supports-the-deepfake-detection-challenge-with-competition-data-and-aws-credits/](https://aws.amazon.com/blogs/machine-learning/aws-supports-the-deepfake-detection-challenge-with-competition-data-and-aws-credits/)

### Step 1:  Create and Activate Your AWS Account
* https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/ 

### Step 2:  Apply Your AWS Credits (If Applicable)
* https://aws.amazon.com/awscredits/  

### Step 3:  Create an S3 Bucket
* How to [Create an S3 Bucket](https://docs.aws.amazon.com/AmazonS3/latest/user-guide/create-bucket.html)

### Step 4:  Choose a Region
* Review the [Regions](https://docs.aws.amazon.com/general/latest/gr/rande.html#sagemaker_region) supported by Amazon SageMaker 

### Step 5:  Manage/Increase SageMaker Instance Limits
* Review the [Default Limits](https://docs.aws.amazon.com/general/latest/gr/sagemaker.html#limits_sagemaker) for Amazon SageMaker Service Limits
* Request a [Limit Increase](https://docs.aws.amazon.com/servicequotas/latest/userguide/request-quota-increase.html) if Needed
* Review the [SageMaker Instance Pricing](https://aws.amazon.com/sagemaker/pricing/instance-types/)

### Step 6:  Create a SageMaker Notebook Instance
* Select an [Instance Type](https://aws.amazon.com/sagemaker/pricing/instance-types/)
* Select “Create a New IAM Role”
* Select the S3 Bucket Created Above
* Select “Jupyter” or “JupyterLab” to Launch the Notebook
* Connect to a Public or Private GitHub or GitLab repo using [these](git-integration.md) instructions.

### Step 7:  Train a Model Using Your SageMaker Notebook Instance
* [**Sample TensorFlow Notebook**](tensorflow/) using Distributed TensorFlow and SageMaker.
* [**Sample PyTorch Notebook**](pytorch/) using Distributed PyTorch and SageMaker.
* [**Sample MXNet Notebook**](mxnet/) using Distributed MXNet and SageMaker.
* To adapt a custom training script to SageMaker, please follow [**these instructions**](https://sagemaker.readthedocs.io/en/stable/using_tf.html#adapting-your-local-tensorflow-script).

### Step 8:  Submit Your Trained Model to Kaggle
* [**Competition Code Requirements**](https://www.kaggle.com/c/deepfake-detection-challenge/overview/code-requirements)

Wish You Luck!
