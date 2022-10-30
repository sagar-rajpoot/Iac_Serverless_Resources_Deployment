# Iac_Serverless_Resources_Deployment - 


This Project is for Serverless Framwork fundamentals.
We need to Deploy AWS resources via Serverless Framwork ( Iac )

# Step 1-
- First Step install serverless on local where you use serverless
  or
  if you are using docker then you need to install serverless on docker.
command -
npm install -g serverless


# Step 2 - 
-  Create boilerplate ( basic Structure for Development )

Command-
serverless create -t aws-nodejs
it generate - handler.js , Serverless.yml , .npmignore


# Step 3 - Update Serverss and your Lambda handler


# Step 4 - Serverless Deploy command 

after this command you can see a hidden .serverless folder will get created and inside it
you can see -
- cloudformation template for create stack json
- cloudformation template for update stack json
- a zip file for your project ( like artifacts )
- Serverless-state.json ( state file for serverless)

Test Deployment






