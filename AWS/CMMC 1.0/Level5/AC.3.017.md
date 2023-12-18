# AC.3.017
Separate the duties of individuals to reduce the risk of malevolent activity without collusion.

##  emr-kerberos-enabled
[emr-kerberos-enabled](https://docs.aws.amazon.com/config/latest/developerguide/emr-kerberos-enabled.html)

Guidance:
The access permissions and authorizations can be managed and incorporated with the principles of least privilege and separation of duties, by enabling Kerberos for Amazon EMR clusters. In Kerberos, the services and the users that need to authenticate are known as principals. The principals exist within a Kerberos realm. Within the realm, a Kerberos server is known as the key distribution center (KDC). It provides a means for the principals to authenticate. The KDC authenticates by issuing tickets for authentication. The KDC maintains a database of the principals within its realm, their passwords, and other administrative information about each principal.

##  iam-customer-policy-blocked-kms-actions
[iam-customer-policy-blocked-kms-actions](https://docs.aws.amazon.com/config/latest/developerguide/iam-customer-policy-blocked-kms-actions.html)

Guidance:
AWS Identity and Access Management (IAM) can help you incorporate the principles of least privilege and separation of duties with access permissions and authorizations, restricting policies from containing blocked actions on all AWS Key Management Service keys. Having more privileges than needed to complete a task may violate the principle of least privilege and separation of duties. This rule allows you to set the blockedActionsPatterns parameter. (AWS Foundational Security Best Practices value: kms:Decrypt, kms:ReEncryptFrom). The actual values should reflect your organization's policies

##  iam-group-has-users-check
[iam-group-has-users-check](https://docs.aws.amazon.com/config/latest/developerguide/iam-group-has-users-check.html)

Guidance:
AWS Identity and Access Management (IAM) can help you incorporate the principles of least privilege and separation of duties with access permissions and authorizations, by ensuring that IAM groups have at least one user. Placing users in groups based on their associated permissions or job function is one way to incorporate least privilege.

##  iam-no-inline-policy-check
[iam-no-inline-policy-check](https://docs.aws.amazon.com/config/latest/developerguide/iam-no-inline-policy-check.html)

Guidance:
Ensure an AWS Identity and Access Management (IAM) user, IAM role or IAM group does not have an inline policy to control access to systems and assets. AWS recommends to use managed policies instead of inline policies. The managed policies allow reusability, versioning and rolling back, and delegating permissions management.

##  iam-policy-no-statements-with-admin-access
[iam-policy-no-statements-with-admin-access](https://docs.aws.amazon.com/config/latest/developerguide/iam-policy-no-statements-with-admin-access.html)

Guidance:
AWS Identity and Access Management (IAM) can help you incorporate the principles of least privilege and separation of duties with access permissions and authorizations, restricting policies from containing "Effect": "Allow" with "Action": "*" over "Resource": "*". Allowing users to have more privileges than needed to complete a task may violate the principle of least privilege and separation of duties.

##  iam-policy-no-statements-with-full-access
[iam-policy-no-statements-with-full-access](https://docs.aws.amazon.com/config/latest/developerguide/iam-policy-no-statements-with-full-access.html)

Guidance:
Ensure IAM Actions are restricted to only those actions that are needed. Allowing users to have more privileges than needed to complete a task may violate the principle of least privilege and separation of duties.

##  iam-root-access-key-check
[iam-root-access-key-check](https://docs.aws.amazon.com/config/latest/developerguide/iam-root-access-key-check.html)

Guidance:
Access to systems and assets can be controlled by checking that the root user does not have access keys attached to their AWS Identity and Access Management (IAM) role. Ensure that the root access keys are deleted. Instead, create and use role-based AWS accounts to help to incorporate the principle of least functionality.

##  iam-user-group-membership-check
[iam-user-group-membership-check](https://docs.aws.amazon.com/config/latest/developerguide/iam-user-group-membership-check.html)

Guidance:
AWS Identity and Access Management (IAM) can help you restrict access permissions and authorizations, by ensuring users are members of at least one group. Allowing users more privileges than needed to complete a task may violate the principle of least privilege and separation of duties.

##  iam-user-no-policies-check
[iam-user-no-policies-check](https://docs.aws.amazon.com/config/latest/developerguide/iam-user-no-policies-check.html)

Guidance:
This rule ensures AWS Identity and Access Management (IAM) policies are attached only to groups or roles to control access to systems and assets. Assigning privileges at the group or the role level helps to reduce opportunity for an identity to receive or retain excessive privileges.

##  s3-bucket-policy-grantee-check
[s3-bucket-policy-grantee-check](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-policy-grantee-check.html)

Guidance:
Manage access to the AWS Cloud by enabling s3_ bucket_policy_grantee_check. This rule checks that the access granted by the Amazon S3 bucket is restricted by any of the AWS principals, federated users, service principals, IP addresses, or Amazon Virtual Private Cloud (Amazon VPC) IDs that you provide.
