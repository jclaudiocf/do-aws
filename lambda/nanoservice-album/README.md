> AWS lambda - Nanosservice Album Project

# VSCode Shortcuts

Ctrl + Shift + P
keymaps -> install Intellij keymaps

# Pre requisito
- S3 with name: 

# Create http-handler project

serverless create --template aws-nodejs --path http-handler
cd http-handler/
npm init

# Dependencies install

npm i serverless-apigw-binary --save-dev
npm i aws-sdk --save-dev
npm i uuid

# Deploy on AWS

sls deploy

# Endpoints

- upload
POST https://URL/dev/images