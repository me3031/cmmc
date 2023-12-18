# AC.1.002
Limit information system access to the types of transactions and functions that authorized users are permitted to execute.

##  dms-replication-not-public
[dms-replication-not-public](https://docs.aws.amazon.com/config/latest/developerguide/dms-replication-not-public.html)

Guidance:
Manage access to the AWS Cloud by ensuring DMS replication instances cannot be publicly accessed. DMS replication instances can contain sensitive information and access control is required for such accounts.

##  ebs-snapshot-public-restorable-check
[ebs-snapshot-public-restorable-check](https://docs.aws.amazon.com/config/latest/developerguide/ebs-snapshot-public-restorable-check.html)

Guidance:
Manage access to the AWS Cloud by ensuring EBS snapshots are not publicly restorable. EBS volume snapshots can contain sensitive information and access control is required for such accounts.

##  ec2-imdsv2-check
[ec2-imdsv2-check](https://docs.aws.amazon.com/config/latest/developerguide/ec2-imdsv2-check.html)

Guidance:
Ensure the Instance Metadata Service Version 2 (IMDSv2) method is enabled to help protect access and control of Amazon Elastic Compute Cloud (Amazon EC2) instance metadata. The IMDSv2 method uses session-based controls. With IMDSv2, controls can be implemented to restrict changes to instance metadata.

##  ec2-instance-no-public-ip
[ec2-instance-no-public-ip](https://docs.aws.amazon.com/config/latest/developerguide/ec2-instance-no-public-ip.html)

Guidance:
Manage access to the AWS Cloud by ensuring Amazon Elastic Compute Cloud (Amazon EC2) instances cannot be publicly accessed. Amazon EC2 instances can contain sensitive information and access control is required for such accounts.

##  elasticsearch-in-vpc-only
[elasticsearch-in-vpc-only](https://docs.aws.amazon.com/config/latest/developerguide/elasticsearch-in-vpc-only.html)

Guidance:
Manage access to the AWS Cloud by ensuring Amazon OpenSearch Service (OpenSearch Service) Domains are within an Amazon Virtual Private Cloud (Amazon VPC). An OpenSearch Service domain within an Amazon VPC enables secure communication between OpenSearch Service and other services within the Amazon VPC without the need for an internet gateway, NAT device, or VPN connection.

##  emr-kerberos-enabled
[emr-kerberos-enabled](https://docs.aws.amazon.com/config/latest/developerguide/emr-kerberos-enabled.html)

Guidance:
The access permissions and authorizations can be managed and incorporated with the principles of least privilege and separation of duties, by enabling Kerberos for Amazon EMR clusters. In Kerberos, the services and the users that need to authenticate are known as principals. The principals exist within a Kerberos realm. Within the realm, a Kerberos server is known as the key distribution center (KDC). It provides a means for the principals to authenticate. The KDC authenticates by issuing tickets for authentication. The KDC maintains a database of the principals within its realm, their passwords, and other administrative information about each principal.

##  emr-master-no-public-ip
[emr-master-no-public-ip](https://docs.aws.amazon.com/config/latest/developerguide/emr-master-no-public-ip.html)

Guidance:
Manage access to the AWS Cloud by ensuring Amazon EMR cluster master nodes cannot be publicly accessed. Amazon EMR cluster master nodes can contain sensitive information and access control is required for such accounts.

##  iam-no-inline-policy-check
[iam-no-inline-policy-check](https://docs.aws.amazon.com/config/latest/developerguide/iam-no-inline-policy-check.html)

Guidance:
Ensure an AWS Identity and Access Management (IAM) user, IAM role or IAM group does not have an inline policy to control access to systems and assets. AWS recommends to use managed policies instead of inline policies. The managed policies allow reusability, versioning and rolling back, and delegating permissions management.

##  iam-password-policy
[iam-password-policy](https://docs.aws.amazon.com/config/latest/developerguide/iam-password-policy.html)

Guidance:
The identities and the credentials are issued, managed, and verified based on an organizational IAM password policy. They meet or exceed requirements as stated by NIST SP 800-63 and the AWS Foundational Security Best Practices standard for password strength. This rule allows you to optionally set RequireUppercaseCharacters (AWS Foundational Security Best Practices value: true), RequireLowercaseCharacters (AWS Foundational Security Best Practices value: true), RequireSymbols (AWS Foundational Security Best Practices value: true), RequireNumbers (AWS Foundational Security Best Practices value: true), MinimumPasswordLength (AWS Foundational Security Best Practices value: 14), PasswordReusePrevention (AWS Foundational Security Best Practices value: 24), and MaxPasswordAge (AWS Foundational Security Best Practices value: 90) for your IAM Password Policy. The actual values should reflect your organization's policies.

##  iam-policy-no-statements-with-admin-access
[iam-policy-no-statements-with-admin-access](https://docs.aws.amazon.com/config/latest/developerguide/iam-policy-no-statements-with-admin-access.html)

Guidance:
AWS Identity and Access Management (IAM) can help you incorporate the principles of least privilege and separation of duties with access permissions and authorizations, restricting policies from containing "Effect": "Allow" with "Action": "*" over "Resource": "*". Allowing users to have more privileges than needed to complete a task may violate the principle of least privilege and separation of duties.

##  iam-root-access-key-check
[iam-root-access-key-check](https://docs.aws.amazon.com/config/latest/developerguide/iam-root-access-key-check.html)

Guidance:
Access to systems and assets can be controlled by checking that the root user does not have access keys attached to their AWS Identity and Access Management (IAM) role. Ensure that the root access keys are deleted. Instead, create and use role-based AWS accounts to help to incorporate the principle of least functionality.

##  iam-user-group-membership-check
[iam-user-group-membership-check](https://docs.aws.amazon.com/config/latest/developerguide/iam-user-group-membership-check.html)

Guidance:
AWS Identity and Access Management (IAM) can help you restrict access permissions and authorizations, by ensuring users are members of at least one group. Allowing users more privileges than needed to complete a task may violate the principle of least privilege and separation of duties.

##  iam-user-mfa-enabled
[iam-user-mfa-enabled](https://docs.aws.amazon.com/config/latest/developerguide/iam-user-mfa-enabled.html)

Guidance:
Enable this rule to restrict access to resources in the AWS Cloud. This rule ensures multi-factor authentication (MFA) is enabled for all users. MFA adds an extra layer of protection on top of sign-in credentials. Reduce the incidents of compromised accounts by requiring MFA for users.

##  iam-user-no-policies-check
[iam-user-no-policies-check](https://docs.aws.amazon.com/config/latest/developerguide/iam-user-no-policies-check.html)

Guidance:
This rule ensures AWS Identity and Access Management (IAM) policies are attached only to groups or roles to control access to systems and assets. Assigning privileges at the group or the role level helps to reduce opportunity for an identity to receive or retain excessive privileges.

##  restricted-ssh
[restricted-ssh](https://docs.aws.amazon.com/config/latest/developerguide/restricted-ssh.html)

Guidance:
Amazon Elastic Compute Cloud (Amazon EC2) Security Groups can help manage network access by providing stateful filtering of ingress and egress network traffic to AWS resources. Not allowing ingress (or remote) traffic from 0.0.0.0/0 to port 22 on your resources help you restricting remote access.

##  ec2-instances-in-vpc
[ec2-instances-in-vpc](https://docs.aws.amazon.com/config/latest/developerguide/ec2-instances-in-vpc.html)

Guidance:
Deploy Amazon Elastic Compute Cloud (Amazon EC2) instances within an Amazon Virtual Private Cloud (Amazon VPC) to enable secure communication between an instance and other services within the amazon VPC, without requiring an internet gateway, NAT device, or VPN connection. All traffic remains securely within the AWS Cloud. Because of their logical isolation, domains that reside within an Amazon VPC have an extra layer of security when compared to domains that use public endpoints. Assign Amazon EC2 instances to an Amazon VPC to properly manage access.

##  internet-gateway-authorized-vpc-only
[internet-gateway-authorized-vpc-only](https://docs.aws.amazon.com/config/latest/developerguide/internet-gateway-authorized-vpc-only.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that internet gateways are only attached to authorized Amazon Virtual Private Cloud (Amazon VPC). Internet gateways allow bi-directional internet access to and from the Amazon VPC that can potentially lead to unauthorized access to Amazon VPC resources.

##  lambda-function-public-access-prohibited
[lambda-function-public-access-prohibited](https://docs.aws.amazon.com/config/latest/developerguide/lambda-function-public-access-prohibited.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring AWS Lambda functions cannot be publicly accessed. Public access can potentially lead to degradation of availability of resources.

##  lambda-inside-vpc
[lambda-inside-vpc](https://docs.aws.amazon.com/config/latest/developerguide/lambda-inside-vpc.html)

Guidance:
Deploy AWS Lambda functions within an Amazon Virtual Private Cloud (Amazon VPC) for a secure communication between a function and other services within the Amazon VPC. With this configuration, there is no requirement for an internet gateway, NAT device, or VPN connection. All the traffic remains securely within the AWS Cloud. Because of their logical isolation, domains that reside within an Amazon VPC have an extra layer of security when compared to domains that use public endpoints. To properly manage access, AWS Lambda functions should be assigned to a VPC.

##  mfa-enabled-for-iam-console-access
[mfa-enabled-for-iam-console-access](https://docs.aws.amazon.com/config/latest/developerguide/mfa-enabled-for-iam-console-access.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that MFA is enabled for all AWS Identity and Access Management (IAM) users that have a console password. MFA adds an extra layer of protection on top of sign-in credentials. By requiring MFA for users, you can reduce incidents of compromised accounts and keep sensitive data from being accessed by unauthorized users.

##  rds-instance-public-access-check
[rds-instance-public-access-check](https://docs.aws.amazon.com/config/latest/developerguide/rds-instance-public-access-check.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon Relational Database Service (Amazon RDS) instances are not public. Amazon RDS database instances can contain sensitive information, and principles and access control is required for such accounts.

##  rds-snapshots-public-prohibited
[rds-snapshots-public-prohibited](https://docs.aws.amazon.com/config/latest/developerguide/rds-snapshots-public-prohibited.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon Relational Database Service (Amazon RDS) instances are not public. Amazon RDS database instances can contain sensitive information and principles and access control is required for such accounts.

##  redshift-cluster-public-access-check
[redshift-cluster-public-access-check](https://docs.aws.amazon.com/config/latest/developerguide/redshift-cluster-public-access-check.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon Redshift clusters are not public. Amazon Redshift clusters can contain sensitive information and principles and access control is required for such accounts.

##  restricted-common-ports
[restricted-common-ports](https://docs.aws.amazon.com/config/latest/developerguide/restricted-common-ports.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring common ports are restricted on Amazon Elastic Compute Cloud (Amazon EC2) security groups. Not restricting access to ports to trusted sources can lead to attacks against the availability, integrity and confidentiality of systems. This rule allows you to optionally set blockedPort1 - blockedPort5 parameters (Config Defaults: 20,21,3389,3306,4333). The actual values should reflect your organization's policies.

##  root-account-hardware-mfa-enabled
[root-account-hardware-mfa-enabled](https://docs.aws.amazon.com/config/latest/developerguide/root-account-hardware-mfa-enabled.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring hardware MFA is enabled for the root user. The root user is the most privileged user in an AWS account. The MFA adds an extra layer of protection for sign-in credentials. By requiring MFA for the root user, you can reduce the incidents of compromised AWS accounts.

##  root-account-mfa-enabled
[root-account-mfa-enabled](https://docs.aws.amazon.com/config/latest/developerguide/root-account-mfa-enabled.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring MFA is enabled for the root user. The root user is the most privileged user in an AWS account. The MFA adds an extra layer of protection for sign-in credentials. By requiring MFA for the root user, you can reduce the incidents of compromised AWS accounts.

##  s3-account-level-public-access-blocks-periodic
[s3-account-level-public-access-blocks-periodic](https://docs.aws.amazon.com/config/latest/developerguide/s3-account-level-public-access-blocks-periodic.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon Simple Storage Service (Amazon S3) buckets cannot be publicly accessed. This rule helps keeping sensitive data safe from unauthorized remote users by preventing public access. This rule allows you to optionally set the ignorePublicAcls (Config Default: True), blockPublicPolicy (Config Default: True), blockPublicAcls (Config Default: True), and restrictPublicBuckets parameters (Config Default: True). The actual values should reflect your organization's policies.

##  s3-bucket-level-public-access-prohibited
[s3-bucket-level-public-access-prohibited](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-level-public-access-prohibited.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon Simple Storage Service (Amazon S3) buckets cannot be publicly accessed. This rule helps keeping sensitive data safe from unauthorized remote users by preventing public access at the bucket level.

##  s3-bucket-policy-grantee-check
[s3-bucket-policy-grantee-check](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-policy-grantee-check.html)

Guidance:
Manage access to the AWS Cloud by enabling s3_ bucket_policy_grantee_check. This rule checks that the access granted by the Amazon S3 bucket is restricted by any of the AWS principals, federated users, service principals, IP addresses, or Amazon Virtual Private Cloud (Amazon VPC) IDs that you provide.

##  s3-bucket-public-read-prohibited
[s3-bucket-public-read-prohibited](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-public-read-prohibited.html)

Guidance:
Manage access to resources in the AWS Cloud by only allowing authorized users, processes, and devices access to Amazon Simple Storage Service (Amazon S3) buckets. The management of access should be consistent with the classification of the data.

##  s3-bucket-public-write-prohibited
[s3-bucket-public-write-prohibited](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-public-write-prohibited.html)

Guidance:
Manage access to resources in the AWS Cloud by only allowing authorized users, processes, and devices access to Amazon Simple Storage Service (Amazon S3) buckets. The management of access should be consistent with the classification of the data.

##  sagemaker-notebook-no-direct-internet-access
[sagemaker-notebook-no-direct-internet-access](https://docs.aws.amazon.com/config/latest/developerguide/sagemaker-notebook-no-direct-internet-access.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon SageMaker notebooks do not allow direct internet access. By preventing direct internet access, you can keep sensitive data from being accessed by unauthorized users.

##  vpc-default-security-group-closed
[vpc-default-security-group-closed](https://docs.aws.amazon.com/config/latest/developerguide/vpc-default-security-group-closed.html)

Guidance:
Amazon Elastic Compute Cloud (Amazon EC2) security groups can help in the management of network access by providing stateful filtering of ingress and egress network traffic to AWS resources. Restricting all the traffic on the default security group helps in restricting remote access to your AWS resources.

##  vpc-sg-open-only-to-authorized-ports
[vpc-sg-open-only-to-authorized-ports](https://docs.aws.amazon.com/config/latest/developerguide/vpc-sg-open-only-to-authorized-ports.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring common ports are restricted on Amazon Elastic Compute Cloud (Amazon EC2) Security Groups. Not restricting access on ports to trusted sources can lead to attacks against the availability, integrity and confidentiality of systems. By restricting access to resources within a security group from the internet (0.0.0.0/0) remote access can be controlled to internal systems.

##  opensearch-in-vpc-only
[opensearch-in-vpc-only](https://docs.aws.amazon.com/config/latest/developerguide/opensearch-in-vpc-only.html)

Guidance:
Manage access to the AWS Cloud by ensuring Amazon OpenSearch Service domains are within an Amazon Virtual Private Cloud (Amazon VPC). An Amazon OpenSearch Service domain within an Amazon VPC enables secure communication between Amazon OpenSearch Service and other services within the Amazon VPC without the need for an internet gateway, NAT device, or VPN connection.
