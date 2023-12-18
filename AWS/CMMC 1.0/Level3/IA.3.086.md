# IA.3.086
Disable identifiers after a defined period of inactivity.

##  iam-password-policy
[iam-password-policy](https://docs.aws.amazon.com/config/latest/developerguide/iam-password-policy.html)

Guidance:
The identities and the credentials are issued, managed, and verified based on an organizational IAM password policy. They meet or exceed requirements as stated by NIST SP 800-63 and the AWS Foundational Security Best Practices standard for password strength. This rule allows you to optionally set RequireUppercaseCharacters (AWS Foundational Security Best Practices value: true), RequireLowercaseCharacters (AWS Foundational Security Best Practices value: true), RequireSymbols (AWS Foundational Security Best Practices value: true), RequireNumbers (AWS Foundational Security Best Practices value: true), MinimumPasswordLength (AWS Foundational Security Best Practices value: 14), PasswordReusePrevention (AWS Foundational Security Best Practices value: 24), and MaxPasswordAge (AWS Foundational Security Best Practices value: 90) for your IAM Password Policy. The actual values should reflect your organization's policies.

##  iam-user-unused-credentials-check
[iam-user-unused-credentials-check](https://docs.aws.amazon.com/config/latest/developerguide/iam-user-unused-credentials-check.html)

Guidance:
AWS Identity and Access Management (IAM) can help you with access permissions and authorizations by checking for IAM passwords and access keys that are not used for a specified time period. If these unused credentials are identified, you should disable and/or remove the credentials, as this may violate the principle of least privilege. This rule requires you to set a value to the maxCredentialUsageAge (Config Default: 90). The actual value should reflect your organization's policies.
