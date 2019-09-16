# AWS Security Workshop Series
In this series, we will introduce how to get started with Amazon Sercurity Services such as [Amazon WAF](https://aws.amazon.com/tw/waf/), [Amazon GuardDuty](https://aws.amazon.com/tw/guardduty/), [Amazon Inspector](https://aws.amazon.com/tw/inspector/), [Amazon KMS](https://aws.amazon.com/tw/kms/) and how to integrate these services with your infrastructure.  

## Prerequisite
* AWS Account
* Make sure the region is **US East (N. Virginia)**, which its short name is **us-east-1**.

## Lab Map

1. Build Environment
    - [Build Network environment and Web application](/01Buildenvironment/01BuildNetworkenvironmentandWebapplication/README.md)
    - [Use AWS Inspector inspect EC2](/01Buildenvironment/02UseAWSInspectorinspectEC2/README.md)
2. Implement WAF- Web application Firewall
    - [Build WAF with cloudformation and Test](/02BuildWAFwithcloudformationandTest/README.md)
3. GuardDuty to SNS and EBS encryption
    - [GuardDuty to SNS](/03GuardDutytoSNSandEBSencryption/01GuardDutytoSNS/README.md)
    - [EBS Encryption with AWS KMS](/03GuardDutytoSNSandEBSencryption/02EBSencryption/README.md)