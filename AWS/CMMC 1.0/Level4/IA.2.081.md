# IA.2.081
Store and transmit only cryptographically-protected passwords.

##  alb-http-drop-invalid-header-enabled
[alb-http-drop-invalid-header-enabled](https://docs.aws.amazon.com/config/latest/developerguide/alb-http-drop-invalid-header-enabled.html)

Guidance:
Ensure that your Elastic Load Balancers (ELB) are configured to drop http headers. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  alb-http-to-https-redirection-check
[alb-http-to-https-redirection-check](https://docs.aws.amazon.com/config/latest/developerguide/alb-http-to-https-redirection-check.html)

Guidance:
To help protect data in transit, ensure that your Application Load Balancer automatically redirects unencrypted HTTP requests to HTTPS. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  api-gw-cache-enabled-and-encrypted
[api-gw-cache-enabled-and-encrypted](https://docs.aws.amazon.com/config/latest/developerguide/api-gw-cache-enabled-and-encrypted.html)

Guidance:
To help protect data at rest, ensure encryption is enabled for your API Gateway stage's cache. Because sensitive data can be captured for the API method, enable encryption at rest to help protect that data.

##  api-gw-ssl-enabled
[api-gw-ssl-enabled](https://docs.aws.amazon.com/config/latest/developerguide/api-gw-ssl-enabled.html)

Guidance:
Ensure Amazon API Gateway REST API stages are configured with SSL certificates to allow backend systems to authenticate that requests originate from API Gateway.

##  ec2-ebs-encryption-by-default
[ec2-ebs-encryption-by-default](https://docs.aws.amazon.com/config/latest/developerguide/ec2-ebs-encryption-by-default.html)

Guidance:
To help protect data at rest, ensure that encryption is enabled for your Amazon Elastic Block Store (Amazon EBS) volumes. Because sensitive data can exist at rest in these volumes, enable encryption at rest to help protect that data.

##  efs-encrypted-check
[efs-encrypted-check](https://docs.aws.amazon.com/config/latest/developerguide/efs-encrypted-check.html)

Guidance:
Because sensitive data can exist and to help protect data at rest, ensure encryption is enabled for your Amazon Elastic File System (EFS).

##  elasticsearch-encrypted-at-rest
[elasticsearch-encrypted-at-rest](https://docs.aws.amazon.com/config/latest/developerguide/elasticsearch-encrypted-at-rest.html)

Guidance:
Because sensitive data can exist and to help protect data at rest, ensure encryption is enabled for your Amazon OpenSearch Service (OpenSearch Service) domains.

##  elasticsearch-node-to-node-encryption-check
[elasticsearch-node-to-node-encryption-check](https://docs.aws.amazon.com/config/latest/developerguide/elasticsearch-node-to-node-encryption-check.html)

Guidance:
Ensure node-to-node encryption for Amazon OpenSearch Service is enabled. Node-to-node encryption enables TLS 1.2 encryption for all communications within the Amazon Virtual Private Cloud (Amazon VPC). Because sensitive data can exist, enable encryption in transit to help protect that data.

##  elbv2-acm-certificate-required
[elbv2-acm-certificate-required](https://docs.aws.amazon.com/config/latest/developerguide/elbv2-acm-certificate-required.html)

Guidance:
Because sensitive data can exist and to help protect data at transit, ensure encryption is enabled for your Elastic Load Balancing. Use AWS Certificate Manager to manage, provision and deploy public and private SSL/TLS certificates with AWS services and internal resources.

##  elb-acm-certificate-required
[elb-acm-certificate-required](https://docs.aws.amazon.com/config/latest/developerguide/elb-acm-certificate-required.html)

Guidance:
Because sensitive data can exist and to help protect data at transit, ensure encryption is enabled for your Elastic Load Balancing. Use AWS Certificate Manager to manage, provision and deploy public and private SSL/TLS certificates with AWS services and internal resources.

##  elb-tls-https-listeners-only
[elb-tls-https-listeners-only](https://docs.aws.amazon.com/config/latest/developerguide/elb-tls-https-listeners-only.html)

Guidance:
Ensure that your Elastic Load Balancers (ELBs) are configured with SSL or HTTPS listeners. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  encrypted-volumes
[encrypted-volumes](https://docs.aws.amazon.com/config/latest/developerguide/encrypted-volumes.html)

Guidance:
Because sensitive data can exist and to help protect data at rest, ensure encryption is enabled for your Amazon Elastic Block Store (Amazon EBS) volumes.

##  rds-snapshot-encrypted
[rds-snapshot-encrypted](https://docs.aws.amazon.com/config/latest/developerguide/rds-snapshot-encrypted.html)

Guidance:
Ensure that encryption is enabled for your Amazon Relational Database Service (Amazon RDS) snapshots. Because sensitive data can exist at rest, enable encryption at rest to help protect that data.

##  rds-storage-encrypted
[rds-storage-encrypted](https://docs.aws.amazon.com/config/latest/developerguide/rds-storage-encrypted.html)

Guidance:
To help protect data at rest, ensure that encryption is enabled for your Amazon Relational Database Service (Amazon RDS) instances. Because sensitive data can exist at rest in Amazon RDS instances, enable encryption at rest to help protect that data.

##  redshift-cluster-kms-enabled
[redshift-cluster-kms-enabled](https://docs.aws.amazon.com/config/latest/developerguide/redshift-cluster-kms-enabled.html)

Guidance:
To help protect data at rest, ensure encryption with AWS Key Management Service (AWS KMS) is enabled for your Amazon Redshift cluster. Because sensitive data can exist at rest in Redshift clusters, enable encryption at rest to help protect that data.

##  redshift-require-tls-ssl
[redshift-require-tls-ssl](https://docs.aws.amazon.com/config/latest/developerguide/redshift-require-tls-ssl.html)

Guidance:
Ensure that your Amazon Redshift clusters require TLS/SSL encryption to connect to SQL clients. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  s3-bucket-server-side-encryption-enabled
[s3-bucket-server-side-encryption-enabled](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-server-side-encryption-enabled.html)

Guidance:
To help protect data at rest, ensure encryption is enabled for your Amazon Simple Storage Service (Amazon S3) buckets. Because sensitive data can exist at rest in Amazon S3 buckets, enable encryption to help protect that data.

##  s3-bucket-ssl-requests-only
[s3-bucket-ssl-requests-only](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-ssl-requests-only.html)

Guidance:
To help protect data in transit, ensure that your Amazon Simple Storage Service (Amazon S3) buckets require requests to use Secure Socket Layer (SSL). Because sensitive data can exist, enable encryption in transit to help protect that data.

##  s3-default-encryption-kms
[s3-default-encryption-kms](https://docs.aws.amazon.com/config/latest/developerguide/s3-default-encryption-kms.html)

Guidance:
Ensure that encryption is enabled for your Amazon Simple Storage Service (Amazon S3) buckets. Because sensitive data can exist at rest in an Amazon S3 bucket, enable encryption at rest to help protect that data.

##  sagemaker-endpoint-configuration-kms-key-configured
[sagemaker-endpoint-configuration-kms-key-configured](https://docs.aws.amazon.com/config/latest/developerguide/sagemaker-endpoint-configuration-kms-key-configured.html)

Guidance:
To help protect data at rest, ensure encryption with AWS Key Management Service (AWS KMS) is enabled for your SageMaker endpoint. Because sensitive data can exist at rest in SageMaker endpoint, enable encryption at rest to help protect that data.

##  sagemaker-notebook-instance-kms-key-configured
[sagemaker-notebook-instance-kms-key-configured](https://docs.aws.amazon.com/config/latest/developerguide/sagemaker-notebook-instance-kms-key-configured.html)

Guidance:
To help protect data at rest, ensure encryption with AWS Key Management Service (AWS KMS) is enabled for your SageMaker notebook. Because sensitive data can exist at rest in SageMaker notebook, enable encryption at rest to help protect that data.

##  sns-encrypted-kms
[sns-encrypted-kms](https://docs.aws.amazon.com/config/latest/developerguide/sns-encrypted-kms.html)

Guidance:
To help protect data at rest, ensure that your Amazon Simple Notification Service (Amazon SNS) topics require encryption using AWS Key Management Service (AWS KMS). Because sensitive data can exist at rest in published messages, enable encryption at rest to help protect that data.

##  opensearch-encrypted-at-rest
[opensearch-encrypted-at-rest](https://docs.aws.amazon.com/config/latest/developerguide/opensearch-encrypted-at-rest.html)

Guidance:
Because sensitive data can exist and to help protect data at rest, ensure encryption is enabled for your Amazon OpenSearch Service domains.

##  opensearch-node-to-node-encryption-check
[opensearch-node-to-node-encryption-check](https://docs.aws.amazon.com/config/latest/developerguide/opensearch-node-to-node-encryption-check.html)

Guidance:
Ensure node-to-node encryption for Amazon OpenSearch Service is enabled. Node-to-node encryption enables TLS 1.2 encryption for all communications within the Amazon Virtual Private Cloud (Amazon VPC). Because sensitive data can exist, enable encryption in transit to help protect that data.
