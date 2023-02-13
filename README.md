# AWS Custom Lens Hub
Provide JSON file template that demonstrate how to create customize Well-Architected reviews using Custom lenses.

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
* [DynamoDB](/DynamoDB)
* [DocumentDB](/DocumentDB)
* [Glue](/Glue)
* [OpenSearch](/OpenSearch)

### Custom Lens for Operation
* [Operational Readiness Review](/ORR-Lens/)

## :balance_scale: License

This library is licensed under the MIT-0 License. For more details, please take a look at the [LICENSE](LICENSE) file.

## :handshake: Contributing
Please read our [contributing guidelines](CONTRIBUTING.md)
