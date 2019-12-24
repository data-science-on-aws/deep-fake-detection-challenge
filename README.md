## Step 1. Create and Activate an AWS Account
* https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/ 

## Step 2. Apply the AWS Credits
* https://aws.amazon.com/awscredits/  

## Step 3. Create an S3 Bucket
* How to [create a S3 bucket](https://docs.aws.amazon.com/AmazonS3/latest/user-guide/create-bucket.html)

## Step 4. Choose a Region
* Amazon SageMaker [supported regions](https://docs.aws.amazon.com/general/latest/gr/rande.html#sagemaker_region)

## Step 5. Manage/Increase SageMaker Service Limits
* Check [default Amazon SageMaker Service Limits](https://docs.aws.amazon.com/general/latest/gr/sagemaker.html#limits_sagemaker)
* How to [request quota increase](https://docs.aws.amazon.com/servicequotas/latest/userguide/request-quota-increase.html)

## Step 6. Create a SageMaker Notebook
* Select [Instance Type](https://aws.amazon.com/sagemaker/pricing/instance-types/)
* Select “Create a New IAM Role”
* Select the S3 Bucket Created Above
* Select “Jupyter” or “JupyterLab” to Launch the Notebook
* Connect to GitHub/GitLab repo to access notebooks 
* (Follow the instructions [here](https://aws.amazon.com/blogs/machine-learning/amazon-sagemaker-notebooks-now-support-git-integration-for-increased-persistence-collaboration-and-reproducibility/) to connect to a private GitHub/GitLab repo!)

### Introduction to SageMaker Instance Types
* List of [SageMaker Instance Types](https://aws.amazon.com/sagemaker/pricing/instance-types/)
* Check to comply with Kaggle competition code requirements https://www.kaggle.com/c/deepfake-detection-challenge/overview/code-requirements

### Noteboook Examples using Tensorflow/Keras
* https://docs.aws.amazon.com/sagemaker/latest/dg/tf.html

### Notebook Examples using PyTorch
* https://docs.aws.amazon.com/sagemaker/latest/dg/pytorch.html

## Step 7. Run the Notebook
* Run this MNIST [sample notebook](examples/script/tensorflow_distributed_mnist.ipynb) using Tensorflow Distributed Training and SageMaker Script Mode.

## Step 8. Convert the Notebook to a `train.py` File in Docker Image
* Run this [sample notebook](examples/custom-sagemaker-container/notebook.ipynb)
![Parameter Server](parameter_server.png)

## Step 9. Run the Docker Image as a SageMaker Training Job

### Option 1:  Single Node / Instance
* https://sagemaker.readthedocs.io/en/stable/using_tf.html#train-a-model-with-tensorflow

### Option 2:  Multiple Nodes / Instances
* https://github.com/awslabs/amazon-sagemaker-examples/tree/master/advanced_functionality/distributed_tensorflow_mask_rcnn
![Distributed Tensorflow](distributed_tf.png)
![Multi Node Distribution](multi_node.png)
![Incremental Retraining](incremental_retraining.png)

## Step 10. Submit your Notebook and `train.py`
* https://deepfakedetectionchallenge.ai/

## Extras
### Alternative to Amazon SageMaker: Introduction to Deep Learning AMIs
* AWS [Deep Learning AMIs](https://docs.aws.amazon.com/dlami/latest/devguide/what-is-dlami.html)

### Fully Replicated - Full Copy from S3 Bucket to Each Node / Instance
![Fully Replicated Data](fully_replicated.png)

### Sharded by S3 Key - Different Chunks of Data Copied from S3 Bucket to Each Node / Instance
![Sharded by S3 key](sharded_s3.png)
