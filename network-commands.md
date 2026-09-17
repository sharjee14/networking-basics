# Network Commands

Useful beginner networking commands for troubleshooting Windows systems.

## Check IP Configuration

```powershell
ipconfig
ipconfig /all
```

Use this to check IP address, subnet mask, default gateway, DNS servers, and adapter details.

## Test Connectivity

```powershell
ping 8.8.8.8
ping google.com
```

If ping to an IP works but ping to a domain fails, the issue may be DNS-related.

## Trace Network Path

```powershell
tracert google.com
```

This shows the path traffic takes to reach a destination.

## DNS Troubleshooting

```powershell
nslookup google.com
ipconfig /flushdns
```

Use these commands to test DNS resolution and clear cached DNS records.

## Common Checks

- Confirm the network cable or Wi-Fi connection
- Check the default gateway
- Verify DNS server settings
- Restart the router or access point if required
- Compare settings with a working computer
