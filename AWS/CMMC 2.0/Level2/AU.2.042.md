# AU.2.042
Create and retain system audit logs and records to the extent needed to enable the monitoring, analysis, investigation, and reporting of unlawful or unauthorized system activity.

##  api-gw-execution-logging-enabled
[api-gw-execution-logging-enabled](https://docs.aws.amazon.com/config/latest/developerguide/api-gw-execution-logging-enabled.html)

Guidance:
API Gateway logging displays detailed views of users who accessed the API and the way they accessed the API. This insight enables visibility of user activities.

##  cloudtrail-s3-dataevents-enabled
[cloudtrail-s3-dataevents-enabled](https://docs.aws.amazon.com/config/latest/developerguide/cloudtrail-s3-dataevents-enabled.html)

Guidance:
The collection of Simple Storage Service (Amazon S3) data events helps in detecting any anomalous activity. The details include AWS account information that accessed an Amazon S3 bucket, IP address, and time of event.

##  cloud-trail-cloud-watch-logs-enabled
[cloud-trail-cloud-watch-logs-enabled](https://docs.aws.amazon.com/config/latest/developerguide/cloud-trail-cloud-watch-logs-enabled.html)

Guidance:
Use Amazon CloudWatch to centrally collect and manage log event activity. Inclusion of AWS CloudTrail data provides details of API call activity within your AWS account.

##  cloudtrail-enabled
[cloudtrail-enabled](https://docs.aws.amazon.com/config/latest/developerguide/cloudtrail-enabled.html)

Guidance:
AWS CloudTrail can help in non-repudiation by recording AWS Management Console actions and API calls. You can identify the users and AWS accounts that called an AWS service, the source IP address where the calls generated, and the timings of the calls. Details of captured data are seen within AWS CloudTrail Record Contents.

##  cw-loggroup-retention-period-check
[cw-loggroup-retention-period-check](https://docs.aws.amazon.com/config/latest/developerguide/cw-loggroup-retention-period-check.html)

Guidance:
Ensure a minimum duration of event log data is retained for your log groups to help with troubleshooting and forensics investigations. The lack of available past event log data makes it difficult to reconstruct and identify potentially malicious events.

##  elb-logging-enabled
[elb-logging-enabled](https://docs.aws.amazon.com/config/latest/developerguide/elb-logging-enabled.html)

Guidance:
Elastic Load Balancing activity is a central point of communication within an environment. Ensure ELB logging is enabled. The collected data provides detailed information about requests sent to the ELB. Each log contains information such as the time the request was received, the client's IP address, latencies, request paths, and server responses.

##  multi-region-cloudtrail-enabled
[multi-region-cloudtrail-enabled](https://docs.aws.amazon.com/config/latest/developerguide/multi-region-cloudtrail-enabled.html)

Guidance:
AWS CloudTrail records AWS Management Console actions and API calls. You can identify which users and accounts called AWS, the source IP address from where the calls were made, and when the calls occurred. CloudTrail will deliver log files from all AWS Regions to your S3 bucket if MULTI_REGION_CLOUD_TRAIL_ENABLED is enabled. Additionally, when AWS launches a new Region, CloudTrail will create the same trail in the new Region. As a result, you will receive log files containing API activity for the new Region without taking any action.

##  rds-logging-enabled
[rds-logging-enabled](https://docs.aws.amazon.com/config/latest/developerguide/rds-logging-enabled.html)

Guidance:
To help with logging and monitoring within your environment, ensure Amazon Relational Database Service (Amazon RDS) logging is enabled. With Amazon RDS logging, you can capture events such as connections, disconnections, queries, or tables queried.

##  s3-bucket-logging-enabled
[s3-bucket-logging-enabled](https://docs.aws.amazon.com/config/latest/developerguide/s3-bucket-logging-enabled.html)

Guidance:
Amazon Simple Storage Service (Amazon S3) server access logging provides a method to monitor the network for potential cybersecurity events. The events are monitored by capturing detailed records for the requests that are made to an Amazon S3 bucket. Each access log record provides details about a single access request. The details include the requester, bucket name, request time, request action, response status, and an error code, if relevant.

##  wafv2-logging-enabled
[wafv2-logging-enabled](https://docs.aws.amazon.com/config/latest/developerguide/wafv2-logging-enabled.html)

Guidance:
To help with logging and monitoring within your environment, enable AWS WAF (V2) logging on regional and global web ACLs. AWS WAF logging provides detailed information about the traffic that is analyzed by your web ACL. The logs record the time that AWS WAF received the request from your AWS resource, information about the request, and an action for the rule that each request matched.
