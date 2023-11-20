# Infrastructure Monitoring and Alerting with AWS CloudWatch

## Step Configure
+ Create an AWS EC2 instance and install a sample application that generates logs:
+ Configure CloudWatch to monitor the logs and trigger alerts based on predefined metrics:

## Steps

+ Login to AWS console and Go to EC2 instance page

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/2a81a580-9434-4202-8565-f4b0b4682400)

+ Launch a ec2 instance for monitoring

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/57e91552-6d31-4429-9400-8f83c6c6af71)

+ Connect to the instance and install Apache using “apt install apache2”

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/572e8484-567f-486e-9d91-a0e6f3c72b9a)

+ Creating a role so that cloud watch can interact with ec2.
+ Open IAM Service in AWS console
 
![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/36d373c3-7c7a-44f1-972b-aac313d1cdbc)

+ Create a new role but clicking new role

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/d1aa16d0-717c-4101-8cfc-21e9f2ad7a56)

+ Under use case select EC2 

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/50bdf6a1-7ea4-49a5-9c6f-ea5f27f11804)

+ Select “cloudwatchserverpolicy” to add policy.

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/0a87ab6c-32b4-4e93-8895-6ab50835176f)

+ Give the role a name and click create. 

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/42b5c526-9ccd-435a-8b0f-3b4d6f84eb6c)

+ Select the instance and attach the role to ec2 instance. 

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/40b823bb-6b29-40b3-83a8-697ea305cb6b)

+ Select the IAM role for Ec2 instance which is cloud watch.

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/814870a6-77cb-4094-a430-3c15c981bab1)

+ Go to SNS -Simple Notification service. 

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/b0837398-16b3-4a76-80ab-c98861ea773d)

+ Give a name for a topic and click next step. 
+ Go to IAM and Give SNS access.

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/e867a810-22d8-4c2a-a670-db77d0dd502c)

This will Allow the Service to sync with other services.

+ Create a subscription and give email , a mail is sent to the inbox for confirmation of Subscription to the given emai

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/7d895801-7e24-42b9-8118-5ec224a640b7)

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/d829f18c-48a5-49cd-86f7-822fcb436584)

+ Once confirmed from inbox , the status will be updated to confirmed .

+ Copy the running instance ID from EC2 instance and paste it in CloudWatch metrices session.

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/cf980e2d-a0dc-4d20-9686-bdff0aad779a)

In Cloud watch EC2 has 17 metrices for monitoring 
They are. 
1)	Network packets Out.
2)	Network Packets In.
3)	Disk write Ops.
4)	Network in.
5)	Disk write Bytes.
6)	Disk Read Bytes.
7)	Network Out.
8)	CPU utilization.
9)	Disk read Ops.
10)	CPU surplus Credits Charged.
11)	CPU Credit usage.
12)	CPU credit Balance.
13)	CPU Surplus Credit balance.
14)	Status Check Failed Instance.
15)	Status Check Failed system.
16)	Status checks Failed.
17)	Meta Data no Token.

+ Select the Metrices and select Graph

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/e3206ca7-4942-43d0-aa84-a0e96cc88b5c)

+ Select the Bell symbol in the metrices, it will go to alarm session. 

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/1aa7c306-9ec2-439a-937a-95bc234b8189)

+ Select the alert type.

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/4bf822fd-fcbd-4b1a-808e-25e9f326d40d)

+ Click next and create an alarm. 

![image](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/7f9fb69c-c861-47c7-9bce-27b6f6ef2465)

+ A Email will sent to the subscribed email ID 

![EMail](https://github.com/zen-class/zen-class-devops-documentation/assets/54675124/e27bf715-82e0-45bf-93cc-c0ef878cc367)
