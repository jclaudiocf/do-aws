> AWS lambda - Hello World Project

# VSCode Shortcuts

Ctrl + Shift + P
keymaps -> install Intellij keymaps

# Create a new user on AWS

name: lambda_photo_album_user
Access type
- Programmatic access
- AWS Management Console access
group name: admin_group

IAM name: lambda_photo_album_role
Policies
- AWSLambdaBasicExecutionRole

# Create a new Lambda Function

name: lambda_photo_album_lambda

# Create a s3 and lambda trigger

name: jccf-lambda-photo-album-bucket-images
trigger with lambda: lambda_photo_album_lambda

# Serverless framework

Install serverless (https://www.serverless.com/framework/docs/getting-started/)

$ npm install serverless -g
$ serverless create --template hello-world
$ serverless deploy

It's created the follows resources:
- `dev-hello-world-lambda` API Gateway
- `hello-world-lambda-dev-serverlessdeploymentbucket-1uxn2sj38npih` S3
- `hello-world-lambda-dev-helloWorld` Lambda
- `/aws/lambda/hello-world-lambda-dev-helloWorld` CloudWatch