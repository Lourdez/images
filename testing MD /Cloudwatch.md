# AWS Cloud-Watch
<img src ="https://github.com/Lourdez/images/blob/main/testing%20MD/1_3BAC2llwtKNf0K9zOWkf4w.png">

Amazon CloudWatch is a component of Amazon Web Services that provides monitoring for AWS resources and the customer applications running on the Amazon infrastructure.

## What is cloud-Watch

<img src ="https://github.com/Lourdez/images/blob/main/What-is-AWS-CloudWatch.png">

**Amazon Cloud Watch** monitors your Amazon Web Services (AWS) resources and the applications you run on AWS in real time. You can use Cloud Watch to collect and track metrics, which are variables you can measure for your resources and applications


## What It Does
It Collect, access, and analyze your resource and application data using powerful visualization tools.

<img src ="https://github.com/Lourdez/images/blob/main/Product-Page-Diagram_Amazon-CloudWatch.095eb618193be7422d2d34e3abd5fdf178b6c0e2.png">

Improve operational performance using alarms and automated actions set to activate at predetermined thresholds.

Seamlessly integrate with more than 70 AWS services for simplified monitoring and scalability.

Troubleshoot operational problems with actionable insights derived from logs and metrics in your Cloud Watch dashboards.

## Use Cases
### Monitor application performance
Visualize performance data, create alarms, and correlate data to understand and resolve the root cause of performance issues in your AWS resources.

<img src ="https://github.com/Lourdez/images/blob/main/monitor.png">

### Perform root cause analysis
Analyze metrics, logs, logs analytics, and user requests to speed up debugging and reduce overall mean time to resolution.

<img src ="https://github.com/Lourdez/images/blob/main/analyse.png">

### Optimize resources proactively
Automate resource planning and lower costs by setting actions to occur when thresholds are met based on your specifications or machine learning models.

<img src ="https://github.com/Lourdez/images/blob/main/collect.png">


## Monitoring and Observability and Telemetry

+ Full-stack observability at AWS includes AWS-native, Application Performance Monitoring (APM), and open-source solutions
+ Giving you the ability to understand what is happening across your technology stack at any time. 
+ AWS observability lets you collect, correlate, aggregate, and analyze telemetry in your network, infrastructure, and applications in the cloud, hybrid, or on-premises environments 
+ so you can gain insights into the behavior, performance, and health of your system. These insights help you detect, investigate, and remediate problems faster; and coupled with artificial intelligence and machine learning, proactively react, predict, and prevent problems.

<img src ="https://github.com/Lourdez/images/blob/main/Observability-vs-Monitoring-vs-Telemetry%402x.png">

## Collect metrics, logs, and traces from Amazon EC2 instances and on-premises servers with the Cloud Watch agent
The unified Cloud Watch agent enables you to do the following:

+ Collect internal system-level metrics from Amazon EC2 instances across operating systems. The metrics can include in-guest metrics, in addition to the metrics for EC2 instances.
+ collect system-level metrics from on-premises servers. These can include servers in a hybrid environment as well as servers not managed by AWS.

+ Retrieve custom metrics from your applications or services using the StatsD and collectd protocols. StatsD is supported on both Linux servers and servers running Windows Server. collectd is supported only on Linux servers.

+ Collect logs from Amazon EC2 instances and on-premises servers, running either Linux or Windows Server.

+ Versions 1.300025.0 and later can collect traces from the AWS X-Ray Open Telemetry auto-instrumentation SDKs and send them to the X-Ray backend.

## Monitor Your Entire AWS Environment More Effectively

<img src ="https://github.com/Lourdez/images/blob/main/testing%20MD/cw-dashboard.jpg">

+ See inside any stack, any app, anywhere at any scale with Datadog’s 650+ vendor-backed integrations
+ Get started in seconds with auto-discovery for AWS services such as S3, EBS, ELB, and ElastiCache, among many others
+ Visualize the performance of all your cloud services, on-premise servers, containers, and databases in real time with customizable, drag-and-drop dashboards


## Resolve AWS Performance Issues Faster

<img src ="https://github.com/Lourdez/images/blob/main/testing%20MD/2019-06-20%2012_11_54-Cloud%20Insights%20(1)-2.webp">

+ Gain full visibility into your AWS application code performance with end-to-end tracing, full latency breakdowns, and flame graphs showcasing request-level details
+ Identify critical issues quickly with real-time service maps, AI-powered synthetic monitors, and alerts on performance issues
+ Easily test hypotheses by overlaying events onto time-synchronized graphs
+ Reduce mean time to resolution with infrastructure metrics, distributed request traces, and logs all within one platform

## Receive AWS Alerts Only for the Issues That Matter and Eliminate False-Positives

<img src ="https://github.com/Lourdez/images/blob/main/testing%20MD/Example-Picture-1-2.png">

+ Set up alerts for anomalies and outliers that account for daily, weekly, and seasonal fluctuations
+ Proactively prevent outages and errors by alerting on metric forecasts
+ Create composite alerts, based on boolean logic, to reduce your time spent responding to spurious alerts
+ Automatically detect unanticipated outliers, anomalies, and errors with Watchdog

## AWS Cloud-Watch All Feathers in Simple 

