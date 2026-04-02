# DHCP Troubleshooting (APIPA Issue)

## Objective
Fix a network issue where the computer was not receiving a valid IP address.

## Problem
The device received an IP address in the range 169.254.x.x (APIPA), meaning it could not reach the network or internet.

## Tools Used
- ipconfig (Windows Command Prompt)
- Router interface

## Steps Taken
1. Ran `ipconfig` to check IP address
2. Confirmed APIPA address (169.254.x.x)
3. Ran `ipconfig /release` and `ipconfig /renew`
4. Checked physical connection (Ethernet cable)
5. Verified router DHCP was working

## Findings
The system was not able to communicate with the DHCP server initially.

## Result
Successfully obtained a valid IP address and restored network connectivity.

## What I Learned
- APIPA indicates DHCP failure
- DHCP is required for automatic IP assignment2