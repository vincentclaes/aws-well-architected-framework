# AWS Well Architected Framework

notes and links while following the AWS Well Architected Franework

## Links

- Help you with reviews: https://www.wellarchitectedlabs.com/
- Upgrade your skills: https://explore.skillbuilder.aws/learn

## Thoughts

- These pillars are a useful framework to review an architecture of an application.
- The course + labs are focused towards classic, legacy applications that are setup in the basic compute units like EC2. Last time I touched an EC2 was 5 years ago. There is not a lot of emphasis on serverless/managed services which are "hot" at the moment. This course is interesting if you need to migrate a legacy application as-is to the cloud. Not so much on serverless appications or greenfield applications.



## Summary

AWS Well architected is a set of tools, principles to review an architecture.
It reminds me of applying DevSecOps principles to an application in the cloud

It's based on 6 pillars

- Operational excellence; __automation__, setup a CICD and use infra-as-code and continuous improve this process 
- Reliability; __recover from disruptions__, seperate state from run with a cache, for example. Apply horizontal scaling. Inject faults in the CICD to validate the resilience.
- Security; __access__, RBAC (role based access control), humans cannot access data by default, multi account setup, traceability (Cloudtrail)
- Performance; __democratize advanced tech__, serverless and managed services abstract away the complicated part of advanced tech. For example AWS Glue.
- Cost; __finops__, use instances when you need them. Monitor the cost versus the revenue. 
- Sustainability; __reduce carbon__, maximize utilization when needed. Stop instances when you do not need them.

## Notes
![summary.png](summary.png)
