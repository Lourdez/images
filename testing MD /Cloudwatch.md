# AWS Cloud-Watch
<img src ="https://github.com/Lourdez/images/blob/main/testing%20MD/1_3BAC2llwtKNf0K9zOWkf4w.png">

Amazon Web Services, Inc. (AWS) is a subsidiary of Amazon that provides on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered, pay-as-you-go basis. 

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

Full-stack observability at AWS includes AWS-native, Application Performance Monitoring (APM), and open-source solutions, giving you the ability to understand what is happening across your technology stack at any time. AWS observability lets you collect, correlate, aggregate, and analyze telemetry in your network, infrastructure, and applications in the cloud, hybrid, or on-premises environments so you can gain insights into the behavior, performance, and health of your system. These insights help you detect, investigate, and remediate problems faster; and coupled with artificial intelligence and machine learning, proactively react, predict, and prevent problems.

<img src ="https://github.com/Lourdez/images/blob/main/Observability-vs-Monitoring-vs-Telemetry%402x.png">

## Collect metrics, logs, and traces from Amazon EC2 instances and on-premises servers with the Cloud Watch agent
The unified Cloud Watch agent enables you to do the following:

+ Collect internal system-level metrics from Amazon EC2 instances across operating systems. The metrics can include in-guest metrics, in addition to the metrics for EC2 instances.
+ collect system-level metrics from on-premises servers. These can include servers in a hybrid environment as well as servers not managed by AWS.

+ Retrieve custom metrics from your applications or services using the StatsD and collectd protocols. StatsD is supported on both Linux servers and servers running Windows Server. collectd is supported only on Linux servers.

+ Collect logs from Amazon EC2 instances and on-premises servers, running either Linux or Windows Server.

+ Versions 1.300025.0 and later can collect traces from the AWS X-Ray Open Telemetry auto-instrumentation SDKs and send them to the X-Ray backend.


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

