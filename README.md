In this project, a ETL data pipeline was built on AWS using Apache Airflow to automate the process.

First an Instance was created on EC2.
![Screenshot (66)](https://github.com/andremiracle/Data-Engineering/assets/39734097/5a0b7487-9f43-49ed-885a-770cf3a26f26)
On the image above, the instance is running and a public IPv4 address and some other information were generated including the Instance ID.
Then a S3 bucket named kaggle-dataset-team-bucket-ylm was created on the instance. This bucket houses the data to be used in this bucket. 
![Screenshot (67)](https://github.com/andremiracle/Data-Engineering/assets/39734097/c71f7811-bb6b-42fd-b36b-a8c5df253897)
The data needed for this project will be uploaded in the S3 bucket.

