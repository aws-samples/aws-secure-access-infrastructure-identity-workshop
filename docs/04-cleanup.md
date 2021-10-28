# Module 4: Cleanup

In the last module we will terminate the instances we built and delete the CloudFormation stack.

## Tasks

1. Terminate the Amazon EC2 Instances
2. Delete the CloudFormation Stack
3. Delete the IAM User

### Task 1: Terminate the Amazon EC2 Instances

1.You must perform the following cleanup steps using your Admin Session.

2.Go to the EC2 <a href="https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#Instances:sort=statusChecks" target="_blank">Console</a>: **Select** the following Amazon Ec2 Instances that were created as part of Module 2:
>
> * ProdEC2Instance
> * DevEC2Instance
> * ProdOnPrem
> * DevOnPrem
> * EC2ConnectInstance

3.Click on **Actions**, click on **Instance State**, and select **Terminate**. You will get a Warning, click **Yes, Terminate**.


### Task 2: Delete the AWS CloudFormation stack

1.Go to the
<a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks" target="_blank">CloudFormation Console</a>. Select the stack that has the description 'Infrastructure Identity in AWS workshop - AWS Systems Manager Sessions Manager, EC2 Instance Connect.', select **Actions** and click on **Delete Stack**. At the prompt, select **Yes, Delete**

### Task 3: Delete the IAM User
1.Go to the <a href="https://console.aws.amazon.com/iam/home?#/home" target="_blank">IAM console</a>, click on **Users**, select **MyWorkshopUser** and delete.
