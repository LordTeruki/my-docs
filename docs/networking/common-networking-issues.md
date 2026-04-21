\# Common Networking Issues (Beta)



\## Cannot SSH to VM



\- Confirm you are using the \*\*public IPv6 address\*\*

\- Make sure the correct SSH key was selected during VM creation

\- Check Security Group allows port 22



\## No Internet Inside Private Networks



\- Create a router and set gateway to external net

\- Ensure the VM interface is attached to the correct network



\## Private IPv4 not working between VMs



\- Verify both VMs are attached to the same private network/subnet

\- Check firewall rules inside the VMs



Report any unusual behavior through the dashboard Support.

