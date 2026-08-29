# Linux Networking

Hands-on Red Hat Enterprise Linux (RHEL) networking labs focused on network configuration and connection management using NetworkManager and nmcli.

## Skills Practiced

- NetworkManager
- nmcli
- Static IPv4 configuration
- DHCP configuration
- Default gateway configuration
- DNS configuration
- Network connection management
- Secondary IP addressing
- Network interface verification
- Basic network troubleshooting

## Practical Tasks

### Static IP Configuration

Configured a static IPv4 address, default gateway, and DNS server using `nmcli`.

```bash
nmcli connection modify <connection> ipv4.addresses 192.168.10.50/24
nmcli connection modify <connection> ipv4.gateway 192.168.10.1
nmcli connection modify <connection> ipv4.dns 8.8.8.8
nmcli connection modify <connection> ipv4.method manual
```

### Connection Management

Practiced activating, deactivating, and modifying network connections using NetworkManager.

```bash
nmcli connection show
nmcli connection up <connection>
nmcli connection down <connection>
```

### DHCP and Static Addressing

Practiced switching network configurations between automatic DHCP and manual static IPv4 addressing.

### Secondary IP Address

Configured an additional IPv4 address on an existing network connection.

## Verification

Network configuration was verified using commands such as:

```bash
ip addr
ip route
nmcli connection show
nmcli device status
```

## Lab Documentation

The attached lab document contains configuration steps, terminal commands, verification results, and screenshots.

## Key Takeaways

This lab provided hands-on experience with RHEL network configuration using NetworkManager and nmcli, including static addressing, DHCP, DNS, gateways, connection management, and secondary IP configuration.
