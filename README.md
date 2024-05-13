# example-xdebug-php 😊

## Important for WSL2:

If you're using WSL2, make sure to follow these steps:

- Run PowerShell as administrator:

```powershell
New-NetFirewallRule -DisplayName "WSL" -Direction Inbound -InterfaceAlias "vEthernet (WSL (Hyper-V firewall))" -Action Allow
```

This command sets up a firewall rule to allow traffic for WSL. 😊