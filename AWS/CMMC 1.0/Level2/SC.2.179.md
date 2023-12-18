# SC.2.179
Use encrypted sessions for the management of network devices.

##  alb-http-to-https-redirection-check
[alb-http-to-https-redirection-check](https://docs.aws.amazon.com/config/latest/developerguide/alb-http-to-https-redirection-check.html)

Guidance:
To help protect data in transit, ensure that your Application Load Balancer automatically redirects unencrypted HTTP requests to HTTPS. Because sensitive data can exist, enable encryption in transit to help protect that data.

##  api-gw-ssl-enabled
[api-gw-ssl-enabled](https://docs.aws.amazon.com/config/latest/developerguide/api-gw-ssl-enabled.html)

Guidance:
Ensure Amazon API Gateway REST API stages are configured with SSL certificates to allow backend systems to authenticate that requests originate from API Gateway.

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
