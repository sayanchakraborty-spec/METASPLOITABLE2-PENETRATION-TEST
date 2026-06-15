# Metasploitable 2 — Penetration Test

A full penetration test conducted against Metasploitable 2 in an isolated lab environment for educational purposes.

## Summary

This assessment identified 6 vulnerabilities across network services, web applications, and authentication systems — including two paths to unauthenticated remote root access.

## Tools Used

Nmap, Metasploit Framework, SQLMap, Hydra, John the Ripper, DVWA

## Findings

| # | Finding | Severity |
|---|---|---|
| 1 | VSFTPd 2.3.4 Backdoor (CVE-2011-2523) | Critical |
| 2 | Samba usermap_script RCE (CVE-2007-2447) | Critical |
| 3 | SQL Injection (DVWA) | High |
| 4 | SSH Weak Default Credentials | High |
| 5 | Weak Password Hashes | Medium |
| 6 | OS Command Injection & File Upload | Critical |

## Full Report

See `PROJECT.pdf` for the complete report including methodology, detailed steps, impact analysis, and remediation recommendations for each finding.

## Disclaimer

All testing was performed in an isolated virtual lab environment. No production systems were involved.
