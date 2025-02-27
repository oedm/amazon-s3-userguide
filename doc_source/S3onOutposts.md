# Using Amazon S3 on Outposts<a name="S3onOutposts"></a>

AWS Outposts is a fully managed service that extends AWS infrastructure, services, APIs, and tools to your premises\. By providing local access to AWS managed infrastructure, AWS Outposts helps you build and run applications on\-premises using the same programming interfaces as in AWS Regions, while using local compute and storage resources for lower latency and local data processing needs\. For more information, see [What is AWS Outposts?](https://docs.aws.amazon.com/outposts/latest/userguide/what-is-outposts.htm) in the *AWS Outposts User Guide*\.

With Amazon S3 on Outposts, you can create S3 buckets on your AWS Outposts and easily store and retrieve objects on premises for applications that require local data access, local data processing, and data residency\. S3 on Outposts provides a new storage class, `OUTPOSTS`, which uses the S3 APIs, and is designed to store data durably and redundantly across multiple devices and servers on your AWS Outposts\. You communicate with your Outposts bucket using an access point and endpoint connection over a virtual private cloud \(VPC\)\. You can use the same APIs and features on Outposts buckets as you do on Amazon S3, including access policies, encryption, and tagging\. You can use S3 on Outposts through the AWS Management Console, AWS CLI, AWS SDKs, or REST API\.

You can use S3 on Outposts to deploy object storage on\-premises that is monitored, patched, and updated by AWS\. With S3 on Outposts you can reduce the time, resources, operational risk, and maintenance downtime required for managing on\-premises storage\. You can process and securely store data locally in your on\-premises environment and transfer data to Amazon S3 in an AWS Region for further processing or archival\. S3 on Outposts enables you to meet data residency or regulatory requirements by keeping data on an Outpost on\-premises within a country, state/province, or location where there is not an AWS Region today\.

For on\-premises applications that require high\-throughput local processing, S3 on Outposts provides on\-premises object storage to minimize data transfers and buffer from network variations, while providing you the ability to easily transfer data between Outposts and AWS Regions\. S3 on Outposts is integrated with AWS DataSync\. So you can automate transferring data between your Outposts and AWS Regions, choosing what to transfer, when to transfer, and how much network bandwidth to use\. For more information about transferring data from your S3 on Outposts buckets using DataSync, see [Getting Started with AWS DataSync](https://docs.aws.amazon.com/datasync/latest/userguide/getting-started.html) in the *AWS DataSync User Guide*\.

**Topics**
+ [Getting started with Amazon S3 on Outposts](S3OutpostsGS.md)
+ [Amazon S3 on Outposts restrictions and limitations](S3OnOutpostsRestrictionsLimitations.md)
+ [Using AWS Identity and Access Management with Amazon S3 on Outposts](S3OutpostsIAM.md)
+ [Accessing Amazon S3 on Outposts](WorkingWithS3Outposts.md)
+ [Sharing Amazon S3 on Outposts by using AWS Resource Access Manager](outposts-sharing-with-ram.md)
+ [Monitoring Amazon S3 on Outposts](MonitoringS3Outposts.md)
+ [Managing Amazon S3 on Outposts buckets and objects](S3OutpostsExamples.md)