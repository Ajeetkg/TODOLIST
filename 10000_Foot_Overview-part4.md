# AWS 10000 foot overview

## Compute
* EC2: Elastic compute cloud
* EC2 Container Service: Elastic compute cloud container service- docker containers. Where you run and manage docker containers
* Elastic BeanStalk: Who don't know about AWS, they just upload the code and everything else is taken care by Amazon.
* Lambda: You control when the code executes. You only worry about the code. 
* Lightsail: similar to EC2
* Batch: for batch computing

##  Storage
* S3: Simple storage service
* EFS: Elastic File system. Mounting to multiple machiens
* Glacier: Want to archive the data
* Snowball: Way to bring large amount of data, use physical way to bring data to AWS cloud
* Storage gateway: Virtual machines which you install in your datacenter. This will replicate data in the S3.

## Database
* RDS: Relations Database. Any relational database will be in RDS
* DynamoDB: Non-relational database
* ElasticCache: Way to cache data from the common services. Free up database
* Red Shift: To do complex queries on your system. Data warehousing service

## Migration
* AWS Migration Hub: A way of tracking service as you migrate to AWS
* Application Discovery Service: Automated way of finding the application/services
* Database Migration Service: Helps you migrate the database
* Snowball: Storage and migration, To migrate large amount of data


## Network
* VPC: let you configure your virtual private network, fundamental is very important to pass the exam. you build the firewalls.
* Cloudfront: Amazon content delivery network.  If you got your image file or videos, and website is hosted in Australia, it will create a copy if someone is accessing in london.
* Route53: DNS system from Amazon. IPV6 address for your system.
* API Gateway: Developer associate course. Servelesss website 
* Direct Connect: Running a dedicated line from the corporate office to the AWS



## Developer Tools:
* CodeStar: group of developer working closely. You have CI tool chain. Way of collaborating with other developers
* Codecommit: Store your commit. Source commit
* CodeBuild: Very similar to Jenkins
* CodeDeploy: Deploys to EC2 instance
* Code pipeline: Visualize and model your different services
* X-Ray: To debug the application
* Cloud9: its IDE, you can do your code in the browser, no need to IDE.

----

# 10000 Foot overview - Management Tools - Part 3

## Management Tools
* CloudWatch:
* CloudFormation: solutions architect uses this service. It is a way of scripting infrastructure. Earlier, you had to buy physical server, load balancer etc. CloudFormation takes that job and make it very easy. You can reuse the same code to deploy at any other location. You can also opensource the work.
* CloudTrail: Anything you do in the AWS cloud, it is basically triggering AWS to log the action in the CloudTrail. It is turned-on by default but stores data only for one week.
* Config: AWS Config monitors the configuration of your entire AWS environment. 
* OpsWork: for configuration of the environment
* Service Catalog: Way of managing catalog of IT services. Fortune 500 companies generally use this service. Catalog service.
* System Manager: Want to manage security patches across thousands of application, you can group your application.
* Trusted Advisor: Difference between Trusted Advisor and inspector. It will give advise across multiple discipline, about security, across the services you don't use. It is like accountant who gives advise across several services.
* Managed Services: AWS managed services

## Media Services
* Elastic Transcoder: It will resize the recordded videos so that it looks good on different services
* MediaConvert: transcoder
* MediaLIve: high quality video stream to broadcoast to TV
* MediaPackage: Prepares and protect your videos
* MediaStore: Optimize for media, to give live and on-demand services
* Media Tailor: Targetted advertizing 

## Machine Learning
* SageMaker: makes it really easy for developer to use DEEP LEARNING. 
* Comprehend: Amazon Comprehend does sentiment analysis across data. Whether pepole are saying good or bad things about the products.
* DeepLens: Artificial camera which can finds out what is happening in front of the camera. Security... Deeplens is physical device. Camera itself can itself figures out what it is looking at.e.g. Somebody is coming through the door, and the camera can itself figure out whether to open the door or not.
* Lex: What powers alexa services. it is a way of communicating with the customer, to chat with the customer.
* Machine learning: It is different from SageMaker ( Deep learning- neural networks). Machine learning ... throw a dataset to the AML and, it will determine outcome on new data. Whenever you login to Amazon, its recommendation is based on Machine learning.
* Polly: It takes text and turns into speech. These voices sounds like humans... australian, british, indian accents. Just save them in the text editor and then can listen them on our demans. It is a good way to prepare of the exam.
* Rekognition: You upload a file, and it will tell you what is there in the picture. What all is there in the picture. Rekognition will tell you what it finds in the video.
* Amazon Translate: Google translatpr
* Amazon Transcribe: To transcribe our courses  - uploads the video, speech and, it converts to text. You can create a service using polly, rekognition, translate and transcribe.


## Analytics
* Athena: it allows to let you run SQL across the S3 buckets. Completly serverless and easy to use.
* EMR: Elastic map reduce. to process large amount of data. big data solutions.
* CloudSearch: Search services for AWS
* ElasticSearch Service: Angolia
* Kinesis: big data specialy, solutions architect specialit. it is a way of communicating with the customer, to chat with the customer.
* Machine learning: It is different from SageMaker ( Deep learning- neural networks). Machine learning ... throw a dataset to the AML and, it will determine outcome on new data. Whenever you login to Amazon, its recommendation is based on Machine learning.
* Polly: It takes text and turns into speech. These voices sounds like humans... australian, british, indian accents. Just save them in the text editor and then can listen them on our demans. It is a good way to prepare of the exam.
* Rekognition: You upload a file, and it will tell you what is there in the picture. What all is there in the picture. Rekognition will tell you what it finds in the video.
* Amazon Translate: Google translatpr
* Amazon Transcribe: To transcribe our courses  - uploads the video, speech and, it converts to text. You can create a service using polly, rekognition, translate and transcribe.


## Analytics
* Athena: it allows to let you run SQL across the S3 buckets. Completly serverless and easy to use.
* EMR: Elastic map reduce. to process large amount of data. big data solutions.
* CloudSearch: Search services for AWS
* ElasticSearch Service: Angolia
* Kinesis: big data specialy, solutions architect speciality. Let you stream large amount of data.
* Kinesis Video Streams: it is similar to Media services.
* QuickSight: Amazons business intelligence tool. Its a great BI tool at the fraction of other business intelligence tool.
* Data Pipeline: It is a way of moving data across the different services.
* Glue: it is used for ETL.


## Security & Identity & Compliance







