
# Getting started with emr serverless and hudi
<img width="949" alt="Capture" src="https://user-images.githubusercontent.com/39345855/218268918-c059b8a0-73d2-43d2-9267-5e9e8ef7c23e.PNG">

# Phase 1 Create Hello world Hudi Transcation Datalake with EMR Serverless 
#### Step 1 Deploy the stack 
```
npm install -g serverless

serverless config credentials --provider aws --key XXXX  --secret XXXXX -o
```

##### Step 2:
```
When you submit job provides these conf
--conf spark.jars=/usr/lib/hudi/hudi-spark-bundle.jar --conf spark.serializer=org.apache.spark.serializer.KryoSerializer


```



#### Learn More
* Step by Step guide how to setup VPC & Subnet & Get Started with HUDI on EMR | Installation Guide |
* https://www.youtube.com/watch?v=-e1-Zsk17Ss

## Referneces
* https://catalog.us-east-1.prod.workshops.aws/workshops/e8e8fbb5-c3fb-4f86-bf77-0ba1fe402c55/en-US/transactional-data-lake/hudi
* https://docs.aws.amazon.com/emr/latest/EMR-Sesrverless-UserGuide/getting-started.html
