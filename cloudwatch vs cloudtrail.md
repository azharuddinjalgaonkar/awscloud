**CloudWatch vs CloudTrail in AWS

AWS CloudWatch

CloudWatch focuses on the activity of AWS services and resources, reporting on their health and performance.

CloudTrail is a log of all actions that have taken place inside your AWS environment.

CloudWatch:
AWS CloudWatch is a monitoring service for AWS cloud resources and the applications you run on AWS. You can use Amazon CloudWatch to collect and track metrics, collect and monitor log files, set alarms, and automatically react to changes in your AWS resources.

CloudTrail:
AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. CloudTrail provides event history of your AWS account activity, including actions taken through the AWS Management Console, AWS SDKs, command line tools, and other AWS services. This event history simplifies security analysis, resource change tracking, and troubleshooting.

**Comparison between CloudWatch and CloudTrail

AWS CloudTrail

CloudWatch: "What is happening on AWS?" and logging all the events for a particular service or application.

CloudTrail: "Who did what on AWS?" and the API calls to the service or resource.

CloudWatch is a monitoring service for AWS resources and applications. CloudTrail is a web service that records API activity in your AWS account. They are both useful monitoring tools in AWS.

CloudWatch offers free basic monitoring for your resources by default, such as EC2 instances, EBS volumes, and RDS DB instances. CloudTrail is also enabled by default when you create your AWS account.

With CloudWatch, you can collect and track metrics, collect and monitor log files, and set alarms. On the other hand, CloudTrail logs information on who made a request, the services used, the actions performed, parameters for the actions, and the response elements returned by the AWS service. CloudTrail Logs are then stored in an S3 bucket or a CloudWatch Logs log group that you specify.

Typically, CloudTrail delivers an event within 15 minutes of the API call. CloudWatch delivers metric data in 5 minutes periods for basic monitoring and 1 minute periods for detailed monitoring. The CloudWatch Logs Agent will send log data every five seconds by default.

You can enable detailed monitoring from your AWS resources to send metric data to CloudWatch more frequently, with an additional cost. CloudTrail helps you ensure compliance and regulatory standards.

CloudWatch Logs reports on application logs, while CloudTrail Logs provide you specific information on what occurred in your AWS account.

CloudWatch Events is a near real time stream of system events describing changes to your AWS resources. CloudTrail focuses more on AWS API calls made in your AWS account.

CloudTrail delivers one free copy of management event logs for each AWS region. Management events include management operations performed on resources in your AWS account, such as when a user logs in to your account. Logging data events are charged. Data events include resource operations performed on or within the resource itself, such as S3 object-level API activity or Lambda function execution activity.