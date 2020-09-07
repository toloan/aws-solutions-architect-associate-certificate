Serverless stack: API Gateway, Lambda, DynamoDB, Cognito, SQS, SNS... (things that automatically scale, you don't need to adminstration, provision)

## Lambda

- Lambda scales out (not up) automatically
  - Scaling out = adding more components in parallel to spread out a load.
  - Scaling up = making a component bigger or faster so that it can handle more load.
- Lambda functions are independent, 1 event = 1 function
- Lambda is serverless
- Lambda functions can trigger other lambda functions, 1 event can trigger many functions if functions trigger other functions
- AWS X-ray allows you to debug
