# Customize Well-Architected Reviews for DynamoDB

The AWS Well-Archtected Tool makes it easy to create custom lenses by providing a json template that you can use. The template outlines how the lens content must be defined, and it controls how the lens is presented within the AWS WA Tool. This repo used DynamoDB as an example to show how to create Custom Lens in WA console from json template with several step as following:
1. [Prepare your custom lens WA template json file](#prepare-your-custom-lens-WA-template-json-file)
2. [Navigate to the AWS WA Tool on the AWS console and create custom lens](#navigate-to-the-aws-wa-tool-on-the-aws-console-and-create-custom-lens)
3. [Publish your custom lens and attached with version tag](#publish-your-custom-lens-and-attached-with-version-tag)
4. [Review workloads using custom lenses](#review-workloads-using-custom-lenses)

## Prepare your custom lens WA template json file
Prepare your custom lens WA template json file by yourself or just download the [dynamodb custom lens](dynamodb/custom-lensddb.202204152309.json).

```json
{
   "schemaVersion":"2022-11-01",
   "name":"DynamoDB Best Practice Lens",
   "description":"Best practices for optimization your DynamoDB",
   "pillars":[
        {
         "id":"DDBOPS",
         "name":"Operational Excellence",
         "questions":[
            {
               "id":"ddbops1",
               "title":"How do you backup DynamoDB tables?",
               "description":"With proper backup process, you will be able to prevent unexpected data lost.",
               "choices":[
                  {
                     "id":"ddbops1_1",
                     "title":"Use On-Demand Backup for DynamoDB tables",
                     "description":"Some helpful choice description",
                     "helpfulResource":{
                        "displayText":"A detail description or definition of this best practice, and give a clear scope of this best practice in pillar, also the impact of the risk.",
                        "url":"https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/BackupRestore.html"
                     },
                     "improvementPlan":{
                        "displayText":"Enable On-Demand Backup",
                        "url":"https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/BackupRestore.html"
                     }
                  },...
               ]
            },...
         ]
      }
   ]
}

```

## Navigate to the AWS WA Tool on the AWS console and create custom lens

After you prepare your custom lens WA template json file, you can navigate to the AWS WA Tool on the AWS console and create custom lens.
![image 1](https://user-images.githubusercontent.com/17841922/175503831-cf89ff5e-8c6e-42c7-b796-3ff91e9d8470.png)

Upload the your custom lens WA template json template, and submit it.
![image 2](https://user-images.githubusercontent.com/17841922/175503996-9b734d2c-8220-4efb-b5d2-f4ad77ad0ff4.png)

## Publish your custom lens and attached with version tag

And then you will find your custom lens WA in draft version.
![image 3](https://user-images.githubusercontent.com/17841922/175504307-f5bd6dec-bab0-4dc1-be1f-c6dc77906483.png)

Publish your draft version attached with version tag.
![image 4](https://user-images.githubusercontent.com/17841922/175504406-4dcff143-00a5-4a7b-9952-2a2075ce95ab.png)

![image 5](https://user-images.githubusercontent.com/17841922/175504664-ed77ea17-6595-4e14-9751-6c8060daaea7.png)

![image 6](https://user-images.githubusercontent.com/17841922/175504933-b339be90-d99a-4bf9-a5ec-31d46943b3e0.png)

## Review workloads using custom lenses

After your custom lens WA is publish, you can define a workload in your WA console.
![image 7](https://user-images.githubusercontent.com/17841922/175505004-1f9026f7-c3f8-415d-92a1-747ab68f6610.png)

Input your workload information, and select the custom lens WA you just publish. 
![image 8](https://user-images.githubusercontent.com/17841922/175505110-aed421d6-648e-4821-a20c-ae092b48962d.png)

You can continue reviewing and answer the questions for custom lens.
![image 9](https://user-images.githubusercontent.com/17841922/175506629-f1afdcd8-06d5-4fa2-ae65-8dd991714b9b.png)

Now you can review your DynamoDB workload with customize questionare and practice.
![image 10](https://user-images.githubusercontent.com/17841922/175505647-835e5413-1b65-4a2d-89e3-072f8e695f2d.png)
