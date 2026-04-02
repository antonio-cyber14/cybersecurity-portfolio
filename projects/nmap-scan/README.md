# Network Scan with Nmap

## Objective
Discover devices on a local network and understand network visibility.

## Tool Used
- Nmap (Network Mapper)

## Command Used
nmap -sn 192.168.1.0/24

## Explanation
- `-sn` performs a ping scan (no port scan)
- Scans the entire subnet to find active devices

## Steps Taken
1. Installed Nmap
2. Opened Command Prompt
3. Ran the scan command
4. Observed the list of active devices

## Findings
- Identified multiple devices on the network
- Each device had an IP address
- Some devices responded while others did not

## Security Insight
- Network scanning reveals the attack surface
- Helps identify unknown or unauthorized devices

## What I Learned
- Nmap is used for network discovery
- Every connected device can be detected
- Visibility is the first step in security