# Using AWS CLI with S3

## Configure AWS CLI

Run this command and fill in the details:

~~~bash
aws configure --profile computus
~~~

Example values:

- Access Key ID: your key
- Secret Access Key: your key
- Default region: us-east-1
- Default output format: json

## Example Commands

### List Buckets

~~~bash
aws --profile computus \
  --endpoint-url https://s3.computus.io:8080 \
  s3 ls
~~~

### Create a Bucket

~~~bash
aws --profile computus \
  --endpoint-url https://s3.computus.io:8080 \
  s3 mb s3://my-first-bucket
~~~

### Upload a File

~~~bash
aws --profile computus \
  --endpoint-url https://s3.computus.io:8080 \
  s3 cp file.txt s3://my-first-bucket/
~~~

---

**Next:** [Using S3 Browser and Cyberduck](using-s3-browser-and-cyberduck.md)
