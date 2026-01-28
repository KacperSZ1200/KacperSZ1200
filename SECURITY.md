# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |

## Reporting a Vulnerability

We take security seriously. If you discover a vulnerability in this project, please follow these steps:

1.  **Do not open a public issue.** Publicly disclosing a vulnerability can put users at risk.
2.  **Report privately.** Please contact the repository owner directly or use GitHub's private vulnerability reporting feature if available.
3.  **Provide details.** Include as much information as possible to help us reproduce and resolve the issue.

## Best Practices for Users

- **Review Source Code:** Always inspect the code of userscripts (`.user.js`) and userstyles (`.user.css`) before installing them.
- **Check Permissions:** Be cautious of scripts requesting excessive permissions (e.g., `@connect`, `@grant`).
- **Limit Scope:** When creating your own scripts based on these examples, restrict `@match` rules to specific domains whenever possible.
