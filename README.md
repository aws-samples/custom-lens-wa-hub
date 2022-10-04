![AWS Well-Archietcted](https://user-images.githubusercontent.com/17841922/192413820-2cb08389-5a74-4027-be34-d8ab0ec62872.png)
# AWS Well-Architected Custom Lens Examples
Example JSON file template that demonstrate how to create customize Well-Architected reviews using Custom lenses.

## :books: Background
[AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/) helps cloud architects build secure, high-performing, resilient, and efficient infrastructure for a variety of applications and workloads.

The AWS Well-Archtected Tool makes it easy to create [Custom Lenses](https://aws.amazon.com/blogs/mt/customize-well-architected-reviews-using-custom-lenses-and-the-aws-well-architected-tool/) by providing a json template that you can use. The template outlines how the lens content must be defined, and it controls how the lens is presented within the AWS WA Tool.

## :hammer_and_wrench: Setup
The quickest setup to run example notebooks includes:
- An [AWS account](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html)
- Proper [IAM User and Role](https://docs.aws.amazon.com/IAM/latest/UserGuide/id.html) to access the AWS Well-Architected Tool with the [WellArchitectedConsoleFullAccess](https://docs.aws.amazon.com/wellarchitected/latest/userguide/iam-auth-access.html) managed policy.

## :computer: Usage
This sample used DynamoDB as an example to show how to create Custom Lens in WA console from json template with several step as following:
1. [Prepare your custom lens WA template json file](/DynamoDB/README.md#prepare-your-custom-lens-WA-template-json-file)
2. [Navigate to the AWS WA Tool on the AWS console and create custom lens](/DynamoDB/README.md#navigate-to-the-aws-wa-tool-on-the-aws-console-and-create-custom-lens)
3. [Publish your custom lens and attached with version tag](/DynamoDB/README.md#publish-your-custom-lens-and-attached-with-version-tag)
4. [Review workloads using custom lenses](/DynamoDB/README.md#review-workloads-using-custom-lenses)

You can also reference the [Well-Architected Lab](https://wellarchitectedlabs.com/well-architectedtool/100_labs/100_custom_lenses_on_watool/) which provide step by step guideline.

## :notebook: Examples
* [DynamoDB](/DynamoDB)
* [DocumentDB](/DocumentDB)
* [Operational Readiness Review](/ORR-Lens/)

## :balance_scale: License

This library is licensed under the MIT-0 License. For more details, please take a look at the [LICENSE](LICENSE.txt) file.

## :handshake: Contributing
Please read our [contributing guidelines](CONTRIBUTING.md)