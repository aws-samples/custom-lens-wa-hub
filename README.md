# AWS Custom Lens Hub
Provide JSON file template that demonstrate how to create customize Well-Architected reviews using Custom lenses.

![HitCount](https://hits.dwyl.com/aws-samples/custom-lens-wa-hub.svg?style=flat-square)
![GitHub](https://img.shields.io/github/license/aws-samples/custom-lens-wa-hub?style=flat-square)
![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/t/aws-samples/custom-lens-wa-hub?style=flat-square)
![GitHub Repo stars](https://img.shields.io/github/stars/aws-samples/custom-lens-wa-hub?style=flat-square)
![GitHub watchers](https://img.shields.io/github/watchers/aws-samples/custom-lens-wa-hub?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/aws-samples/custom-lens-wa-hub?style=flat-square)
![GitHub contributors](https://img.shields.io/github/contributors-anon/aws-samples/custom-lens-wa-hub?style=flat-square)

Note:
> This repository is maintained by internal volunteer, community members and domain service experts.

Disclaimer:
> All the sample artifacts (JSON) were contributed by domain expert for pilot preview purpose. All the pilot preview with custom lens have to be conducted by certified domain expert after customer enablement. If you are looking for official AWS Well-Architected Lenses material for specific topics, please go to  https://aws.amazon.com/architecture/well-architected/.

## :books: Background
[AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/) helps cloud architects build secure, high-performing, resilient, and efficient infrastructure for a variety of applications and workloads.

The AWS Well-Archtected Tool makes it easy to create [Custom Lenses](https://aws.amazon.com/blogs/mt/customize-well-architected-reviews-using-custom-lenses-and-the-aws-well-architected-tool/) by providing a json template that you can use. The template outlines how the lens content must be defined, and it controls how the lens is presented within the AWS WA Tool.

## :hammer_and_wrench: Setup
The quickest setup to run Customs Lens need setup includes:
- An [AWS account](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html)
- Proper [IAM User and Role](https://docs.aws.amazon.com/IAM/latest/UserGuide/id.html) to access the AWS Well-Architected Tool with the [WellArchitectedConsoleFullAccess](https://docs.aws.amazon.com/wellarchitected/latest/userguide/iam-auth-access.html) managed policy.

## :computer: Usage
This repository used DynamoDB as an example to show how to create Custom Lens in WA console from json template with several step as following:
1. [Prepare your custom lens WA template json file](/DynamoDB/README.md#prepare-your-custom-lens-WA-template-json-file)
2. [Navigate to the AWS WA Tool on the AWS console and create custom lens](/DynamoDB/README.md#navigate-to-the-aws-wa-tool-on-the-aws-console-and-create-custom-lens)
3. [Publish your custom lens and attached with version tag](/DynamoDB/README.md#publish-your-custom-lens-and-attached-with-version-tag)
4. [Review workloads using custom lenses](/DynamoDB/README.md#review-workloads-using-custom-lenses)

You can also reference the [Well-Architected Lab](https://wellarchitectedlabs.com/well-architectedtool/100_labs/100_custom_lenses_on_watool/) which provide step by step guideline.

## :clipboard: Repository
### Custom Lens for AWS Key Services
* [DynamoDB](/DynamoDB/)
* [DocumentDB](/DocumentDB/)
* [Glue](/Glue/)
* [OpenSearch](/OpenSearch/)
* [API Gateway and Lambda](/ApiGwLambda/)
* [ElastiCache](/ElastiCache/)
* [ECS](/Amazon-ECS-Lens/)

### Custom Lens for AWS Solutions
* [Streaming Media Lens](/Streaming-Media-Lens/)
* [SAP Lens](https://github.com/aws-samples/aws-sap-lens-well-architected/)
* [Operational Readiness Review](/ORR-Lens/)
* [FSI Governance Lens](/FSI-Governance-Lens/)
* [Container Build Lens](/Container-Build-Lens/)

## :bookmark: Whitepaper
Whitepaper to describe candidate new Custom Lenses, which you can reference as following:
* [Container Build Lens](https://docs.aws.amazon.com/wellarchitected/latest/container-build-lens/container-build-lens.html)
* [Amazon ECS Lens](https://docs.aws.amazon.com/AmazonECS/latest/bestpracticesguide/intro.html)
* [SAP Lens](https://docs.aws.amazon.com/wellarchitected/latest/sap-lens/sap-lens.html)
* [Serverless Applications Lens](https://docs.aws.amazon.com/wellarchitected/latest/serverless-applications-lens/welcome.html)
* [Hybrid Networking Lens](https://docs.aws.amazon.com/wellarchitected/latest/hybrid-networking-lens/hybrid-networking-lens.html)
* [Games Industry Lens](https://docs.aws.amazon.com/wellarchitected/latest/games-industry-lens/games-industry-lens.html)
* [Data Analytics Lens](https://docs.aws.amazon.com/wellarchitected/latest/analytics-lens/analytics-lens.html)
* [Machine Learning Lens](https://docs.aws.amazon.com/wellarchitected/latest/machine-learning-lens/machine-learning-lens.html)
* [Streaming Media Lens](https://docs.aws.amazon.com/wellarchitected/latest/streaming-media-lens/streaming-media-lens.html)
* [SaaS Lens](https://docs.aws.amazon.com/wellarchitected/latest/saas-lens/saas-lens.html)
* [Financial Services Industry Lens](https://docs.aws.amazon.com/wellarchitected/latest/financial-services-industry-lens/welcome.html)
* [IoT Lens](https://docs.aws.amazon.com/wellarchitected/latest/iot-lens/abstract-and-introduction.html)
* [IoT Lens Checklist](https://docs.aws.amazon.com/wellarchitected/latest/iot-lens-checklist/overview.html)
* [High Performance Computing Lens](https://docs.aws.amazon.com/wellarchitected/latest/high-performance-computing-lens/welcome.html)

## :balance_scale: License

This library is licensed under the MIT-0 License. For more details, please take a look at the [LICENSE](LICENSE) file.

## :handshake: Contributing
Please read our [contributing guidelines](CONTRIBUTING.md)
