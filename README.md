# terraform-code
1. creates a lambda called, DynamoDBCleanupAndArchiveNew
2. a iam role called DynamoDBLambdaExecutionRole with a policy ("DynamoDBLambdaPolicy") for dynamodb to read and write and s3 to read
3. eventbridge rule to run this lambda the beginning of everyday
