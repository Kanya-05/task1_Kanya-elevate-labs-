# task1_Kanya-elevate-labs-
## Nmap Scan Summary

- **Scan Range**: 192.168.1.0/24
- **Command Used**: `nmap -sS 192.168.1.0/24 -oN scan_results.txt`
- **Scan Duration**: ~10 minutes
- **Devices Detected**: 252 active hosts

### Findings

- All scanned devices responded as **online** (host is up)
- However, all **1000 TCP ports were filtered** on every device
- No open ports were identified during this scan

###  Interpretation

- The network or hosts are **well-secured** against external scans
- Likely protected by:
  - Firewalls (software or router-level)
  - Security settings disabling responses to port probes

### Security Note

- While no services were exposed, this doesn't guarantee complete security
- **Filtered ports** mean responses are hidden — not necessarily closed or safe
- Further authenticated/internal scanning may reveal more

