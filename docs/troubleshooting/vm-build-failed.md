# VM Build Failed

## Common Reasons

- No SSH key uploaded before launching the instance
- Did not select external net as the network
- Selected a flavor or image that is not available in beta
- Reached the limit of 2 VMs

## How to Fix

1. Go to Access → SSH Keys and upload a public key.
2. Delete any failed instance.
3. Launch again and make sure to:
   - Choose Ubuntu, Debian, or Rocky Linux
   - Choose Tiny, Small, or Medium flavor
   - Select external net
   - Select your SSH key

Check the instance logs in the dashboard for more details.
