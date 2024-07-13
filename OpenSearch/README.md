# AWS OpenSearch Well-Architected Custom Lens

- [About](#about)
- [Prepare the json file](#prepare-the-json-file)
- [Create custom lens on Well-Architected Tool](#create-custom-lens-on-well-architected-tool)
- [Intended Audience](#intended-audience)
- [Contributing](#contributing)

## About

AWS OpenSearch Well-Architected Custom Lens specifies best practices in Operational Excellence, Security, Performance Efficiency, Reliability and Cost Optimization pillars. The best practices are designed for OpenSearch workload. 

## Prepare the json file
Prepare your custom lens Well-Architected template json file or just download the [provided recommended glue custom lens file](custom-lens-OpenSearch.json).
```json
{
    "schemaVersion": "2021-11-01",
    "name": "OpenSearch Best Practice - For WA Custom Lens",
    "description": "Best practices for configuring OpenSearch",
    "pillars": [
        {
            "id": "AOSSOPS",
            "name": "Operational Excellence",
            "questions": [
                {
                    "id": "aossops1",
                    "title": "How do you monitor and analyze your Amazon OpenSearch domains performance?",
                    "description": "Amazon OpenSearch Service emits performance metrics to Amazon CloudWatch. Regularly review your cluster and instance metrics and configure recommended CloudWatch alarms based on your workload performance.",
                    "helpfulResource": {
                        "displayText": "Amazon OpenSearch Service exposes OpenSearch error logs, search slow logs, indexing slow logs, and audit logs in Amazon CloudWatch Logs. You can enable log publishing through AWS Console, CLI, SDK, or CloudFormation.",
                        "url": "https://docs.aws.amazon.com/opensearch-service/latest/developerguide/createdomain-configure-slow-logs.html"
                    },
                    "choices": [
                        {
                            "id": "aossops1_1",
                            "title": "Setup the recommended CloudWatch alarms for your Amazon OpenSearch Service.",
                            "helpfulResource": {
                                "displayText": "Understand what recommended CloudWatch alarms are for your Amazon OpenSearch Service.",
                                "url": "https://docs.aws.amazon.com/opensearch-service/latest/developerguide/cloudwatch-alarms.html"
                            },
                            "improvementPlan": {
                                "displayText": "Setup CloudWatch alarms for Amazon OpenSearch Service.",
                                "url": "https://docs.aws.amazon.com/opensearch-service/latest/developerguide/cloudwatch-alarms.html"
                            }
                        }
                    ]
                }
             ]
      }
   ]
}

```

## Create custom lens on Well-Architected Tool
After you prepare your custom lens Well-Architected template json file, you can navigate to the AWS Well-Architected Tool on the AWS console and create custom lens.
![image 1](https://user-images.githubusercontent.com/17841922/175503831-cf89ff5e-8c6e-42c7-b796-3ff91e9d8470.png)

Upload the your custom lens Well-Architected template json template, and submit it.
![image 2](https://user-images.githubusercontent.com/17841922/175503996-9b734d2c-8220-4efb-b5d2-f4ad77ad0ff4.png)

And then you will find your Well-Architected custom lens in draft version.
![image 3](https://github.com/user-attachments/assets/28a0a3c0-2bd0-4d2f-b652-bc7ce3e04d9e)

Publish your draft version and provide a version tag.
![image 4](https://github.com/user-attachments/assets/177e88d4-d05e-40d0-9aa9-cafa6d2b317f)

After your Well-Architected custom lens is published, you can define a workload in your AWS Well-Architected console.
![image 5](https://user-images.githubusercontent.com/17841922/175505004-1f9026f7-c3f8-415d-92a1-747ab68f6610.png)

Input your workload information, and select the Well-Architected custom lens you just published. 
![image 6](https://github.com/user-attachments/assets/065eeac4-9030-4bec-9463-be2ed81e8a35)

Choose Continue reviewing for the just published OpenSearch Well-Architected custom lens.
![image 7](https://github.com/user-attachments/assets/4cc84630-ac7b-4bad-b602-de9c804d1a54)

Now you can review your OpenSearch workload with OpenSearch Well-Architected Custom Lens.
![image 8](https://github.com/user-attachments/assets/788a66ed-56be-4f64-982e-108588a0d2b5)

## Intended Audience

CTO, Technical Leader or technical owner for an AWS OpenSearch workload

## Contributing
- Shih-Yong Wang, Manager, Solutions Architect, AWS
- [Ray Wang](mailto:hsiawang@amazon.com), Solutions Architect, AWS
- Ankush Agarwal, OpenSearch SME, APAC, AWS
