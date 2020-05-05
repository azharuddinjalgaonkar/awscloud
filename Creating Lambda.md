 **WHAT IS LAMBDA CONCEPT IN AWS.

 AWS Lambda is a serverless compute service that runs your code in response to events and automatically manages the underlying compute resources for you. You can use AWS Lambda to extend other AWS services with custom logic, or create your own back-end services that operate at AWS scale, performance, and security. AWS Lambda can automatically run code in response to multiple events, such as HTTP requests via Amazon API Gateway, modifications to objects in Amazon S3 buckets, table updates in Amazon DynamoDB, and state transitions in AWS Step Functions.


 To create the Lambda function (console)

Sign in to the AWS Management Console and open the AWS Lambda console.

Choose Create function.

On the Create function page, choose Use a blueprint. Type HELLO in the filter text box and then press Enter to find the blueprint, choose the hello-world in nodejs blueprint.

Lambda function blueprints are provided in both Node.js and Python. For this exercise, use the nodejs-based blueprint.

On the Basic information page, do the following.

Type a Lambda function name.

For the execution role, choose Create a new role with basic Lambda permissions.

Leave the other default values.

Choose Create function.

Test the Lambda function.

Choose Select a test event, Configure test events.

Choose Create.

Choose Test to test the code hook.

Verify that the Lambda function successfully executed. The response in this case matches the Amazon Lex response model.

