
The instance can be launched by simply uploading the template to AWS and creating a new stack.
This template will create a new Notebook instance  with S3 bucket and will also launch a jupyter notebook as told here in the reference video https://www.youtube.com/watch?v=dQGJZucBPsg
 
Note:

InstanceType: "ml.t2.medium" -----To make changes to the instance type 
VolumeSizeInGB: 5 -----5GB is the smallest EBS vol that we can get for a Notebook instance, Make changes here to increase the volume size.
Bucket name sagemaker15154787521 ------- this bucket will be retained even after the stack is removed
