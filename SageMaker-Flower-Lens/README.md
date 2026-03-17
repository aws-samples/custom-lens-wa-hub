# Federated Learning (Flower) on SageMaker AI Best Practice Lens
- [About](#about)
- [Prepare the json file](#prepare-the-json-file)
- [Create custom lens on Well-Architected Tool](#create-custom-lens-on-well-architected-tool)
- [Intended Audience](#intended-audience)
- [Contributing](#contributing)

## About 
Federated Learning (Flower) on SageMaker AI Best Practice Lens provides best practices for federated learning using flower framework on SageMaker AI includes 4 pillars of the AWS Well-Architected Framework: Operational Excellence, Security, Performance Efficiency, Cost Optimization.

## Prepare the json file
Prepare your custom lens Well-Architected template json file or just download the [provided recommended glue custom lens file](custom-lens-sagemaker-flower-v1.0.json).
```json
{
    "schemaVersion": "2021-11-01",
    "name": "Federated Learning (Flower) on SageMaker AI Best Practice Lens",
    "description": "Best practices for configuring Federated Learning (Flower) on SageMaker AI",
    "pillars": [
        {
            "id": "PERF",
            "name": "Performance Efficiency",
            "questions": [
                {
                    "id": "PERF1",
                    "title": "Are you aware of how data quality affects model performance in federated learning?",
                    "description": "Ensure balanced data distribution across nodes to prevent skewed training and improve model accuracy.",
                    "choices": [
                        {
                            "id": "PERF1_1",
                            "title": "Anomaly detection in AWS Glue Data Quality",
                            "helpfulResource": {
                                "displayText": "Anomaly detection employs machine learning to automatically identify unusual patterns in data",
                                "url": "https://docs.aws.amazon.com/glue/latest/dg/data-quality-anomaly-detection.html"
                            },
                            "improvementPlan": {
                                "displayText": "AWS Glue Data Quality helping to detect issues that traditional methods might miss.",
                                "url": "https://docs.aws.amazon.com/glue/latest/dg/data-quality-anomaly-detection.html"
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
![image 1](https://github.com/user-attachments/assets/18b0c4a2-5153-4cea-9fbb-c1e96debb775)

Upload the your custom lens Well-Architected template json template, and submit it.
![image 2](https://github.com/user-attachments/assets/d628ae41-9fb9-4e25-b9a7-da71ed4d670b)

And then you will find your Well-Architected custom lens in draft version.
![image 3](https://github.com/user-attachments/assets/b7e9a2f8-0c76-40a3-b085-44f9c9d46d26)

Publish your draft version and provide a version tag.
![image 4](https://github.com/user-attachments/assets/746fe002-fdbc-4219-87a9-68c056d57a60)

After your Well-Architected custom lens is published, you can define a workload in your AWS Well-Architected console.
![image 5](https://github.com/user-attachments/assets/a684a380-62d4-4fdf-973e-a66be22bf98c)

Input your workload information, and select the Well-Architected custom lens you just published. 
![image 6](https://github.com/user-attachments/assets/f04cde7e-e5dd-4adf-b4ff-e072029eb520)

Choose Continue reviewing for the just published Glue Well-Architected custom lens.
![image 7](https://github.com/user-attachments/assets/ef813acb-2ce3-4670-abf3-c57600763bf8)

Now you can review your Glue workload with Glue Well-Architected Custom Lens.
![image 8](https://github.com/user-attachments/assets/80b25de5-b803-4f58-a7d8-ad452020a7f1)

## Intended Audience

CTO, Technical Leader or technical owner for an Flower on Amazon SageMaker workload

## Contributing
- Ray Wang, Senior Solutions Architect, AWS

## Reviewers
- Sasi Kumar, Machine Learning Engineer, Flower Labs
- Dimitris Stripelis, Research Engineer, Flower Labs
