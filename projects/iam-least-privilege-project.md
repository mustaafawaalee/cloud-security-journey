# IAM and Least Privilege Project

## Project Overview
This project focuses on Identity and Access Management (IAM) and the principle of least privilege in cloud security.

The goal is to understand how access should be controlled so that users only have the permissions they need to do their jobs and nothing more.

## Why This Project Matters
IAM is one of the most important parts of cloud security. If permissions are too broad, users can access or change things they should not. Least privilege reduces security risk by limiting access.

## Key Concepts

### Identity and Access Management (IAM)
IAM is used to control who can access cloud resources and what actions they are allowed to perform.

### Least Privilege
Least privilege means giving users the minimum level of access required to perform their responsibilities.

### Multi-Factor Authentication (MFA)
MFA adds an extra layer of security by requiring more than a password to log in.

### Role-Based Access
Access can be assigned based on a person’s role, such as admin, analyst, or viewer.

## Example Scenario
A company has three employees who use cloud resources:

- **Admin**: Full access to manage systems and settings
- **Security Analyst**: Access to logs, alerts, and monitoring tools
- **Viewer**: Read-only access to reports and dashboards

In a secure cloud environment, each person should only receive the access needed for their role.

## Access Design Example

| Role | Access Level | Reason |
|------|--------------|--------|
| Admin | Full administrative access | Needed to manage systems and users |
| Security Analyst | Read logs, monitor alerts, investigate activity | Needed for security operations |
| Viewer | Read-only access | Needed to review information without making changes |

## Risks of Too Much Access
If every user has admin access, the organization faces higher risk, including:

- Accidental changes to systems
- Data exposure
- Misuse of privileges
- Larger impact if an account is compromised

## Security Best Practices
- Use least privilege
- Enable MFA
- Review permissions regularly
- Avoid sharing accounts
- Monitor account activity
- Remove unused access

## What I Learned
This project helped me understand that IAM is a core part of cloud security. Least privilege is important because it reduces the attack surface and helps protect systems and data.

## Next Steps
- Learn IAM in AWS or Azure
- Practice creating users, groups, and roles in a cloud lab
- Continue documenting cloud security concepts in GitHub
