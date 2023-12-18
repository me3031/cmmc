# IA.3.083
Use multifactor authentication for local and network access to privileged accounts and for network access to non-privileged accounts.

##  iam-user-mfa-enabled
[iam-user-mfa-enabled](https://docs.aws.amazon.com/config/latest/developerguide/iam-user-mfa-enabled.html)

Guidance:
Enable this rule to restrict access to resources in the AWS Cloud. This rule ensures multi-factor authentication (MFA) is enabled for all users. MFA adds an extra layer of protection on top of sign-in credentials. Reduce the incidents of compromised accounts by requiring MFA for users.

##  mfa-enabled-for-iam-console-access
[mfa-enabled-for-iam-console-access](https://docs.aws.amazon.com/config/latest/developerguide/mfa-enabled-for-iam-console-access.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that MFA is enabled for all AWS Identity and Access Management (IAM) users that have a console password. MFA adds an extra layer of protection on top of sign-in credentials. By requiring MFA for users, you can reduce incidents of compromised accounts and keep sensitive data from being accessed by unauthorized users.

##  root-account-hardware-mfa-enabled
[root-account-hardware-mfa-enabled](https://docs.aws.amazon.com/config/latest/developerguide/root-account-hardware-mfa-enabled.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring hardware MFA is enabled for the root user. The root user is the most privileged user in an AWS account. The MFA adds an extra layer of protection for sign-in credentials. By requiring MFA for the root user, you can reduce the incidents of compromised AWS accounts.

##  root-account-mfa-enabled
[root-account-mfa-enabled](https://docs.aws.amazon.com/config/latest/developerguide/root-account-mfa-enabled.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring MFA is enabled for the root user. The root user is the most privileged user in an AWS account. The MFA adds an extra layer of protection for sign-in credentials. By requiring MFA for the root user, you can reduce the incidents of compromised AWS accounts.
