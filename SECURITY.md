# Security Policy

## Scope

This document describes the security characteristics of psscope.

## Security Characteristics

### Network Behavior

- psscope does NOT establish any network connections
- psscope does NOT send data to external servers
- psscope does NOT receive remote commands

### Telemetry

- psscope does NOT collect telemetry
- psscope does NOT track usage statistics
- psscope does NOT phone home

### Auto-Update

- psscope does NOT auto-update
- Updates must be downloaded manually from GitHub Releases

### Data Access

- psscope reads process information from /proc filesystem
- psscope does NOT modify system files
- psscope does NOT write to system directories

### Privileges

- psscope runs with current user privileges
- Some features may require elevated permissions for full visibility
- psscope does NOT require root for basic operation

## Vulnerability Reporting

If you discover a security vulnerability, please report it via:

1. GitHub Security Advisories (preferred)
2. Direct email to the maintainer

Please include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact assessment

Do NOT disclose vulnerabilities publicly until a fix is available.

## Response Timeline

- Acknowledgment: within 48 hours
- Initial assessment: within 7 days
- Fix or mitigation: based on severity

## Supported Versions

| Version | Supported |
|---------|-----------|
| 0.1.x   | Yes       |

## Security Updates

Security updates are distributed via GitHub Releases.
Check release notes for security-related changes.
