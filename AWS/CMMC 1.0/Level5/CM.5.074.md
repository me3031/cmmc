# CM.5.074
Verify the integrity and correctness of security critical or essential software as defined by the organization (e.g., roots of trust, formal verification, or cryptographic signatures).

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
