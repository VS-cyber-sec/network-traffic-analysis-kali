## Before Setup
- SSH service was running without restrictions.
- No firewall rules were applied.
- All incoming connections were allowed.

## After Setup
- UFW enabled with SSH allowed only.
- fail2ban configured to block brute-force login attempts after 5 failures.
- SSH login attempts monitored and suspicious activity logged.
- Packet captures available for forensic analysis.

## Observations
- Several failed login attempts were blocked.
- The firewall prevented unwanted access.
- Traffic analysis confirmed attack patterns like SYN floods and repeated login attempts.