<img src ="https://github.com/Lourdez/images/blob/main/testing%20MD/security-4_steps_toward_cloud_sec-f.png">

### Collect 

+ Collect data through logs and metrices

### Monitors

+ Data reported Through Dashboard and virtualization
  
### Act

+ Automate responses for specific metrices
  
### Analyze 

+ Advanced metrices and correlation

### CloudWatch Logs. 
+ This service enables users to collect and store logs for vended services for customers, logs for specific AWS services such as AWS CloudTrail, AWS Lambda, Amazon API Gateway, Amazon Simple Notification Service, or for proprietary applications and on-premises resources.
+  CloudWatch Logs Insights can provide quick queries and visualization of log data.
  
### Metrics collection.
+ Users can collect default metrics from more than 70 distributed AWS applications and view them in one place. They also can collect metrics and customize logs from their own applications or on-premises resources.
  
### Container Insights.
+ This feature collects, aggregates and monitors metrics and logs for containerized applications and microservices. It can also troubleshoot Amazon Elastic Kubernetes Service and Amazon Container Orchestration Service. 
### CloudWatch Lambda Insights.
+This service collects, aggregates and monitors AWS Lambda logs and performance metrics from each container, including CPU, memory and disk information.   

### Contributor Insights.
+ This feature provides a view of the top contributors influencing system performance, such as API calls, applications or customer accounts.
Unified view.
+ This feature enables users to create dashboard views for selected applications, graphs and other visualized cloud data.
### Composite alarms.
+ This function unifies alarms for different issues affected by the same application into a single notification. This can help root-cause diagnosis.
### High resolution alarms. 
+ Users can set thresholds for specific metrics that trigger alarm actions, such as shutting down unused instances.
### Correlation.
+ CloudWatch can correlate specific patterns in logs with metrics to diagnose a root cause.
### Application Insights for .NET and SQL Server.
+ This feature provides easy monitoring for .NET and SQL Server applications, with automated dashboards and smart metrics.
### Anomaly Detection.
+ Machine learning algorithms can detect abnormal activity in AWS systems.
### ServiceLens.
+ This service monitors the performance, health and availability of applications and dependencies to reduce bottlenecks, recognize affected users and diagnose root causes.
### Synthetics.
+ This facility monitors application endpoints and alerts the user to errors and abnormal infrastructure issues.
### Metric Streams.
+ This feature enables users to create near real-time metric streams to other applications, such as Amazon S3, or share them with third-party service providers.
### Auto Scaling.
+ This feature automates capacity and resource planning.
### CloudWatch Events.
+ This service provides a near real-time stream of system events and automates responses to operational changes.
### Log analytics.
+ Advanced analytics are available for the information in CloudWatch Logs, without provisioning additional servers or the need for extra software. Queries can be exported to dashboards.
### Integration with AWS Identity and Access Management.
+ This facility provides a management console to control which users and applications have access to CloudWatch data and resources.


## How To Create Cloud Watch
1. Login Into [Amazon Management Console](https://signin.aws.amazon.com/signin?redirect_uri=https%3A%2F%2Fconsole.aws.amazon.com%2Fconsole%2Fhome%3FhashArgs%3D%2523%26isauthcode%3Dtrue%26nc2%3Dh_ct%26src%3Dheader-signin%26state%3DhashArgsFromTB_eu-north-1_67569bb514fd7334&client_id=arn%3Aaws%3Asignin%3A%3A%3Aconsole%2Fcanvas&forceMobileApp=0&code_challenge=O-19Kk8URbYdcSReZJtf-59QKpGm4u3dALUVrpv1Fj4&code_challenge_method=SHA-256)

<img src ="https://github.com/Lourdez/images/blob/main/Screenshot%20(127).png">

2. Search for cloud watch in the search bar and Click on First result  to get into Cloud watch Page

<img src ="https://github.com/Lourdez/images/blob/main/Cloud%20watch.png">

3. Under Dash Board Session , click create dashboard 

<img src ="https://github.com/Lourdez/images/blob/main/Screenshot%20(134).png">

4. Give a name to the dash board and click next 

<img src ="https://github.com/Lourdez/images/blob/main/Screenshot%20(133).png">

5.Select the metrics or logs to monitoring and select the EC2 / S3 / ELB / load Balancer  

<img src ="https://github.com/Lourdez/images/blob/main/Screenshot%20(135).png">


## Cloud Watch Pricing

### Free tier
You can get started with Amazon Cloud Watch for free. Most AWS Services (EC2, S3, Kinesis, etc.) send metrics automatically for free to Cloud Watch. Many applications should be able to operate within these free tier limits.

|  |  |
| ------ | -----------: |
| Metrics | Basic Monitoring Metrics (Metrics sent from AWS Services by default)
| Dashboard | 3 Custom Dashboards referencing up to 50 metrics each per month. Additionally, all Automatic Dashboards are free.
| Alarms| 10 Alarm metrics (only applicable to Standard resolution alarms that list metrics directly and don’t use a Metrics Insights query)
| Logs | 5 GB Data (ingestion, archive storage, and data scanned by Logs Insights queries)1,800 minutes of Live Tail usage per month (approximately an hour per day)


To know more about Cloud Watch [Click Here](https://aws.amazon.com/cloudwatch/)

