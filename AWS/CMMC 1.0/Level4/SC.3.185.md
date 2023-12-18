# SC.3.185
Implement cryptographic mechanisms to prevent unauthorized disclosure of CUI during transmission unless otherwise protected by alternative physical safeguards.

##  acm-certificate-expiration-check
[acm-certificate-expiration-check](https://docs.aws.amazon.com/config/latest/developerguide/acm-certificate-expiration-check.html)

Guidance:
Ensure network integrity is protected by ensuring X509 certificates are issued by AWS ACM. These certificates must be valid and unexpired. This rule requires a value for daysToExpiration (AWS Foundational Security Best Practices value: 90). The actual value should reflect your organization's policies.

##  alb-http-drop-invalid-header-enabled
[alb-http-drop-invalid-header-enabled](https://docs.aws.amazon.com/config/latest/developerguide/alb-http-drop-invalid-header-enabled.html)

Guidance:
Ensure that your Elastic Load Balancers (ELB) are configured to drop http headers. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  alb-http-to-https-redirection-check
[alb-http-to-https-redirection-check](https://docs.aws.amazon.com/config/latest/developerguide/alb-http-to-https-redirection-check.html)

Guidance:
To help protect data in transit, ensure that your Application Load Balancer automatically redirects unencrypted HTTP requests to HTTPS. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  api-gw-ssl-enabled
[api-gw-ssl-enabled](https://docs.aws.amazon.com/config/latest/developerguide/api-gw-ssl-enabled.html)

Guidance:
Ensure Amazon API Gateway REST API stages are configured with SSL certificates to allow backend systems to authenticate that requests originate from API Gateway.

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

##  redshift-require-tls-ssl
[redshift-require-tls-ssl](https://docs.aws.amazon.com/config/latest/developerguide/redshift-require-tls-ssl.html)

Guidance:
Ensure that your Amazon Redshift clusters require TLS/SSL encryption to connect to SQL clients. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  s3-bucket-ssl-requests-only
[s3-bucket-ssl-requests-only](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-ssl-requests-only.html)

Guidance:
To help protect data in transit, ensure that your Amazon Simple Storage Service (Amazon S3) buckets require requests to use Secure Socket Layer (SSL). Because sensitive data can exist, enable encryption in transit to help protect that data.

##  opensearch-node-to-node-encryption-check
[opensearch-node-to-node-encryption-check](https://docs.aws.amazon.com/config/latest/developerguide/opensearch-node-to-node-encryption-check.html)

Guidance:
Ensure node-to-node encryption for Amazon OpenSearch Service is enabled. Node-to-node encryption enables TLS 1.2 encryption for all communications within the Amazon Virtual Private Cloud (Amazon VPC). Because sensitive data can exist, enable encryption in transit to help protect that data.
