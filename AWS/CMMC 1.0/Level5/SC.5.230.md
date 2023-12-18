# SC.5.230
Enforce port and protocol compliance.

##  alb-http-to-https-redirection-check
[alb-http-to-https-redirection-check](https://docs.aws.amazon.com/config/latest/developerguide/alb-http-to-https-redirection-check.html)

Guidance:
To help protect data in transit, ensure that your Application Load Balancer automatically redirects unencrypted HTTP requests to HTTPS. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  api-gw-ssl-enabled
[api-gw-ssl-enabled](https://docs.aws.amazon.com/config/latest/developerguide/api-gw-ssl-enabled.html)

Guidance:
Ensure Amazon API Gateway REST API stages are configured with SSL certificates to allow backend systems to authenticate that requests originate from API Gateway.

##  elb-tls-https-listeners-only
[elb-tls-https-listeners-only](https://docs.aws.amazon.com/config/latest/developerguide/elb-tls-https-listeners-only.html)

Guidance:
Ensure that your Elastic Load Balancers (ELBs) are configured with SSL or HTTPS listeners. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  restricted-ssh
[restricted-ssh](https://docs.aws.amazon.com/config/latest/developerguide/restricted-ssh.html)

Guidance:
Amazon Elastic Compute Cloud (Amazon EC2) Security Groups can help manage network access by providing stateful filtering of ingress and egress network traffic to AWS resources. Not allowing ingress (or remote) traffic from 0.0.0.0/0 to port 22 on your resources help you restricting remote access.

##  redshift-require-tls-ssl
[redshift-require-tls-ssl](https://docs.aws.amazon.com/config/latest/developerguide/redshift-require-tls-ssl.html)

Guidance:
Ensure that your Amazon Redshift clusters require TLS/SSL encryption to connect to SQL clients. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  restricted-common-ports
[restricted-common-ports](https://docs.aws.amazon.com/config/latest/developerguide/restricted-common-ports.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring common ports are restricted on Amazon Elastic Compute Cloud (Amazon EC2) security groups. Not restricting access to ports to trusted sources can lead to attacks against the availability, integrity and confidentiality of systems. This rule allows you to optionally set blockedPort1 - blockedPort5 parameters (Config Defaults: 20,21,3389,3306,4333). The actual values should reflect your organization's policies.

##  s3-bucket-ssl-requests-only
[s3-bucket-ssl-requests-only](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-ssl-requests-only.html)

Guidance:
To help protect data in transit, ensure that your Amazon Simple Storage Service (Amazon S3) buckets require requests to use Secure Socket Layer (SSL). Because sensitive data can exist, enable encryption in transit to help protect that data.

##  vpc-default-security-group-closed
[vpc-default-security-group-closed](https://docs.aws.amazon.com/config/latest/developerguide/vpc-default-security-group-closed.html)

Guidance:
Amazon Elastic Compute Cloud (Amazon EC2) security groups can help in the management of network access by providing stateful filtering of ingress and egress network traffic to AWS resources. Restricting all the traffic on the default security group helps in restricting remote access to your AWS resources.

##  vpc-sg-open-only-to-authorized-ports
[vpc-sg-open-only-to-authorized-ports](https://docs.aws.amazon.com/config/latest/developerguide/vpc-sg-open-only-to-authorized-ports.html)

Guidance:
Manage access to resources in the AWS Cloud by ensuring common ports are restricted on Amazon Elastic Compute Cloud (Amazon EC2) Security Groups. Not restricting access on ports to trusted sources can lead to attacks against the availability, integrity and confidentiality of systems. By restricting access to resources within a security group from the internet (0.0.0.0/0) remote access can be controlled to internal systems.
