# Amazon ECS\-Optimized Amazon Linux 2 AMI<a name="al2ami"></a>

The Amazon ECS\-optimized Amazon Linux 2 AMI is the recommended AMI to use for launching your Amazon ECS container instances\. Amazon ECS provides separate Amazon ECS\-optimized Amazon Linux 2 AMIs for x86 and arm64 architecture\.

Although you can create your own container instance AMI that meets the basic specifications outlined in [Container Instance AMIs](container_instance_AMIs.md), the Amazon ECS\-optimized Amazon Linux 2 AMI is preconfigured and tested on Amazon ECS by AWS engineers\. It is the simplest AMI for you to get started and to get your containers running on AWS quickly\.

**Note**  
Amazon ECS vends Linux AMIs that are optimized for the service in two variants\. The latest and recommended version is based on Amazon Linux 2\. Amazon ECS also vends AMIs that are based on the Amazon Linux AMI\. We recommend that you migrate your workloads to the Amazon Linux 2 variant, as support for the Amazon Linux AMI ends no later than June 30, 2020\.

The current Amazon ECS\-optimized Amazon Linux 2 AMI consists of:
+ The latest minimal version of the Amazon Linux 2
+ The latest version of the Amazon ECS container agent \(`1.25.1`\)
+ The recommended version of Docker for the latest Amazon ECS container agent \(`18.06.1-ce`\)
+ The latest version of the `ecs-init` package to run and monitor the Amazon ECS agent \(`1.25.1-1`\)

The Amazon ECS\-optimized Amazon Linux 2 AMI metadata, including the AMI ID, can be retrieved programmatically\. For more information, see [Retrieving Amazon ECS\-Optimized AMI Metadata](retrieve-ecs-optimized_AMI.md)\.

The following table lists the current Amazon ECS\-optimized Amazon Linux 2 AMI IDs by Region\.


| Region | AMI Name | AMI ID | EC2 Console Link | 
| --- | --- | --- | --- | 
| us\-east\-2 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-005930c8f6eb929ba | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=us-east-2#LaunchInstanceWizard:ami=ami-005930c8f6eb929ba) | 
| us\-east\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-011a85ba0ae2013bf | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#LaunchInstanceWizard:ami=ami-011a85ba0ae2013bf) | 
| us\-west\-2 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-08a73ef2db6c656e5 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=us-west-2#LaunchInstanceWizard:ami=ami-08a73ef2db6c656e5) | 
| us\-west\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-0d9f6edebb7a71985 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=us-west-1#LaunchInstanceWizard:ami=ami-0d9f6edebb7a71985) | 
| eu\-west\-3 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-00f450ea3c6b83ffe | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=eu-west-3#LaunchInstanceWizard:ami=ami-00f450ea3c6b83ffe) | 
| eu\-west\-2 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-078d18e79de0fab14 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=eu-west-2#LaunchInstanceWizard:ami=ami-078d18e79de0fab14) | 
| eu\-west\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-0f778fb7f41acc3b9 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=eu-west-1#LaunchInstanceWizard:ami=ami-0f778fb7f41acc3b9) | 
| eu\-central\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-0e81c199cc79782ac | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=eu-central-1#LaunchInstanceWizard:ami=ami-0e81c199cc79782ac) | 
| eu\-north\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-0308ae5298817c894 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=eu-north-1#LaunchInstanceWizard:ami=ami-0308ae5298817c894) | 
| ap\-northeast\-2 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-0e2ad4e582b9b22c2 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=ap-northeast-2#LaunchInstanceWizard:ami=ami-0e2ad4e582b9b22c2) | 
| ap\-northeast\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-0b8933b7fd93e97e9 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=ap-northeast-1#LaunchInstanceWizard:ami=ami-0b8933b7fd93e97e9) | 
| ap\-southeast\-2 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-092eb8209cbca22c9 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=ap-southeast-2#LaunchInstanceWizard:ami=ami-092eb8209cbca22c9) | 
| ap\-southeast\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-09b965b4d74a4c5e2 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=ap-southeast-1#LaunchInstanceWizard:ami=ami-09b965b4d74a4c5e2) | 
| ca\-central\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-07297d7703df5a13c | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=ca-central-1#LaunchInstanceWizard:ami=ami-07297d7703df5a13c) | 
| ap\-south\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-0a5044768ebf7ed50 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=ap-south-1#LaunchInstanceWizard:ami=ami-0a5044768ebf7ed50) | 
| sa\-east\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-09d08b8179ca0e18c | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=sa-east-1#LaunchInstanceWizard:ami=ami-09d08b8179ca0e18c) | 
| us\-gov\-west\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-x86\_64\-ebs | ami\-53325e32 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=us-gov-west-1#LaunchInstanceWizard:ami=ami-53325e32) | 

The following table lists the current Amazon ECS\-optimized Amazon Linux 2 \(arm64\) AMI IDs by Region\.


| Region | AMI Name | AMI ID | EC2 Console Link | 
| --- | --- | --- | --- | 
| us\-east\-2 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-arm64\-ebs | ami\-03c8e52026e8e08a7 | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=us-east-2#LaunchInstanceWizard:ami=ami-03c8e52026e8e08a7) | 
| us\-east\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-arm64\-ebs | ami\-0b580fabcc7e0e3af | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#LaunchInstanceWizard:ami=ami-0b580fabcc7e0e3af) | 
| us\-west\-2 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-arm64\-ebs | ami\-0acb24f4e4bf3bd0a | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=us-west-2#LaunchInstanceWizard:ami=ami-0acb24f4e4bf3bd0a) | 
| eu\-west\-1 | amzn2\-ami\-ecs\-hvm\-2\.0\.20190127\-arm64\-ebs | ami\-0dc972aea81873c0e | [Launch instance](https://console.aws.amazon.com/ec2/v2/home?region=eu-west-1#LaunchInstanceWizard:ami=ami-0dc972aea81873c0e) | 

**Topics**
+ [How to Launch the Latest Amazon ECS\-Optimized Amazon Linux 2 AMI](al2ami-get-latest.md)
+ [Amazon ECS\-Optimized Amazon Linux 2 AMI Versions](al2ami-agent-versions.md)
+ [Storage Configuration](al2ami-storage-config.md)