# SC.3.180
Employ architectural designs, software development techniques, and systems engineering principles that promote effective information security within organizational systems.

##  account-part-of-organizations
[account-part-of-organizations](https://docs.aws.amazon.com/config/latest/developerguide/account-part-of-organizations.html)

Guidance:
Centralized management of AWS accounts within AWS Organizations helps to ensure that accounts are compliant. The lack of centralized account governance may lead to inconsistent account configurations, which may expose resources and sensitive data.

##  alb-waf-enabled
[alb-waf-enabled](https://docs.aws.amazon.com/config/latest/developerguide/alb-waf-enabled.html)

Guidance:
Ensure AWS WAF is enabled on Elastic Load Balancers (ELB) to help protect web applications. A WAF helps to protect your web applications or APIs against common web exploits. These web exploits may affect availability, compromise security, or consume excessive resources within your environment.

##  api-gw-associated-with-waf
[api-gw-associated-with-waf](https://docs.aws.amazon.com/config/latest/developerguide/api-gw-associated-with-waf.html)

Guidance:
AWS WAF enables you to configure a set of rules (called a web access control list (web ACL)) that allow, block, or count web requests based on customizable web security rules and conditions that you define. Ensure your Amazon API Gateway stage is associated with a WAF Web ACL to protect it from malicious attacks

##  autoscaling-launch-config-public-ip-disabled
[autoscaling-launch-config-public-ip-disabled](https://docs.aws.amazon.com/config/latest/developerguide/autoscaling-launch-config-public-ip-disabled.html)

Guidance:
If you configure your Network Interfaces with a public IP address, then the associated resources to those Network Interfaces are reachable from the internet. EC2 resources should not be publicly accessible, as this may allow unintended access to your applications or servers.

##  backup-plan-min-frequency-and-min-retention-check
[backup-plan-min-frequency-and-min-retention-check](https://docs.aws.amazon.com/config/latest/developerguide/backup-plan-min-frequency-and-min-retention-check.html)

Guidance:
To help with data back-up processes, ensure your AWS Backup plan is set for a minimum frequency and retention. AWS Backup is a fully managed backup service with a policy-based backup solution. This solution simplifies your backup management and enables you to meet your business and regulatory backup compliance requirements. This rule allows you to set the requiredFrequencyValue (Config default: 1),  requiredRetentionDays (Config default: 35) and requiredFrequencyUnit (Config default: days) parameters. The actual value should reflect your organizations requirements.

##  cloudtrail-security-trail-enabled
[cloudtrail-security-trail-enabled](https://docs.aws.amazon.com/config/latest/developerguide/cloudtrail-security-trail-enabled.html)

Guidance:
This rule helps ensure the use of AWS recommended security best practices for AWS CloudTrail, by checking for the enablement of multiple settings. These include the use of log encryption, log validation, and enabling AWS CloudTrail in multiple regions.

##  codebuild-project-envvar-awscred-check
[codebuild-project-envvar-awscred-check](https://docs.aws.amazon.com/config/latest/developerguide/codebuild-project-envvar-awscred-check.html)

Guidance:
Ensure authentication credentials AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY do not exist within AWS Codebuild project environments. Do not store these variables in clear text. Storing these variables in clear text leads to unintended data exposure and unauthorized access.

##  codebuild-project-source-repo-url-check
[codebuild-project-source-repo-url-check](https://docs.aws.amazon.com/config/latest/developerguide/codebuild-project-source-repo-url-check.html)

Guidance:
Ensure the GitHub or Bitbucket source repository URL does not contain personal access tokens, sign-in credentials within AWS Codebuild project environments. Use OAuth instead of personal access tokens or sign-in credentials to grant authorization for accessing GitHub or Bitbucket repositories.

##  db-instance-backup-enabled
[db-instance-backup-enabled](https://docs.aws.amazon.com/config/latest/developerguide/db-instance-backup-enabled.html)

Guidance:
The backup feature of Amazon RDS creates backups of your databases and transaction logs. Amazon RDS automatically creates a storage volume snapshot of your DB instance, backing up the entire DB instance. The system allows you to set specific retention periods to meet your resilience requirements.

##  dms-replication-not-public
[dms-replication-not-public](https://docs.aws.amazon.com/config/latest/developerguide/dms-replication-not-public.html)

Guidance:
Manage access to the AWS Cloud by ensuring DMS replication instances cannot be publicly accessed. DMS replication instances can contain sensitive information and access control is required for such accounts.

##  dynamodb-autoscaling-enabled
[dynamodb-autoscaling-enabled](https://docs.aws.amazon.com/config/latest/developerguide/dynamodb-autoscaling-enabled.html)

Guidance:
Amazon DynamoDB auto scaling uses the AWS Application Auto Scaling service to adjust provisioned throughput capacity that automatically responds to actual traffic patterns. This enables a table or a global secondary index to increase its provisioned read/write capacity to handle sudden increases in traffic, without throttling.

##  dynamodb-in-backup-plan
[dynamodb-in-backup-plan](https://docs.aws.amazon.com/config/latest/developerguide/dynamodb-in-backup-plan.html)

Guidance:
To help with data back-up processes, ensure your Amazon DynamoDB tables are a part of an AWS Backup plan. AWS Backup is a fully managed backup service with a policy-based backup solution. This solution simplifies your backup management and enables you to meet your business and regulatory backup compliance requirements.

##  dynamodb-pitr-enabled
[dynamodb-pitr-enabled](https://docs.aws.amazon.com/config/latest/developerguide/dynamodb-pitr-enabled.html)

Guidance:
Enable this rule to check that information has been backed up. It also maintains the backups by ensuring that point-in-time recovery is enabled in Amazon DynamoDB. The recovery maintains continuous backups of your table for the last 35 days.

##  ebs-in-backup-plan
[ebs-in-backup-plan](https://docs.aws.amazon.com/config/latest/developerguide/ebs-in-backup-plan.html)

Guidance:
To help with data back-up processes, ensure your Amazon Elastic Block Store (Amazon EBS) volumes are a part of an AWS Backup plan. AWS Backup is a fully managed backup service with a policy-based backup solution. This solution simplifies your backup management and enables you to meet your business and regulatory backup compliance requirements.

##  ebs-optimized-instance
[ebs-optimized-instance](https://docs.aws.amazon.com/config/latest/developerguide/ebs-optimized-instance.html)

Guidance:
An optimized instance in Amazon Elastic Block Store (Amazon EBS) provides additional, dedicated capacity for Amazon EBS I/O operations. This optimization provides the most efficient performance for your EBS volumes by minimizing contention between Amazon EBS I/O operations and other traffic from your instance.

##  ebs-snapshot-public-restorable-check
[ebs-snapshot-public-restorable-check](https://docs.aws.amazon.com/config/latest/developerguide/ebs-snapshot-public-restorable-check.html)

Guidance:
Manage access to the AWS Cloud by ensuring EBS snapshots are not publicly restorable. EBS volume snapshots can contain sensitive information and access control is required for such accounts.

##  ec2-instance-no-public-ip
[ec2-instance-no-public-ip](https://docs.aws.amazon.com/config/latest/developerguide/ec2-instance-no-public-ip.html)

Guidance:
Manage access to the AWS Cloud by ensuring Amazon Elastic Compute Cloud (Amazon EC2) instances cannot be publicly accessed. Amazon EC2 instances can contain sensitive information and access control is required for such accounts.

##  efs-in-backup-plan
[efs-in-backup-plan](https://docs.aws.amazon.com/config/latest/developerguide/efs-in-backup-plan.html)

Guidance:
To help with data back-up processes, ensure your Amazon Elastic File System (Amazon EFS) file systems are a part of an AWS Backup plan. AWS Backup is a fully managed backup service with a policy-based backup solution. This solution simplifies your backup management and enables you to meet your business and regulatory backup compliance requirements.

##  elasticache-redis-cluster-automatic-backup-check
[elasticache-redis-cluster-automatic-backup-check](https://docs.aws.amazon.com/config/latest/developerguide/elasticache-redis-cluster-automatic-backup-check.html)

Guidance:
When automatic backups are enabled, Amazon ElastiCache creates a backup of the cluster on a daily basis. The backup can be retained for a number of days as specified by your organization. Automatic backups can help guard against data loss. If a failure occurs, you can create a new cluster, which restores your data from the most recent backup.

##  elasticsearch-in-vpc-only
[elasticsearch-in-vpc-only](https://docs.aws.amazon.com/config/latest/developerguide/elasticsearch-in-vpc-only.html)

Guidance:
Manage access to the AWS Cloud by ensuring Amazon OpenSearch Service (OpenSearch Service) Domains are within an Amazon Virtual Private Cloud (Amazon VPC). An OpenSearch Service domain within an Amazon VPC enables secure communication between OpenSearch Service and other services within the Amazon VPC without the need for an internet gateway, NAT device, or VPN connection.

##  elb-cross-zone-load-balancing-enabled
[elb-cross-zone-load-balancing-enabled](https://docs.aws.amazon.com/config/latest/developerguide/elb-cross-zone-load-balancing-enabled.html)

Guidance:
Enable cross-zone load balancing for your Elastic Load Balancers (ELBs) to help maintain adequate capacity and availability. The cross-zone load balancing reduces the need to maintain equivalent numbers of instances in each enabled availability zone. It also improves your application's ability to handle the loss of one or more instances.

##  elb-deletion-protection-enabled
[elb-deletion-protection-enabled](https://docs.aws.amazon.com/config/latest/developerguide/elb-deletion-protection-enabled.html)

Guidance:
This rule ensures that Elastic Load Balancing has deletion protection enabled. Use this feature to prevent your load balancer from being accidentally or maliciously deleted, which can lead to loss of availability for your applications.

##  emr-master-no-public-ip
[emr-master-no-public-ip](https://docs.aws.amazon.com/config/latest/developerguide/emr-master-no-public-ip.html)

Guidance:
Manage access to the AWS Cloud by ensuring Amazon EMR cluster master nodes cannot be publicly accessed. Amazon EMR cluster master nodes can contain sensitive information and access control is required for such accounts.

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

##  no-unrestricted-route-to-igw
[no-unrestricted-route-to-igw](https://docs.aws.amazon.com/config/latest/developerguide/no-unrestricted-route-to-igw.html)

Guidance:
Ensure Amazon EC2 route tables do not have unrestricted routes to an internet gateway. Removing or limiting the access to the internet for workloads within Amazon VPCs can reduce unintended access within your environment.

##  rds-instance-deletion-protection-enabled
[rds-instance-deletion-protection-enabled](https://docs.aws.amazon.com/config/latest/developerguide/rds-instance-deletion-protection-enabled.html)

Guidance:
Ensure Amazon Relational Database Service (Amazon RDS) instances have deletion protection enabled. Use deletion protection to prevent your Amazon RDS instances from being accidentally or maliciously deleted, which can lead to loss of availability for your applications.

##  rds-instance-public-access-check
[rds-instance-public-access-check](https://docs.aws.amazon.com/config/latest/developerguide/rds-instance-public-access-check.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon Relational Database Service (Amazon RDS) instances are not public. Amazon RDS database instances can contain sensitive information, and principles and access control is required for such accounts.

##  rds-in-backup-plan
[rds-in-backup-plan](https://docs.aws.amazon.com/config/latest/developerguide/rds-in-backup-plan.html)

Guidance:
To help with data back-up processes, ensure your Amazon Relational Database Service (Amazon RDS) instances are a part of an AWS Backup plan. AWS Backup is a fully managed backup service with a policy-based backup solution. This solution simplifies your backup management and enables you to meet your business and regulatory backup compliance requirements.

##  rds-multi-az-support
[rds-multi-az-support](https://docs.aws.amazon.com/config/latest/developerguide/rds-multi-az-support.html)

Guidance:
Multi-AZ support in Amazon Relational Database Service (Amazon RDS) provides enhanced availability and durability for database instances. When you provision a Multi-AZ database instance, Amazon RDS automatically creates a primary database instance, and synchronously replicates the data to a standby instance in a different Availability Zone. Each Availability Zone runs on its own physically distinct, independent infrastructure, and is engineered to be highly reliable. In case of an infrastructure failure, Amazon RDS performs an automatic failover to the standby so that you can resume database operations as soon as the failover is complete.

##  rds-snapshots-public-prohibited
[rds-snapshots-public-prohibited](https://docs.aws.amazon.com/config/latest/developerguide/rds-snapshots-public-prohibited.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon Relational Database Service (Amazon RDS) instances are not public. Amazon RDS database instances can contain sensitive information and principles and access control is required for such accounts.

##  redshift-backup-enabled
[redshift-backup-enabled](https://docs.aws.amazon.com/config/latest/developerguide/redshift-backup-enabled.html)

Guidance:
To help with data back-up processes, ensure your Amazon Redshift clusters have automated snapshots. When automated snapshots are enabled for a cluster, Redshift periodically takes snapshots of that cluster. By default, Redshift takes a snapshot every eight hours or every 5 GB per node of data changes, or whichever comes first.

##  redshift-cluster-public-access-check
[redshift-cluster-public-access-check](https://docs.aws.amazon.com/config/latest/developerguide/redshift-cluster-public-access-check.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon Redshift clusters are not public. Amazon Redshift clusters can contain sensitive information and principles and access control is required for such accounts.

##  restricted-common-ports
[restricted-common-ports](https://docs.aws.amazon.com/config/latest/developerguide/restricted-common-ports.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring common ports are restricted on Amazon Elastic Compute Cloud (Amazon EC2) security groups. Not restricting access to ports to trusted sources can lead to attacks against the availability, integrity and confidentiality of systems. This rule allows you to optionally set blockedPort1 - blockedPort5 parameters (Config Defaults: 20,21,3389,3306,4333). The actual values should reflect your organization's policies.

##  s3-account-level-public-access-blocks-periodic
[s3-account-level-public-access-blocks-periodic](https://docs.aws.amazon.com/config/latest/developerguide/s3-account-level-public-access-blocks-periodic.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon Simple Storage Service (Amazon S3) buckets cannot be publicly accessed. This rule helps keeping sensitive data safe from unauthorized remote users by preventing public access. This rule allows you to optionally set the ignorePublicAcls (Config Default: True), blockPublicPolicy (Config Default: True), blockPublicAcls (Config Default: True), and restrictPublicBuckets parameters (Config Default: True). The actual values should reflect your organization's policies.

##  s3-bucket-default-lock-enabled
[s3-bucket-default-lock-enabled](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-default-lock-enabled.html)

Guidance:
Ensure that your Amazon Simple Storage Service (Amazon S3) bucket has lock enabled, by default. Because sensitive data can exist at rest in S3 buckets, enforce object locks at rest to help protect that data.

##  s3-bucket-level-public-access-prohibited
[s3-bucket-level-public-access-prohibited](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-level-public-access-prohibited.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon Simple Storage Service (Amazon S3) buckets cannot be publicly accessed. This rule helps keeping sensitive data safe from unauthorized remote users by preventing public access at the bucket level.

##  s3-bucket-public-read-prohibited
[s3-bucket-public-read-prohibited](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-public-read-prohibited.html)

Guidance:
Manage access to resources in the AWS Cloud by only allowing authorized users, processes, and devices access to Amazon Simple Storage Service (Amazon S3) buckets. The management of access should be consistent with the classification of the data.

##  s3-bucket-public-write-prohibited
[s3-bucket-public-write-prohibited](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-public-write-prohibited.html)

Guidance:
Manage access to resources in the AWS Cloud by only allowing authorized users, processes, and devices access to Amazon Simple Storage Service (Amazon S3) buckets. The management of access should be consistent with the classification of the data.

##  s3-bucket-replication-enabled
[s3-bucket-replication-enabled](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-replication-enabled.html)

Guidance:
Amazon Simple Storage Service (Amazon S3) Cross-Region Replication (CRR) supports maintaining adequate capacity and availability. CRR enables automatic, asynchronous copying of objects across Amazon S3 buckets to help ensure that data availability is maintained.

##  s3-bucket-versioning-enabled
[s3-bucket-versioning-enabled](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-versioning-enabled.html)

Guidance:
Amazon Simple Storage Service (Amazon S3) bucket versioning helps keep multiple variants of an object in the same Amazon S3 bucket. Use versioning to preserve, retrieve, and restore every version of every object stored in your Amazon S3 bucket. Versioning helps you to easily recover from unintended user actions and application failures.

##  sagemaker-notebook-no-direct-internet-access
[sagemaker-notebook-no-direct-internet-access](https://docs.aws.amazon.com/config/latest/developerguide/sagemaker-notebook-no-direct-internet-access.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon SageMaker notebooks do not allow direct internet access. By preventing direct internet access, you can keep sensitive data from being accessed by unauthorized users.

##  ssm-document-not-public
[ssm-document-not-public](https://docs.aws.amazon.com/config/latest/developerguide/ssm-document-not-public.html)

Guidance:
Ensure AWS Systems Manager (SSM) documents are not public, as this may allow unintended access to your SSM documents. A public SSM document can expose information about your account, resources and internal processes.

##  subnet-auto-assign-public-ip-disabled
[subnet-auto-assign-public-ip-disabled](https://docs.aws.amazon.com/config/latest/developerguide/subnet-auto-assign-public-ip-disabled.html)

Guidance:
Manage access to the AWS Cloud by ensuring Amazon Virtual Private Cloud (VPC) subnets are not automatically assigned a public IP address. Amazon Elastic Compute Cloud (EC2) instances that are launched into subnets that have this attribute enabled have a public IP address assigned to their primary network interface.

##  vpc-default-security-group-closed
[vpc-default-security-group-closed](https://docs.aws.amazon.com/config/latest/developerguide/vpc-default-security-group-closed.html)

Guidance:
Amazon Elastic Compute Cloud (Amazon EC2) security groups can help in the management of network access by providing stateful filtering of ingress and egress network traffic to AWS resources. Restricting all the traffic on the default security group helps in restricting remote access to your AWS resources.

##  vpc-sg-open-only-to-authorized-ports
[vpc-sg-open-only-to-authorized-ports](https://docs.aws.amazon.com/config/latest/developerguide/vpc-sg-open-only-to-authorized-ports.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring common ports are restricted on Amazon Elastic Compute Cloud (Amazon EC2) Security Groups. Not restricting access on ports to trusted sources can lead to attacks against the availability, integrity and confidentiality of systems. By restricting access to resources within a security group from the internet (0.0.0.0/0) remote access can be controlled to internal systems.

##  vpc-vpn-2-tunnels-up
[vpc-vpn-2-tunnels-up](https://docs.aws.amazon.com/config/latest/developerguide/vpc-vpn-2-tunnels-up.html)

Guidance:
Redundant Site-to-Site VPN tunnels can be implemented to achieve resilience requirements. It uses two tunnels to help ensure connectivity in case one of the Site-to-Site VPN connections becomes unavailable. To protect against a loss of connectivity, in case your customer gateway becomes unavailable, you can set up a second Site-to-Site VPN connection to your Amazon Virtual Private Cloud (Amazon VPC) and virtual private gateway by using a second customer gateway.

##  opensearch-in-vpc-only
[opensearch-in-vpc-only](https://docs.aws.amazon.com/config/latest/developerguide/opensearch-in-vpc-only.html)

Guidance:
Manage access to the AWS Cloud by ensuring Amazon OpenSearch Service domains are within an Amazon Virtual Private Cloud (Amazon VPC). An Amazon OpenSearch Service domain within an Amazon VPC enables secure communication between Amazon OpenSearch Service and other services within the Amazon VPC without the need for an internet gateway, NAT device, or VPN connection.
