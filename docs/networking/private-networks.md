# Private Networks & Experiments (Beta)

This is one of the most interesting areas for beta testing.

## How to Create a Private Network

1. Go to **Networking → Networks** in the dashboard
2. Click **Create Network**
3. Give it a name (e.g. `internal-app-net`, `database-tier`)
4. Click **Create**

You can then create subnets inside the network and attach interfaces to your VMs.

## What We Want You to Test

- Multiple private networks between your 2 VMs
- Different subnet configurations
- Inter-VM communication over private IPv4
- Any creative setups (web tier + db tier, etc.)

Please share your experiments and any issues via the Support section in the dashboard.

---

**Next:** [Subnets & Routers](routers.md)
