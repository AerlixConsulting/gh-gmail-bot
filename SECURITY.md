# Security Policy

We take security seriously. If you discover a vulnerability in this repository, please follow the guidelines below.

## Reporting a Vulnerability

If you have found a vulnerability, please report it via email at security@aerlixconsulting.com or by creating a private security advisory (if enabled). Provide a detailed description and reproduction steps. We will acknowledge your report promptly and work with you to resolve the issue.

## Responsible Disclosure

Please do not publicly disclose vulnerabilities until we've had an opportunity to investigate and address them. Our typical response is within 1 business day. We appreciate your cooperation in following responsible disclosure practices.

## Supported Versions

This project follows semantic versioning. We maintain the latest stable release. If you find a security issue on older versions, please update to the latest release and verify if the issue persists.

## Security Practices

- Secrets and API keys are never committed to the repository. Configuration is managed via environment variables (`.env.example` is provided).
- Dependencies are monitored using GitHub's security alerts.
- Our CI pipeline runs static analysis and vulnerability scanning.
- Access controls adhere to least-privilege principles.

For any other questions or concerns, contact us at contact@aerlixconsulting.com.
