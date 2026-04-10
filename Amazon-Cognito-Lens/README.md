# Amazon Cognito Best Practice Lens for Well-Architected

The Amazon Cognito Best Practice Lens helps you evaluate your Cognito workloads against AWS Well-Architected best practices. This lens provides guidance on designing, securing, and operating Amazon Cognito User Pools and Identity Pools across five Well-Architected pillars.

## Overview

Amazon Cognito provides authentication, authorization, and user management for web and mobile applications. With User Pools, you can add user sign-up and sign-in functionality, while Identity Pools provide AWS credentials to access AWS resources. This lens helps you implement Cognito following AWS best practices to build secure, reliable, efficient, and cost-effective authentication systems.

## Coverage

This lens covers best practices for:

- **User Pools**: User directories, authentication flows, MFA, passwordless authentication, password policies, threat protection, Lambda triggers, and federated identity providers
- **Identity Pools**: IAM role configuration, authenticated and unauthenticated access, role-based and attribute-based access control (RBAC/ABAC), and temporary credential management
- **Integration Patterns**: API Gateway integration, app client configuration, OAuth flows, token management, and custom authentication flows
- **Operational Aspects**: Infrastructure as Code, monitoring, logging, user migration, incident response, and disaster recovery

## Five Pillars

### Security (11 questions)

| ID       | Question                                                        |
| -------- | --------------------------------------------------------------- |
| CGNSEC1  | How do you enforce strong authentication for your users?        |
| CGNSEC2  | How do you use threat protection to defend against attacks?     |
| CGNSEC3  | How do you secure Identity Pool IAM roles with least privilege? |
| CGNSEC4  | How do you protect data at rest and in transit?                 |
| CGNSEC5  | How do you manage token security and lifecycle?                 |
| CGNSEC6  | How do you secure federated identity provider integration?      |
| CGNSEC7  | How do you implement compliance and auditing requirements?      |
| CGNSEC8  | How do you manage user groups and role-based access control?    |
| CGNSEC9  | How do you protect sensitive user attributes?                   |
| CGNSEC10 | How do you protect Cognito endpoints from abuse?                |
| CGNSEC11 | How do you secure Lambda triggers?                              |

### Reliability (8 questions)

| ID      | Question                                                                     |
| ------- | ---------------------------------------------------------------------------- |
| CGNREL1 | How do you design for multi-region resilience?                               |
| CGNREL2 | How do you monitor service quotas, handle throttling, and design for limits? |
| CGNREL3 | How do you ensure Lambda trigger reliability and resilience?                 |
| CGNREL4 | How do you design account recovery flows for reliability?                    |
| CGNREL5 | How do you handle dependency failures?                                       |
| CGNREL6 | How do you implement graceful degradation?                                   |
| CGNREL7 | How do you test reliability of authentication flows?                         |
| CGNREL8 | How do you monitor Cognito service health and performance?                   |

### Operational Excellence (11 questions)

| ID       | Question                                                       |
| -------- | -------------------------------------------------------------- |
| CGNOPS1  | How do you manage Cognito resources as Infrastructure as Code? |
| CGNOPS2  | How do you monitor and log Cognito events?                     |
| CGNOPS3  | How do you plan and execute user migration?                    |
| CGNOPS4  | How do you set up alerting and notifications?                  |
| CGNOPS5  | How do you manage Lambda triggers operationally?               |
| CGNOPS6  | How do you manage change and configuration drift?              |
| CGNOPS7  | How do you maintain operational documentation?                 |
| CGNOPS8  | How do you implement testing strategies?                       |
| CGNOPS9  | How do you manage multiple environments?                       |
| CGNOPS10 | How do you handle Cognito service updates?                     |
| CGNOPS11 | How do you perform incident response and post-mortems?         |

### Performance Efficiency (6 questions)

| ID       | Question                                                     |
| -------- | ------------------------------------------------------------ |
| CGNPERF1 | How do you optimize region selection for latency?            |
| CGNPERF2 | How do you manage token caching and lifecycle?               |
| CGNPERF3 | How do you optimize Lambda trigger performance?              |
| CGNPERF4 | How do you design efficient custom authentication flows?     |
| CGNPERF5 | How do you optimize API usage and large-scale operations?    |
| CGNPERF6 | How do you monitor and benchmark authentication performance? |

### Cost Optimization (6 questions)

| ID       | Question                                                         |
| -------- | ---------------------------------------------------------------- |
| CGNCOST1 | How do you monitor and forecast Cognito costs?                   |
| CGNCOST2 | How do you choose the right feature plan?                        |
| CGNCOST3 | How do you optimize SMS and email delivery costs?                |
| CGNCOST4 | How do you optimize Lambda trigger costs?                        |
| CGNCOST5 | How do you optimize M2M authorization costs?                     |
| CGNCOST6 | How do you leverage free tier and understand pricing dimensions? |

## Usage Instructions

### 1. Prepare your custom lens JSON file

Download the [custom-lens-cognito-v1.0.json](custom-lens-cognito-v1.0.json) file from this directory.

### 2. Navigate to the AWS Well-Architected Tool

1. Open the [AWS Well-Architected Tool console](https://console.aws.amazon.com/wellarchitected/)
2. In the left navigation pane, choose **Custom lenses**
3. Choose **Create custom lens**

### 3. Upload and create the custom lens

1. Choose **Upload JSON file**
2. Select the `custom-lens-cognito-v1.0.json` file
3. Review the lens details
4. Choose **Submit**

### 4. Publish your custom lens

1. After the lens is created, it will be in **Draft** status
2. Select the lens and choose **Publish**
3. Provide a version number (e.g., `1.0`)
4. Add release notes if desired
5. Choose **Publish**

### 5. Review workloads using the custom lens

1. Navigate to **Workloads** in the Well-Architected Tool
2. Create a new workload or select an existing one
3. Choose **Edit** and select the **Amazon Cognito Best Practice Lens** under custom lenses
4. Save and begin your review

## Benefits

Using this lens helps you:

- **Improve Security**: Implement MFA, threat protection, passwordless authentication, and least privilege access control
- **Enhance Reliability**: Design for multi-region resilience, handle dependency failures, and implement graceful degradation
- **Optimize Operations**: Manage Cognito as code, implement comprehensive monitoring, and execute smooth user migrations
- **Boost Performance**: Optimize latency, token caching, Lambda trigger performance, and API usage patterns
- **Reduce Costs**: Choose the right feature plan, optimize SMS/email delivery, and cache M2M tokens

## Contributings

- Jeremy Lin, Solutions Architect, AWS

## Reviewer

- Yungang Wu, Sr. Cloud Support Eng, AWS
