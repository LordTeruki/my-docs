# Creating Buckets

## How to Create a Bucket

You can create buckets using any S3 client (recommended) or through the S3 API.

### Using AWS CLI (Example)

aws s3 mb s3://my-first-bucket \
  --endpoint-url https://s3.computus.io:8080
