# Networking Troubleshooting Commands

## Basic Connectivity
- `ping <IP>`  
  Tests reachability and latency.

- `tracert <domain>` (Windows)  
  Shows the path packets take.

- `traceroute <domain>` (Linux/Mac)  
  Same as tracert.

## Interface & IP Info
- `ipconfig` (Windows)  
- `ifconfig` (Linux/Mac)  
- `ip a` (Linux)  
  Shows IP addresses and interface status.

## DNS Troubleshooting
- `nslookup <domain>`  
  Checks DNS resolution.

- `dig <domain>`  
  Detailed DNS query.

## Port & Connection Checks
- `netstat -an`  
  Shows active connections and listening ports.

- `telnet <IP> <port>`  
  Tests if a port is open.

## Routing
- `route print` (Windows)  
- `ip route` (Linux)  
  Shows routing table.

## ARP
- `arp -a`  
  Displays ARP cache.

## Logs
- `eventvwr` (Windows Event Viewer)  
- `/var/log/syslog` (Linux)  
  System logs for deeper troubleshooting.
