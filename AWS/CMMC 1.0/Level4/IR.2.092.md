# IR.2.092
Establish an operational incident-handling capability for organizational systems that includes preparation, detection, analysis, containment, recovery, and user response activities.

##  cloudwatch-alarm-action-check
[cloudwatch-alarm-action-check](https://docs.aws.amazon.com/config/latest/developerguide/cloudwatch-alarm-action-check.html)

Guidance:
Amazon CloudWatch alarms alert when a metric breaches the threshold for a specified number of evaluation periods. The alarm performs one or more actions based on the value of the metric or expression relative to a threshold over a number of time periods. This rule requires a value for alarmActionRequired (Config Default: True), insufficientDataActionRequired (Config Default: True), okActionRequired (Config Default: False). The actual value should reflect the alarm actions for your environment.

##  guardduty-enabled-centralized
[guardduty-enabled-centralized](https://docs.aws.amazon.com/config/latest/developerguide/guardduty-enabled-centralized.html)

Guidance:
Amazon GuardDuty can help to monitor and detect potential cybersecurity events by using threat intelligence feeds. These include lists of malicious IPs and machine learning to identify unexpected, unauthorized, and malicious activity within your AWS Cloud environment.

##  guardduty-non-archived-findings
[guardduty-non-archived-findings](https://docs.aws.amazon.com/config/latest/developerguide/guardduty-non-archived-findings.html)

Guidance:
Amazon GuardDuty helps you understand the impact of an incident by classifying findings by severity: low, medium, and high. You can use these classifications for determining remediation strategies and priorities. This rule allows you to optionally set the daysLowSev (Config Default: 30), daysMediumSev (Config Default: 7), and daysHighSev (Config Default: 1) for non-archived findings, as required by your organization's policies.

##  lambda-dlq-check
[lambda-dlq-check](https://docs.aws.amazon.com/config/latest/developerguide/lambda-dlq-check.html)

Guidance:
Enable this rule to help notify the appropriate personnel through Amazon Simple Queue Service (Amazon SQS) or Amazon Simple Notification Service (Amazon SNS) when a function has failed.

##  securityhub-enabled
[securityhub-enabled](https://docs.aws.amazon.com/config/latest/developerguide/securityhub-enabled.html)

Guidance:
AWS Security Hub helps to monitor unauthorized personnel, connections, devices, and software. AWS Security Hub aggregates, organizes, and prioritizes the security alerts, or findings, from multiple AWS services. Some such services are Amazon Security Hub, Amazon Inspector, Amazon Macie, AWS Identity and Access Management (IAM) Access Analyzer, and AWS Firewall Manager, and AWS Partner solutions.
