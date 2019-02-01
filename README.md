# Serverless AWS Face Recognition

## Description:
  A Serverless Amazon Web Service collection which is one click deployable and/or removable.


## Pre-requisites:
  1. [Complete the Serverless Specific pre-requirements ](https://serverless.com/framework/docs/providers/aws/guide/quick-start/)

## Deploying Services

- [sls deploy](https://serverless.com/framework/docs/providers/aws/cli-reference/deploy/)
  - deploys the whole CloudFormationStack Services to AWS
- [sls deploy -f ***functionName***](https://serverless.com/framework/docs/providers/aws/cli-reference/deploy/)
  - updates **ONLY** the lambda functionName
## Removing Services
- [sls remove](https://serverless.com/framework/docs/providers/aws/cli-reference/remove/)
  - removes all services from AWS