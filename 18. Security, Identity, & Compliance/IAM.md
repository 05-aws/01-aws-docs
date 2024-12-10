## What is IAM

## Multi-Factor Authentication (MFA)

## How can users access AWS

- There are 3 options
  . AWS Management Console (protected by password + MFA)
  . AWS Command Line Interface (CLI) (projected by access key)
  . AWS Software Development Kit (SDK) (projected by access key)

## Best Practices

- Don't use root account except for AWS setup
- One physical user = one AWS user
- Create strong password policy
- Use and enforce the use of Multi-Factor Authentication (MFA)
- Create and use Roles for giving permission to AWS services
- Use Access Key for Programmatic Access (CLI/SDK)
- Audit permission of your account using IAM Credential Report and IAM Access Advisor
- Never share IAM users and Access Keys
