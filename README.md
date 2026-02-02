# Cloud Monitoring and Alert System using AWS

## 📌 Project Overview
This project demonstrates a cloud-based monitoring and alert system built using AWS services.
It monitors EC2 CPU utilization and sends email alerts when usage exceeds a defined threshold.

## 🛠️ AWS Services Used
- Amazon EC2
- Amazon CloudWatch
- Amazon SNS
- IAM

## 🏗️ Architecture
EC2 → CloudWatch Metrics → CloudWatch Alarm → SNS → Email Notification

## ⚙️ Implementation Steps
1. Created an EC2 instance using Amazon Linux 2
2. Enabled monitoring using Amazon CloudWatch
3. Created an SNS topic and email subscription
4. Configured CloudWatch alarm for high CPU usage
5. Tested alert by generating CPU load

## 🧪 Testing
High CPU usage was simulated using Linux commands.
Email alerts were successfully received when CPU crossed the threshold.

## ✅ Outcome
- Real-time monitoring of EC2 instance
- Automated alert notifications
- Improved system reliability

## 📚 Learning
This project helped me understand AWS monitoring, alerting, and cloud fundamentals.

