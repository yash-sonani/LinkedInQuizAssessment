## Question List ##

1.] Which AWS CLI command invokes a function
  1. aws lambda invoke --function ReturnBucketName outputfile.txt
  2. **aws lambda invoke --function-name ReturnBucketName outputfile.txt**
  3. aws lambda execute --function-name ReturnBucketName outputfile.txt
  4. aws lambda execute --function ReturnBucketName outputfile.txt
  
2.] It is AWS best practice to enable lambda health logging by which of these methods?

  1. **Use Lambda metrices and CloudWatch alarms.**
  2. Use S3 metrics and CloudWatch alarms.
  3. Create custom metrics within your CloudWatch code.
  4. Create custom metrics within your Lambda code.
  
3.] You can restrict the scope of user's permissions by specifying which two items in an IAM policy?

  1. **resources and conditions**
  2. events and users
  3. events and conditions
  4. resources and users
  
4.] You are performance-testing your lambda to verify that you set the memory size adequately. Where do you verify the execution overhead?

  1. S3 logs 
  2. Lambda logs
  3. **CloudWatch logs**
  4. DynamoDB logs
  
5.] How are environment variables are stored?

  1. S3 buckets
  2. none of these answers
  3. **key-value pairs**
  4. DynamoDB tables
  
6.] You are creating a Lambda to trigger on change to files in an S3 bucket. Where should you put the bucket name?

  1. in the lambda tages
  2. **in a lambda environment variable**
  3. in another S3 bucket
  4. in the lambda function code

7.] You are building an application that needs to decide how to serve content based on user characteristics(such as location  and client device), and that can be executed and served close to your user without having to be routed back to  a centralized server. What type of function do you select?

  1. Greengrass
  2. **Lambda@Edge**
  3. Async Lambda
  4. Lambda and API Gateway

8.] What are listed downstream resources based on?

  1. the Lambda nodes
  2. the IAM user
  3. the execution policy
  4. **the Lambda configuration**
  
9.] What can you use to monitor function invocations?

  1. S3
  2. API Gateway
  3. **CloudTrail**
  4. SAS

10.] What does Lambda logging include?

  1. **logging events**
  2. rotating streams
  3. advancing log groups
  4. logging streams
  
11.] You need to set up a mechanism to put controls in place to notify you when you have a spike in lambda concurrency. What should you do?

  1. **Deploy a CloudWatch alarm that notify you when function metrics exceed your threshold. Create an AWS budget to monitor costs.**
  2. Deploy a CloudTrail alarm that notify you when function metrics exceed your threshold. Create an AWS Costmonitor to monitor costs.
  3. Deploy a CloudTrail alarm that notify you when function metrics exceed your threshold. Create an AWS budget to monitor costs.
  4. Deploy a CloudWatch alarm that notify you when function metrics exceed your threshold. Create an AWS Costmonitor to monitor costs.




