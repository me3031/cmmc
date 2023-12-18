# CM.2.064
Establish and enforce security configuration settings for information technology products employed in organizational systems.

##  account-part-of-organizations
[account-part-of-organizations](https://docs.aws.amazon.com/config/latest/developerguide/account-part-of-organizations.html)

Guidance:
Centralized management of AWS accounts within AWS Organizations helps to ensure that accounts are compliant. The lack of centralized account governance may lead to inconsistent account configurations, which may expose resources and sensitive data.

##  cloudtrail-security-trail-enabled
[cloudtrail-security-trail-enabled](https://docs.aws.amazon.com/config/latest/developerguide/cloudtrail-security-trail-enabled.html)

Guidance:
This rule helps ensure the use of AWS recommended security best practices for AWS CloudTrail, by checking for the enablement of multiple settings. These include the use of log encryption, log validation, and enabling AWS CloudTrail in multiple regions.

##  cloud-trail-log-file-validation-enabled
[cloud-trail-log-file-validation-enabled](https://docs.aws.amazon.com/config/latest/developerguide/cloud-trail-log-file-validation-enabled.html)

Guidance:
Utilize AWS CloudTrail log file validation to check the integrity of CloudTrail logs. Log file validation helps determine if a log file was modified or deleted or unchanged after CloudTrail delivered it. This feature is built using industry standard algorithms: SHA-256 for hashing and SHA-256 with RSA for digital signing. This makes it computationally infeasible to modify, delete or forge CloudTrail log files without detection.

##  ec2-instance-managed-by-systems-manager
[ec2-instance-managed-by-systems-manager](https://docs.aws.amazon.com/config/latest/developerguide/ec2-instance-managed-by-systems-manager.html)

Guidance:
An inventory of the software platforms and applications within the organization is possible by managing Amazon Elastic Compute Cloud (Amazon EC2) instances with AWS Systems Manager. Use AWS Systems Manager to provide detailed system configurations, operating system patch levels, services name and type, software installations, application name, publisher and version, and other details about your environment.

##  ec2-managedinstance-association-compliance-status-check
[ec2-managedinstance-association-compliance-status-check](https://docs.aws.amazon.com/config/latest/developerguide/ec2-managedinstance-association-compliance-status-check.html)

Guidance:
Use AWS Systems Manager Associations to help with inventory of software platforms and applications within an organization. AWS Systems Manager assigns a configuration state to your managed instances and allows you to set baselines of operating system patch levels, software installations, application configurations, and other details about your environment.

##  ec2-managedinstance-patch-compliance-status-check
[ec2-managedinstance-patch-compliance-status-check](https://docs.aws.amazon.com/config/latest/developerguide/ec2-managedinstance-patch-compliance-status-check.html)

Guidance:
Enable this rule to help with identification and documentation of Amazon Elastic Compute Cloud (Amazon EC2) vulnerabilities. The rule checks if Amazon EC2 instance patch compliance in AWS Systems Manager as required by your organization's policies and procedures.

##  elastic-beanstalk-managed-updates-enabled
[elastic-beanstalk-managed-updates-enabled](https://docs.aws.amazon.com/config/latest/developerguide/elastic-beanstalk-managed-updates-enabled.html)

Guidance:
Enabling managed platform updates for an Amazon Elastic Beanstalk environment ensures that the latest available platform fixes, updates, and features for the environment are installed. Keeping up to date with patch installation is a best practice  in securing systems.

##  guardduty-enabled-centralized
[guardduty-enabled-centralized](https://docs.aws.amazon.com/config/latest/developerguide/guardduty-enabled-centralized.html)

Guidance:
Amazon GuardDuty can help to monitor and detect potential cybersecurity events by using threat intelligence feeds. These include lists of malicious IPs and machine learning to identify unexpected, unauthorized, and malicious activity within your AWS Cloud environment.

##  rds-automatic-minor-version-upgrade-enabled
[rds-automatic-minor-version-upgrade-enabled](https://docs.aws.amazon.com/config/latest/developerguide/rds-automatic-minor-version-upgrade-enabled.html)

Guidance:
Enable automatic minor version upgrades on your Amazon Relational Database Service (RDS) instances to ensure the latest minor version updates to the Relational Database Management System (RDBMS) are installed, which may include security patches and bug fixes.

##  redshift-cluster-maintenancesettings-check
[redshift-cluster-maintenancesettings-check](https://docs.aws.amazon.com/config/latest/developerguide/redshift-cluster-maintenancesettings-check.html)

Guidance:
This rule ensures that Amazon Redshift clusters have the preferred settings for your organization. Specifically, that they have preferred maintenance windows and automated snapshot retention periods for the database. This rule requires you to set the allowVersionUpgrade. The default is true. It also lets you optionally set the preferredMaintenanceWindow (the default is sat:16:00-sat:16:30), and the automatedSnapshotRetentionPeriod (the default is 1). The actual values should reflect your organization's policies.

##  securityhub-enabled
[securityhub-enabled](https://docs.aws.amazon.com/config/latest/developerguide/securityhub-enabled.html)

Guidance:
AWS Security Hub helps to monitor unauthorized personnel, connections, devices, and software. AWS Security Hub aggregates, organizes, and prioritizes the security alerts, or findings, from multiple AWS services. Some such services are Amazon Security Hub, Amazon Inspector, Amazon Macie, AWS Identity and Access Management (IAM) Access Analyzer, and AWS Firewall Manager, and AWS Partner solutions.
