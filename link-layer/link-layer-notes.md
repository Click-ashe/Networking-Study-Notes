# Link Layer Notes (OSI Layer 2)

## Purpose
The link layer is responsible for:
- Moving frames between devices on the same network
- Handling MAC addressing
- Detecting and correcting basic transmission errors

## Key Concepts
- **MAC Address**: Unique identifier for network interfaces
- **Frames**: Data packets at Layer 2
- **Switching**: Forwarding frames based on MAC addresses
- **ARP**: Resolves IP → MAC

## Common Issues
- Duplicate MAC addresses
- ARP spoofing
- Broadcast storms
- VLAN misconfiguration

## Useful Commands
- `arp -a`
- `ipconfig /all`
- `ifconfig`
- `show mac address-table`
