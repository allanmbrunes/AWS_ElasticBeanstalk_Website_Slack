
# AWS_ElasticBeanstalk_Website

The setting up of an project with Autoscaling included the AWS CloudFront, AWS CloudWatch and AWS Elastic Beanstalk. A stress test was applied to test the Autoscaling of instances, when the CPU utilization trigger the max limit set up, the CloudWatch takes an action of alert trough SNS and Slack message directly to the DevOps team.  

## Table of Contents

- Static Website
- Python application 
- requeriments 
- DynamoDB
- CloudWatch reports integrated with Slack / SNS
- Running AWS commands from Slack to E2 instances 

## Use Cases

- Migration of static Websites or Application from on-premisses to AWS Cloud environment. 
- Cloud project focused on in a situation where the application has required a high demand of CPU and RDS.     

## Commands

On Bash file:
- touch /var/app/file
- sudo chown -R webapp:webapp /var/app/*

## Appendix

![Capture](https://user-images.githubusercontent.com/46986006/122605186-f6ef9680-d02b-11eb-87dc-d6151a2bbc4f.JPG)

![02](https://user-images.githubusercontent.com/46986006/122462464-79635200-cf69-11eb-994f-055d7352b9b3.jpg)

![01](https://user-images.githubusercontent.com/46986006/122461299-02798980-cf68-11eb-9825-68cd88b2b25b.JPG)


### Version 1.0
