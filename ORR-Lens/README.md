# Operational Readiness Review (ORR) Lens

Amazon Web Services (AWS) created the Operational Readiness Review (ORR) to distill the learnings from AWS operational incidents into curated questions with best practice guidance. Refer to the [ORR Whitepaper](https://docs.aws.amazon.com/wellarchitected/latest/operational-readiness-reviews/). Within the Whitepaper [Appendix B](https://docs.aws.amazon.com/wellarchitected/latest/operational-readiness-reviews/appendix-b-example-orr-questions.html) provides example ORR questions. The following ORR lens models those questions as a template to get started quickly building an ORR practice using WA custom lens as the tool. 


# Customize Well-Architected Reviews using Custom Lenses Sample Questionnaire

The AWS Well-Architected Tool makes it easy to create custom lenses by providing a json template that you can use. The template outlines how the lens content must be defined, and it controls how the lens is presented within the AWS WA Tool. This sample used ORR questions as an example from the ORR Whitepaper (see above) to show how to create Custom Lens in WA console from json template with the following several steps:
1. [Prepare your custom lens WA template json file](#prepare-your-custom-lens-WA-template-json-file)
2. [Navigate to the AWS WA Tool on the AWS console and create custom lens](#navigate-to-the-aws-wa-tool-on-the-aws-console-and-create-custom-lens)
3. [Publish your custom lens and attached with version tag](#publish-your-custom-lens-and-attached-with-version-tag)
4. [Review workloads using custom lenses](#review-workloads-using-custom-lenses)

## Prepare your custom lens WA template json file
Feel free to download the [ORR sample custom lens](ORR-Whitepaper-Sample-PUBLISHED.json) and edit is as needed.

## Navigate to the AWS WA Tool on the AWS console and create custom lens

After you prepare your custom lens WA template json file, you can navigate to the AWS WA Tool on the AWS console and create custom lens.
![orr-create-custom-lens](https://user-images.githubusercontent.com/3434790/187253712-ca472b7b-30bb-41f9-8cbd-db622ecea5c9.jpg)

Upload the your custom lens WA template json template, and submit it.
![orr-upload-json-file](https://user-images.githubusercontent.com/3434790/187254567-fa9e9fd6-4625-4dd9-98d4-89e477172b2b.jpg)

## Publish your custom lens and attached with version tag

And then you will find your custom lens WA in draft version.
![orr-publish-custom-lens](https://user-images.githubusercontent.com/3434790/187256107-3f3db861-bd6c-4ce1-b3ae-a924cd3607bd.jpg)

Publish your draft version attached with version tag. After which the status will change from DRAFT to PUBLISHED


## Review workloads using custom lenses

After your custom lens WA is published, you can define a workload in your WA console to use the custom lens.
![image 7](https://user-images.githubusercontent.com/17841922/175505004-1f9026f7-c3f8-415d-92a1-747ab68f6610.png)

Input your workload information, and select the newly published 'AWS Operational Readiness Review Whtiepaper Sample' custom lens. 
![orr-define-workload](https://user-images.githubusercontent.com/3434790/187257574-a0cb454a-5108-42cb-b590-9e0f6a1e71ee.jpg)

You can continue reviewing and answer the questions for custom lens.
![orr-review-workload-using-custom-lens](https://user-images.githubusercontent.com/3434790/187259743-689d717e-cc64-4f57-899d-2ba05b556100.jpg)

Now you can review your 'Operational Readiness Review' (ORR) with customized questionnaire and practice.
![orr-workload-review-custom-lens](https://user-images.githubusercontent.com/3434790/187260519-53a034c2-7663-448b-9011-09c7d53cf0d4.jpg)
