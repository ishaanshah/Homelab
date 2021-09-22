# Homelab

Repository containing scripts, configurations and other stuff used in my homelab setup

## IPv6 Configuration
LibreELEC doesn't enable IPv6 by default.
```bash
connmanctl config <service_name> ipv6 manual <static ipv6 address> 64 <link local ipv6 gateway address>
```

The list of services can be found by running:
```bash
connmanctl services
```
