# Bucket Access Denied

## Possible Causes & Fixes

- Using the wrong Access Key or Secret Key
- Trying to access a bucket that does not exist
- Bucket name contains uppercase letters or invalid characters
- Using the wrong endpoint (:8080 is required)

Quick test:

aws s3 ls --endpoint-url https://s3.computus.io:8080
