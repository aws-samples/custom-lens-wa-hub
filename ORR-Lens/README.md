# Operational Readiness Review (ORR) Lens

Amazon Web Services (AWS) created the Operational Readiness Review (ORR) to distill the learnings from AWS operational incidents into curated questions with best practice guidance. Refer to the [ORR Whitepaper](https://docs.aws.amazon.com/wellarchitected/latest/operational-readiness-reviews/). Within the Whitepaper [Appendix B](https://docs.aws.amazon.com/wellarchitected/latest/operational-readiness-reviews/appendix-b-example-orr-questions.html) provides example ORR questions. The following ORR lens models those questions as a template to get started quickly building an ORR practice using WA custom lens as the tool. 


# Customize Well-Architected Reviews using Custom Lenses Sample Questionnaire

The AWS Well-Architected Tool makes it easy to create custom lenses by providing a json template that you can use. The template outlines how the lens content must be defined, and it controls how the lens is presented within the AWS WA Tool. This sample used ORR questions as an example from the ORR Whitepaper (see above) to show how to create Custom Lens in WA console from json template with the following several steps:
1. [Prepare your custom lens WA template json file](#prepare-your-custom-lens-WA-template-json-file)
2. [Navigate to the AWS WA Tool on the AWS console and create custom lens](#navigate-to-the-aws-wa-tool-on-the-aws-console-and-create-custom-lens)
3. [Publish your custom lens and attached with version tag](#publish-your-custom-lens-and-attached-with-version-tag)
4. [Review workloads using custom lenses](#review-workloads-using-custom-lenses)

## Prepare your custom lens WA template json file
Feel free to download the [ORR sample custom lens](ORR-Lens/ORR-Whitepaper-Sample-PUBLISHED.json) and edit is as needed.

## Navigate to the AWS WA Tool on the AWS console and create custom lens

After you prepare your custom lens WA template json file, you can navigate to the AWS WA Tool on the AWS console and create custom lens.
![image 1](https://user-images.githubusercontent.com/17841922/175503831-cf89ff5e-8c6e-42c7-b796-3ff91e9d8470.png)

Upload the your custom lens WA template json template, and submit it.
![image 2](https://user-images.githubusercontent.com/17841922/175503996-9b734d2c-8220-4efb-b5d2-f4ad77ad0ff4.png)

## Publish your custom lens and attached with version tag

And then you will find your custom lens WA in draft version.

Publish your draft version attached with version tag.


## Review workloads using custom lenses

After your custom lens WA is publish, you can define a workload in your WA console.
![image 7](https://user-images.githubusercontent.com/17841922/175505004-1f9026f7-c3f8-415d-92a1-747ab68f6610.png)

Input your workload information, and select the newly published 'AWS Operational Readiness Review Whtiepaper Sample' custom lens. 


You can continue reviewing and answer the questions for custom lens.

Now you can review your 'Operational Readiness Review' (ORR) with customized questionnaire and practice.
