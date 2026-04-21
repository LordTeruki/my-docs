# S3 Error: SignatureDoesNotMatch

This is the most common S3 error during beta.

## Fixes

1. Use the correct endpoint:
   https://s3.computus.io:8080

2. Make sure you include --endpoint-url in AWS CLI commands.

3. Verify that your Access Key and Secret Key are correct.

4. Make sure there are no extra spaces when copying credentials.

5. Check that the bucket name is correct and already exists.
