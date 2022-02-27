#### S3 Integration with API GateWay

This section demonstrates the Integration between S3 and API gateway. 

**About the Template file**
The **apigw-s3-integration.yaml** file will create a s3 bucket and API gateway with two endpoint. One to get the file content and another to upload or update a file content in bucket.

**Command to Create Cloudformation Stack**
    
    aws cloudformation create-stack --stack-name api-gateway-integration --template-body file://apigw-s3-integration.yaml

**More resource: https://docs.aws.amazon.com/apigateway/latest/developerguide/integrating-api-with-aws-services-s3.html#api-folder-operations-as-s3-bucket-actions**