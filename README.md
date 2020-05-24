# **HVGN Backend Pipeline CloudFormation template**

![Pipeline Diagram][Pipeline]

### 1. Backend code with Serverless Framework template is committed to CodeCommit.
### 2. Backend is packaged for development and production using Serverless Framework.
### 3. Backend intrastructure is deployed to development using Serverless Framework.
### 4. Manual approval step to decide whether to deploy infrastructure to production.
### 5. Backend intrastructure is deployed to production using Serverless Framework.


[Pipeline]: https://github.com/badgerduke/hvgn-backend-pipeline/blob/master/hvgn-backend-pipeline.png