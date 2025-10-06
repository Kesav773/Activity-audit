## EX - 4 Auditing Cloud Activity Using AWS CloudTrail
## Name : S.Harika
## Reg No : 212224240155

## Aim
To enable and analyze AWS CloudTrail logs to audit user and resource activities in a cloud environment.

## Requirements
1.AWS Console access

2.CloudTrail service enabled

3.S3 bucket (for storing logs)

4.IAM permissions to view audit logs

## Procedure

## Step 1: Enable CloudTrail

Go to CloudTrail from AWS Console Click Trails > Create trail Name: CloudAuditTrail Apply trail to all regions Log events:

~ Management events: Read & Write

~ Data events: S3, Lambda (optional) Create or select an S3 bucket for log storage Enable CloudWatch Logs integration (optional)

## Step 2: Review Event History

Go to Event history Filter events by:

~ Username (IAM role or user)

~ Event name (e.g., CreateBucket, TerminateInstances)

~ Date/Time

~ Resource type (e.g., S3, EC2)

## Step 3: Download or Export Logs

Use the Download CSV option to export logs Analyze logs in Excel/Sheets for reporting

## Output:

<img width="818" height="663" alt="Screenshot 2025-10-06 102524" src="https://github.com/user-attachments/assets/58f77b54-e5d8-42ee-8e13-c712eb51f7f5" />


## Result
All AWS user activities, including volume creation, deletion, and permission changes, were successfully audited using CloudTrail.

