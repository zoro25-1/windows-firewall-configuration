# windows-firewall-configuration
# Task 4: Windows Firewall Configuration

## Objective
Configure and test basic firewall rules to allow or block traffic.

## Steps Taken
1. Opened Windows Firewall with Advanced Security
2. Listed current inbound rules
3. Created a rule to block TCP port 23 (Telnet)
4. Tested the rule using `telnet localhost 23`
5. Removed the rule to restore original state

## Screenshots
- Inbound Rules list
- Block rule created
- Telnet test failure

## Summary
Windows Firewall filters traffic based on rules for ports, protocols, and IPs. Blocking port 23 prevents Telnet access, which is insecure and often disabled in modern systems.
