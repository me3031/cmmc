# RE.3.139
Regularly perform complete, comprehensive, and resilient data backups as organizationally defined.

##  backup-plan-min-frequency-and-min-retention-check
[backup-plan-min-frequency-and-min-retention-check](https://docs.aws.amazon.com/config/latest/developerguide/backup-plan-min-frequency-and-min-retention-check.html)

Guidance:
To help with data back-up processes, ensure your AWS Backup plan is set for a minimum frequency and retention. AWS Backup is a fully managed backup service with a policy-based backup solution. This solution simplifies your backup management and enables you to meet your business and regulatory backup compliance requirements. This rule allows you to set the requiredFrequencyValue (Config default: 1),  requiredRetentionDays (Config default: 35) and requiredFrequencyUnit (Config default: days) parameters. The actual value should reflect your organizations requirements.

##  db-instance-backup-enabled
[db-instance-backup-enabled](https://docs.aws.amazon.com/config/latest/developerguide/db-instance-backup-enabled.html)

Guidance:
The backup feature of Amazon RDS creates backups of your databases and transaction logs. Amazon RDS automatically creates a storage volume snapshot of your DB instance, backing up the entire DB instance. The system allows you to set specific retention periods to meet your resilience requirements.

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

##  efs-in-backup-plan
[efs-in-backup-plan](https://docs.aws.amazon.com/config/latest/developerguide/efs-in-backup-plan.html)

Guidance:
To help with data back-up processes, ensure your Amazon Elastic File System (Amazon EFS) file systems are a part of an AWS Backup plan. AWS Backup is a fully managed backup service with a policy-based backup solution. This solution simplifies your backup management and enables you to meet your business and regulatory backup compliance requirements.

##  elasticache-redis-cluster-automatic-backup-check
[elasticache-redis-cluster-automatic-backup-check](https://docs.aws.amazon.com/config/latest/developerguide/elasticache-redis-cluster-automatic-backup-check.html)

Guidance:
When automatic backups are enabled, Amazon ElastiCache creates a backup of the cluster on a daily basis. The backup can be retained for a number of days as specified by your organization. Automatic backups can help guard against data loss. If a failure occurs, you can create a new cluster, which restores your data from the most recent backup.

##  rds-in-backup-plan
[rds-in-backup-plan](https://docs.aws.amazon.com/config/latest/developerguide/rds-in-backup-plan.html)

Guidance:
To help with data back-up processes, ensure your Amazon Relational Database Service (Amazon RDS) instances are a part of an AWS Backup plan. AWS Backup is a fully managed backup service with a policy-based backup solution. This solution simplifies your backup management and enables you to meet your business and regulatory backup compliance requirements.

##  redshift-backup-enabled
[redshift-backup-enabled](https://docs.aws.amazon.com/config/latest/developerguide/redshift-backup-enabled.html)

Guidance:
To help with data back-up processes, ensure your Amazon Redshift clusters have automated snapshots. When automated snapshots are enabled for a cluster, Redshift periodically takes snapshots of that cluster. By default, Redshift takes a snapshot every eight hours or every 5 GB per node of data changes, or whichever comes first.

##  s3-bucket-replication-enabled
[s3-bucket-replication-enabled](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-replication-enabled.html)

Guidance:
Amazon Simple Storage Service (Amazon S3) Cross-Region Replication (CRR) supports maintaining adequate capacity and availability. CRR enables automatic, asynchronous copying of objects across Amazon S3 buckets to help ensure that data availability is maintained.
