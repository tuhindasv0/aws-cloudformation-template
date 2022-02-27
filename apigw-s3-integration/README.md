#### S3 Integration with API GateWay

This section demonstrates the Integration between S3 and API gateway. 

**About the Template file**
The **apigw-s3-integration.yaml** file will create a s3 bucket and API gateway with two endpoint. One to get the file content and another to upload or update a file content in bucket.

**Command to Create Cloudformation Stack**
    
    aws cloudformation create-stack --stack-name api-gateway-integration --template-body file://apigw-s3-integration.yaml

Once the Resources are created Upload the *userDetails.json* file in s3 Bucket or alternatively use **PUT** method to upload the file in s3 Bucket.
![](https://github.com/tuhindasv0/aws-cloudformation-template/blob/master/apigw-s3-integration/putMethod.png)


**More resource: https://docs.aws.amazon.com/apigateway/latest/developerguide/integrating-api-with-aws-services-s3.html#api-folder-operations-as-s3-bucket-actions**