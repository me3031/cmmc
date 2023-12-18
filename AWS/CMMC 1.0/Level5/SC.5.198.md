# SC.5.198
Configure monitoring systems to record packets passing through the organization's Internet network boundaries and other organizationally defined boundaries.

##  alb-waf-enabled
[alb-waf-enabled](https://docs.aws.amazon.com/config/latest/developerguide/alb-waf-enabled.html)

Guidance:
Ensure AWS WAF is enabled on Elastic Load Balancers (ELB) to help protect web applications. A WAF helps to protect your web applications or APIs against common web exploits. These web exploits may affect availability, compromise security, or consume excessive resources within your environment.

##  api-gw-associated-with-waf
[api-gw-associated-with-waf](https://docs.aws.amazon.com/config/latest/developerguide/api-gw-associated-with-waf.html)

Guidance:
AWS WAF enables you to configure a set of rules (called a web access control list (web ACL)) that allow, block, or count web requests based on customizable web security rules and conditions that you define. Ensure your Amazon API Gateway stage is associated with a WAF Web ACL to protect it from malicious attacks

##  wafv2-logging-enabled
[wafv2-logging-enabled](https://docs.aws.amazon.com/config/latest/developerguide/wafv2-logging-enabled.html)

Guidance:
To help with logging and monitoring within your environment, enable AWS WAF (V2) logging on regional and global web ACLs. AWS WAF logging provides detailed information about the traffic that is analyzed by your web ACL. The logs record the time that AWS WAF received the request from your AWS resource, information about the request, and an action for the rule that each request matched.
