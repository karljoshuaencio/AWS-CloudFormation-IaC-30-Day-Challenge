# 30-Day AWS CloudFormation Challenge

### Week 1: Foundations (Basics)

1. Install and configure the AWS CLI. Write a CloudFormation YAML template that creates an **S3 bucket**.
2. Add a **bucket policy** that allows public read access.
3. Create an **EC2 instance** (t2.micro) with a key pair and security group.
4. Add a **user data script** to your EC2 instance that installs Apache and serves a “Hello World” page.
5. Create a **DynamoDB table** with a partition key.
6. Create an **IAM Role** and attach a policy for S3 read/write access.
7. Deploy an **SNS topic** and subscribe your email for notifications.

---

### Week 2: Integrating Services

8. Create an **SQS Queue** and output its URL.
9. Create a **Lambda function** using inline Python code that logs “Hello CloudFormation”.
10. Grant the Lambda permission to write logs to **CloudWatch Logs**.
11. Connect Lambda to the SQS queue as a trigger.
12. Create an **API Gateway REST API** with one GET endpoint integrated with your Lambda.
13. Create a **CloudWatch Alarm** for CPU usage on an EC2 instance.
14. Add **Outputs** and **Parameters** to your template for reusability.

---

### Week 3: Networking & Security

15. Create a **VPC** with 2 public subnets.
16. Add an **Internet Gateway** and route table for the VPC.
17. Launch an **EC2 instance** in one of the subnets.
18. Create a **Security Group** that only allows HTTP (port 80).
19. Add an **Elastic Load Balancer** in front of 2 EC2 instances.
20. Add an **Auto Scaling Group** with min=1, max=3 EC2 instances.
21. Create an **RDS MySQL database** in your VPC.

---

### Week 4: Advanced & Real‑World Scenarios

22. Use **Mappings** to define AMIs per region for your EC2.
23. Use **Conditions** to optionally create an S3 bucket only in `us-east-1`.
24. Create a **Nested Stack** (e.g., one stack for VPC, one for app resources).
25. Add **Stack Outputs** from one template to be used in another stack.
26. Create an **IAM User** with programmatic access and output the access key.
27. Use **AWS::CloudFormation::Init** metadata to configure software on an EC2 instance.
28. Add **stack policies** to prevent accidental deletion of critical resources.
29. Write a template that provisions a **serverless app** (API Gateway + Lambda + DynamoDB).
30. Final Project → Build a **3‑tier web app**:

* S3 static frontend
* API Gateway + Lambda backend
* DynamoDB or RDS database
* With IAM roles, alarms, and outputs
