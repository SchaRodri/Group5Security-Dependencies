# Document Security Best Practices for GitHub Repositories

## Purpose
This document summarizes recommended security best practices for GitHub repositories.

## 1. Dependency Update Frequency
Dependencies should be reviewed and updated regularly to reduce security risks caused by outdated packages.

### Best Practices
- Enable Dependabot alerts to detect known vulnerabilities.
- Review dependencies at least once per sprint or once per month.
- Apply security-related updates as soon as possible.
- Test major version updates before merging them.
- Remove unused dependencies to reduce the attack surface.

## 2. Branch Protection Strategy
Branch protection helps prevent insecure or unreviewed code from being merged into important branches.

### Best Practices
- Protect the `main` branch.
- Do not allow direct pushes to `main`.
- Require pull requests before merging changes.
- Require at least one approval before merging.
- Require status checks to pass before merging.
- Keep branches up to date before merging when possible.

## 3. Review Practices
Code reviews improve code quality and help identify security issues early.

### Best Practices
- Every pull request should be reviewed by at least one team member.
- Reviewers should check for hardcoded secrets, insecure code, and unnecessary dependencies.
- Pull requests should be small and focused.
- Use clear pull request descriptions.
- Resolve all review comments before merging.

## Summary
Following these practices improves repository security, reduces the risk of vulnerabilities, and supports a safer workflow.

## Reusable Cheat Sheet Points
- Update dependencies regularly
- Enable Dependabot alerts
- Protect the main branch
- Require pull requests and approvals
- Review code for secrets and security risks
