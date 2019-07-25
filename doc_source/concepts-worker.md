# Worker Environments<a name="concepts-worker"></a>

AWS resources created for a worker environment tier include an Auto Scaling group, one or more Amazon EC2 instances, and an IAM role\. For the worker environment tier, Elastic Beanstalk also creates and provisions an Amazon SQS queue if you don’t already have one\. When you launch a worker environment, Elastic Beanstalk installs the necessary support files for your programming language of choice and a daemon on each EC2 instance in the Auto Scaling group\. The daemon reads messages from an Amazon SQS queue\. The daemon sends data from each message that it reads to the web application running in the worker environment for processing\. If you have multiple instances in your worker environment, each instance has its own daemon, but they all read from the same Amazon SQS queue\.

The following diagram shows the different components and their interactions across environments and AWS services\.

![\[AWS Elastic Beanstalk Worker Tier Architecture Diagram\]](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/images/aeb-architecture_worker.png)

Amazon CloudWatch is used for alarms and health monitoring\. For more information, go to [Basic Health Reporting](using-features.healthstatus.md)\.

For details about how the worker environment tier works, see [AWS Elastic Beanstalk Worker Environments](using-features-managing-env-tiers.md)\.