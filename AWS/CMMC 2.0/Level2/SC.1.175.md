# SC.1.175
Monitor, control, and protect organizational communications (i.e., information transmitted or received by organizational information systems) at the external boundaries and key internal boundaries of the information systems.

##  alb-http-drop-invalid-header-enabled
[alb-http-drop-invalid-header-enabled](https://docs.aws.amazon.com/config/latest/developerguide/alb-http-drop-invalid-header-enabled.html)

Guidance:
Ensure that your Elastic Load Balancers (ELB) are configured to drop http headers. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  alb-http-to-https-redirection-check
[alb-http-to-https-redirection-check](https://docs.aws.amazon.com/config/latest/developerguide/alb-http-to-https-redirection-check.html)

Guidance:
To help protect data in transit, ensure that your Application Load Balancer automatically redirects unencrypted HTTP requests to HTTPS. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  alb-waf-enabled
[alb-waf-enabled](https://docs.aws.amazon.com/config/latest/developerguide/alb-waf-enabled.html)

Guidance:
Ensure AWS WAF is enabled on Elastic Load Balancers (ELB) to help protect web applications. A WAF helps to protect your web applications or APIs against common web exploits. These web exploits may affect availability, compromise security, or consume excessive resources within your environment.

##  api-gw-associated-with-waf
[api-gw-associated-with-waf](https://docs.aws.amazon.com/config/latest/developerguide/api-gw-associated-with-waf.html)

Guidance:
AWS WAF enables you to configure a set of rules (called a web access control list (web ACL)) that allow, block, or count web requests based on customizable web security rules and conditions that you define. Ensure your Amazon API Gateway stage is associated with a WAF Web ACL to protect it from malicious attacks

##  cloudwatch-alarm-action-check
[cloudwatch-alarm-action-check](https://docs.aws.amazon.com/config/latest/developerguide/cloudwatch-alarm-action-check.html)

Guidance:
Amazon CloudWatch alarms alert when a metric breaches the threshold for a specified number of evaluation periods. The alarm performs one or more actions based on the value of the metric or expression relative to a threshold over a number of time periods. This rule requires a value for alarmActionRequired (Config Default: True), insufficientDataActionRequired (Config Default: True), okActionRequired (Config Default: False). The actual value should reflect the alarm actions for your environment.

##  dms-replication-not-public
[dms-replication-not-public](https://docs.aws.amazon.com/config/latest/developerguide/dms-replication-not-public.html)

Guidance:
Manage access to the AWS Cloud by ensuring DMS replication instances cannot be publicly accessed. DMS replication instances can contain sensitive information and access control is required for such accounts.

##  ebs-snapshot-public-restorable-check
[ebs-snapshot-public-restorable-check](https://docs.aws.amazon.com/config/latest/developerguide/ebs-snapshot-public-restorable-check.html)

Guidance:
Manage access to the AWS Cloud by ensuring EBS snapshots are not publicly restorable. EBS volume snapshots can contain sensitive information and access control is required for such accounts.

##  elasticsearch-in-vpc-only
[elasticsearch-in-vpc-only](https://docs.aws.amazon.com/config/latest/developerguide/elasticsearch-in-vpc-only.html)

Guidance:
Manage access to the AWS Cloud by ensuring Amazon OpenSearch Service (OpenSearch Service) Domains are within an Amazon Virtual Private Cloud (Amazon VPC). An OpenSearch Service domain within an Amazon VPC enables secure communication between OpenSearch Service and other services within the Amazon VPC without the need for an internet gateway, NAT device, or VPN connection.

##  elasticsearch-node-to-node-encryption-check
[elasticsearch-node-to-node-encryption-check](https://docs.aws.amazon.com/config/latest/developerguide/elasticsearch-node-to-node-encryption-check.html)

Guidance:
Ensure node-to-node encryption for Amazon OpenSearch Service is enabled. Node-to-node encryption enables TLS 1.2 encryption for all communications within the Amazon Virtual Private Cloud (Amazon VPC). Because sensitive data can exist, enable encryption in transit to help protect that data.

##  elb-acm-certificate-required
[elb-acm-certificate-required](https://docs.aws.amazon.com/config/latest/developerguide/elb-acm-certificate-required.html)

Guidance:
Because sensitive data can exist and to help protect data at transit, ensure encryption is enabled for your Elastic Load Balancing. Use AWS Certificate Manager to manage, provision and deploy public and private SSL/TLS certificates with AWS services and internal resources.

##  elb-tls-https-listeners-only
[elb-tls-https-listeners-only](https://docs.aws.amazon.com/config/latest/developerguide/elb-tls-https-listeners-only.html)

Guidance:
Ensure that your Elastic Load Balancers (ELBs) are configured with SSL or HTTPS listeners. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  guardduty-enabled-centralized
[guardduty-enabled-centralized](https://docs.aws.amazon.com/config/latest/developerguide/guardduty-enabled-centralized.html)

Guidance:
Amazon GuardDuty can help to monitor and detect potential cybersecurity events by using threat intelligence feeds. These include lists of malicious IPs and machine learning to identify unexpected, unauthorized, and malicious activity within your AWS Cloud environment.

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

##  redshift-require-tls-ssl
[redshift-require-tls-ssl](https://docs.aws.amazon.com/config/latest/developerguide/redshift-require-tls-ssl.html)

Guidance:
Ensure that your Amazon Redshift clusters require TLS/SSL encryption to connect to SQL clients. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  restricted-common-ports
[restricted-common-ports](https://docs.aws.amazon.com/config/latest/developerguide/restricted-common-ports.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring common ports are restricted on Amazon Elastic Compute Cloud (Amazon EC2) security groups. Not restricting access to ports to trusted sources can lead to attacks against the availability, integrity and confidentiality of systems. This rule allows you to optionally set blockedPort1 - blockedPort5 parameters (Config Defaults: 20,21,3389,3306,4333). The actual values should reflect your organization's policies.

##  s3-account-level-public-access-blocks-periodic
[s3-account-level-public-access-blocks-periodic](https://docs.aws.amazon.com/config/latest/developerguide/s3-account-level-public-access-blocks-periodic.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon Simple Storage Service (Amazon S3) buckets cannot be publicly accessed. This rule helps keeping sensitive data safe from unauthorized remote users by preventing public access. This rule allows you to optionally set the ignorePublicAcls (Config Default: True), blockPublicPolicy (Config Default: True), blockPublicAcls (Config Default: True), and restrictPublicBuckets parameters (Config Default: True). The actual values should reflect your organization's policies.

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

##  s3-bucket-ssl-requests-only
[s3-bucket-ssl-requests-only](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-ssl-requests-only.html)

Guidance:
To help protect data in transit, ensure that your Amazon Simple Storage Service (Amazon S3) buckets require requests to use Secure Socket Layer (SSL). Because sensitive data can exist, enable encryption in transit to help protect that data.

##  sagemaker-notebook-no-direct-internet-access
[sagemaker-notebook-no-direct-internet-access](https://docs.aws.amazon.com/config/latest/developerguide/sagemaker-notebook-no-direct-internet-access.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring that Amazon SageMaker notebooks do not allow direct internet access. By preventing direct internet access, you can keep sensitive data from being accessed by unauthorized users.

##  securityhub-enabled
[securityhub-enabled](https://docs.aws.amazon.com/config/latest/developerguide/securityhub-enabled.html)

Guidance:
AWS Security Hub helps to monitor unauthorized personnel, connections, devices, and software. AWS Security Hub aggregates, organizes, and prioritizes the security alerts, or findings, from multiple AWS services. Some such services are Amazon Security Hub, Amazon Inspector, Amazon Macie, AWS Identity and Access Management (IAM) Access Analyzer, and AWS Firewall Manager, and AWS Partner solutions.

##  ssm-document-not-public
[ssm-document-not-public](https://docs.aws.amazon.com/config/latest/developerguide/ssm-document-not-public.html)

Guidance:
Ensure AWS Systems Manager (SSM) documents are not public, as this may allow unintended access to your SSM documents. A public SSM document can expose information about your account, resources and internal processes.

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

##  opensearch-node-to-node-encryption-check
[opensearch-node-to-node-encryption-check](https://docs.aws.amazon.com/config/latest/developerguide/opensearch-node-to-node-encryption-check.html)

Guidance:
Ensure node-to-node encryption for Amazon OpenSearch Service is enabled. Node-to-node encryption enables TLS 1.2 encryption for all communications within the Amazon Virtual Private Cloud (Amazon VPC). Because sensitive data can exist, enable encryption in transit to help protect that data.
