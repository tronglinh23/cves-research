# CVE Research

Hands-on writeups for vulnerabilities I analyzed and reproduced in controlled lab environments.

## Research

| CVE | Product | Topic |
| --- | --- | --- |
| [CVE-2025-52898](CVE-2025-52898/walkthrough.md) | Frappe | Password reset poisoning via Host header |
| [CVE-2025-30212](CVE-2025-30212/walkthrough.md) | Frappe | SQL injection in database query filters |
| [CVE-2025-30213](CVE-2025-30213/walkthrough.md) | Frappe | Path traversal to arbitrary file write and RCE |

Each writeup covers my analysis process, patch diff review, code tracing, and reproduction results. Screenshots from the lab are included, but exploit code is not.

## Disclaimer

This repository is for security research and educational purposes. All testing was performed in isolated environments that I owned or was authorized to use.
