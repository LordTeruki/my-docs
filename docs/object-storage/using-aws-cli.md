# Using AWS CLI with S3

## Configure AWS CLI

Run this command and fill in the details:

```bash
aws configure --profile computus


aws --profile computus \
  --endpoint-url https://s3.computus.io:8080 \
  s3 ls

aws --profile computus \
  --endpoint-url https://s3.computus.io:8080 \
  s3 mb s3://my-first-bucket


aws --profile computus \
  --endpoint-url https://s3.computus.io:8080 \
  s3 cp file.txt s3://my-first-bucket/