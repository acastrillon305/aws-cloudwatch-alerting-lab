# Architecture Overview

This lab represents a basic AWS alerting workflow.

## Flow

1. EC2 instance emits metrics to CloudWatch
2. CloudWatch Alarm evaluates the metric threshold
3. Alarm changes state when the threshold is breached
4. SNS topic sends notification to the operations team

## Example Alert

High CPU utilization on an EC2 instance triggers an alert when average CPU usage exceeds 80% for two evaluation periods.

## Why This Matters

Monitoring and alerting help cloud teams detect issues early, reduce downtime, and improve incident response.
