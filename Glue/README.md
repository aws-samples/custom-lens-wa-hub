# AWS Glue Well-Architected Custom Lens

- [About](#about)
- [Prepare the json file](#prepare-the-json-file)
- [Create custom lens on Well-Architected Tool](#create-custom-lens-on-well-architected-tool)
- [Intended Audience](#intended-audience)
- [Contributing](#contributing)

## About
AWS Glue Well-Architected Custom Lens specifies best practices in Operational Excellence, Security, Performance Efficiency and Cost Optimization pillars. The best practices are designed for Glue workload. 

## Prepare the json file
Prepare your custom lens Well-Architected template json file or just download the [provided recommended glue custom lens file](custom-lens-glue-v2.0.json).
```json
{
   "schemaVersion":"2021-11-01",
   "name":"Glue Best Practice Lens",
   "description":"Best practices for configuring Glue",
   "pillars":[
      {
         "id":"PERF",
         "name":"Performance Efficiency",
         "questions":[
            {
               "id":"PERF1",
               "title":"Do konw how file formats, file size, file layout and compression effect your job performance?",
               "description":"To reduce the amount of data loaded into your job when reading from Amazon S3, you need to consider FileSize, Compression, FileFormat and FileLayout (Partitions) for your dataset.",
               "choices":[
                  {
                     "id":"PERF1_1",
                     "title":"Choice the suitable file format for you Glue ETL Job",
                     "helpfulResource":{
                        "displayText":"Have you use a columnar format. Apache Parquet and Apache ORC are popular columnar data formats?\n\nWhen using columnar formats, you can skip blocks of data that correspond to columns you do not plan to use.",
                        "url":"https://aws.amazon.com/blogs/big-data/top-10-performance-tuning-tips-for-amazon-athena/"
                     },
                     "improvementPlan":{
                        "displayText":"Use input/output parquet, orc dataformat",
                        "url":"https://aws.amazon.com/blogs/big-data/top-10-performance-tuning-tips-for-amazon-athena/"
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
![image 3](https://github.com/aws-samples/custom-lens-wa-hub/assets/17841922/957adf6d-9bde-422c-bf93-1a04ac416473)

Publish your draft version and provide a version tag.
![image 4](https://github.com/aws-samples/custom-lens-wa-hub/assets/17841922/a0aeaafb-e3ba-439f-a4e5-eb27faf68a62)

After your Well-Architected custom lens is published, you can define a workload in your AWS Well-Architected console.
![image 5](https://user-images.githubusercontent.com/17841922/175505004-1f9026f7-c3f8-415d-92a1-747ab68f6610.png)

Input your workload information, and select the Well-Architected custom lens you just published. 
![image 6](https://github.com/aws-samples/custom-lens-wa-hub/assets/17841922/aa84a735-15e9-4852-b600-e9d67cf5c9d9)

Choose Continue reviewing for the just published Glue Well-Architected custom lens.
![image 7](https://github.com/aws-samples/custom-lens-wa-hub/assets/17841922/69affe5c-9ec6-4f6b-8ab5-b97e43c2ae2c)

Now you can review your Glue workload with Glue Well-Architected Custom Lens.
![image 8](https://github.com/aws-samples/custom-lens-wa-hub/assets/17841922/3ebf536b-e453-4688-b15a-fbcfb7bb97d7)

## Intended Audience

CTO, Technical Leader or technical owner for an AWS Glue workload

## Contributing

- Noritaka Sekiyama, Principal Big Data Architect, AWS
- [Ray Wang](mailto:hsiawang@amazon.com), Solutions Architect, AWS
- Hsu, Chia-Wei Cloud Support Engineer (BigData), Glue SME, AWS


