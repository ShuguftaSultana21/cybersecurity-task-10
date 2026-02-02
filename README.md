# cybersecurity-task-10
Firewall Configuration &amp; Testing

## Objective
To configure and test firewall rules using UFW on Kali Linux, control inbound and outbound traffic, block malicious sources, and analyze security impact.

## Tools Used
- Kali Linux
- UFW (Uncomplicated Firewall)

## Firewall Status
- Firewall: Enabled
- Default Incoming Policy: Deny
- Default Outgoing Policy: Allow
- Logging: Enabled

## Configured Rules
- Allowed SSH (Port 22)
- Allowed HTTP (Port 80)
- Blocked FTP (Port 21)
- Blocked malicious IP: 192.168.1.100
- IPv6 rules applied

## Testing
- Verified firewall rules using `ufw status verbose`
- Confirmed blocked and allowed traffic behavior
- Observed firewall logs

## Impact Analysis
- Reduced exposure to network attacks
- Unauthorized access attempts blocked
- Improved system security posture

## Conclusion
This task demonstrated practical firewall configuration and testing. UFW effectively controlled network traffic and enhanced system security.

## Disclaimer
This task was performed in a controlled lab environment for educational purposes only.
