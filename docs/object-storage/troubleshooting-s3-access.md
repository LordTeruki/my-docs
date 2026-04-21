# Troubleshooting S3 Access

## Common Issue: SignatureDoesNotMatch

- Make sure you are using the correct endpoint: `https://s3.computus.io:8080`
- Check that your Access Key and Secret Key are copied correctly (no extra spaces)
- Use `--endpoint-url` flag with every AWS CLI command

## Connection Refused / Timeout

- Confirm you are using port `:8080`
- Check your firewall / network supports IPv6 (some corporate networks block it)

## Access Denied

- Verify the bucket name is correct
- Check your bucket policies

Feel free to report any other issues via Support in the dashboard.
