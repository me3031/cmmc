# RE.5.140
Ensure information processing facilities meet organizationally defined information security continuity, redundancy, and availability requirements.

##  backup-plan-min-frequency-and-min-retention-check
[backup-plan-min-frequency-and-min-retention-check](https://docs.aws.amazon.com/config/latest/developerguide/backup-plan-min-frequency-and-min-retention-check.html)

Guidance:
To help with data back-up processes, ensure your AWS Backup plan is set for a minimum frequency and retention. AWS Backup is a fully managed backup service with a policy-based backup solution. This solution simplifies your backup management and enables you to meet your business and regulatory backup compliance requirements. This rule allows you to set the requiredFrequencyValue (Config default: 1),  requiredRetentionDays (Config default: 35) and requiredFrequencyUnit (Config default: days) parameters. The actual value should reflect your organizations requirements.

##  db-instance-backup-enabled
[db-instance-backup-enabled](https://docs.aws.amazon.com/config/latest/developerguide/db-instance-backup-enabled.html)

Guidance:
The backup feature of Amazon RDS creates backups of your databases and transaction logs. Amazon RDS automatically creates a storage volume snapshot of your DB instance, backing up the entire DB instance. The system allows you to set specific retention periods to meet your resilience requirements.

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

##  efs-in-backup-plan
[efs-in-backup-plan](https://docs.aws.amazon.com/config/latest/developerguide/efs-in-backup-plan.html)

Guidance:
To help with data back-up processes, ensure your Amazon Elastic File System (Amazon EFS) file systems are a part of an AWS Backup plan. AWS Backup is a fully managed backup service with a policy-based backup solution. This solution simplifies your backup management and enables you to meet your business and regulatory backup compliance requirements.

##  elasticache-redis-cluster-automatic-backup-check
[elasticache-redis-cluster-automatic-backup-check](https://docs.aws.amazon.com/config/latest/developerguide/elasticache-redis-cluster-automatic-backup-check.html)

Guidance:
When automatic backups are enabled, Amazon ElastiCache creates a backup of the cluster on a daily basis. The backup can be retained for a number of days as specified by your organization. Automatic backups can help guard against data loss. If a failure occurs, you can create a new cluster, which restores your data from the most recent backup.

##  elb-cross-zone-load-balancing-enabled
[elb-cross-zone-load-balancing-enabled](https://docs.aws.amazon.com/config/latest/developerguide/elb-cross-zone-load-balancing-enabled.html)

Guidance:
Enable cross-zone load balancing for your Elastic Load Balancers (ELBs) to help maintain adequate capacity and availability. The cross-zone load balancing reduces the need to maintain equivalent numbers of instances in each enabled availability zone. It also improves your application's ability to handle the loss of one or more instances.

##  elb-deletion-protection-enabled
[elb-deletion-protection-enabled](https://docs.aws.amazon.com/config/latest/developerguide/elb-deletion-protection-enabled.html)

Guidance:
This rule ensures that Elastic Load Balancing has deletion protection enabled. Use this feature to prevent your load balancer from being accidentally or maliciously deleted, which can lead to loss of availability for your applications.

##  rds-instance-deletion-protection-enabled
[rds-instance-deletion-protection-enabled](https://docs.aws.amazon.com/config/latest/developerguide/rds-instance-deletion-protection-enabled.html)

Guidance:
Ensure Amazon Relational Database Service (Amazon RDS) instances have deletion protection enabled. Use deletion protection to prevent your Amazon RDS instances from being accidentally or maliciously deleted, which can lead to loss of availability for your applications.

##  rds-in-backup-plan
[rds-in-backup-plan](https://docs.aws.amazon.com/config/latest/developerguide/rds-in-backup-plan.html)

Guidance:
To help with data back-up processes, ensure your Amazon Relational Database Service (Amazon RDS) instances are a part of an AWS Backup plan. AWS Backup is a fully managed backup service with a policy-based backup solution. This solution simplifies your backup management and enables you to meet your business and regulatory backup compliance requirements.

##  rds-multi-az-support
[rds-multi-az-support](https://docs.aws.amazon.com/config/latest/developerguide/rds-multi-az-support.html)

Guidance:
Multi-AZ support in Amazon Relational Database Service (Amazon RDS) provides enhanced availability and durability for database instances. When you provision a Multi-AZ database instance, Amazon RDS automatically creates a primary database instance, and synchronously replicates the data to a standby instance in a different Availability Zone. Each Availability Zone runs on its own physically distinct, independent infrastructure, and is engineered to be highly reliable. In case of an infrastructure failure, Amazon RDS performs an automatic failover to the standby so that you can resume database operations as soon as the failover is complete.

##  redshift-backup-enabled
[redshift-backup-enabled](https://docs.aws.amazon.com/config/latest/developerguide/redshift-backup-enabled.html)

Guidance:
To help with data back-up processes, ensure your Amazon Redshift clusters have automated snapshots. When automated snapshots are enabled for a cluster, Redshift periodically takes snapshots of that cluster. By default, Redshift takes a snapshot every eight hours or every 5 GB per node of data changes, or whichever comes first.

##  s3-bucket-default-lock-enabled
[s3-bucket-default-lock-enabled](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-default-lock-enabled.html)

Guidance:
Ensure that your Amazon Simple Storage Service (Amazon S3) bucket has lock enabled, by default. Because sensitive data can exist at rest in S3 buckets, enforce object locks at rest to help protect that data.

##  s3-bucket-replication-enabled
[s3-bucket-replication-enabled](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-replication-enabled.html)

Guidance:
Amazon Simple Storage Service (Amazon S3) Cross-Region Replication (CRR) supports maintaining adequate capacity and availability. CRR enables automatic, asynchronous copying of objects across Amazon S3 buckets to help ensure that data availability is maintained.

##  s3-bucket-versioning-enabled
[s3-bucket-versioning-enabled](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-versioning-enabled.html)

Guidance:
Amazon Simple Storage Service (Amazon S3) bucket versioning helps keep multiple variants of an object in the same Amazon S3 bucket. Use versioning to preserve, retrieve, and restore every version of every object stored in your Amazon S3 bucket. Versioning helps you to easily recover from unintended user actions and application failures.

##  vpc-vpn-2-tunnels-up
[vpc-vpn-2-tunnels-up](https://docs.aws.amazon.com/config/latest/developerguide/vpc-vpn-2-tunnels-up.html)

Guidance:
Redundant Site-to-Site VPN tunnels can be implemented to achieve resilience requirements. It uses two tunnels to help ensure connectivity in case one of the Site-to-Site VPN connections becomes unavailable. To protect against a loss of connectivity, in case your customer gateway becomes unavailable, you can set up a second Site-to-Site VPN connection to your Amazon Virtual Private Cloud (Amazon VPC) and virtual private gateway by using a second customer gateway.
