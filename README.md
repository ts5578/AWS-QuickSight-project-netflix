
# AWS QuickSight Project 

This is a mini project created using AWS Services - Amazon S3 and Amazon QuickSight. This project aims to provide instructions on how to use AWS services to create visualizations from large datasets.

[![AWS](https://img.shields.io/badge/AWS-100000?style=flat&logo=amazon&logoColor=FFFFFF&labelColor=5C5C5C&color=FF7300)](https://docs.aws.amazon.com/quicksight/latest/user/signing-up.html)[![S3](https://img.shields.io/badge/AWS_S3-100000?style=flat&logo=AmazonS3&logoColor=white&labelColor=494949&color=569A31)](https://aws.amazon.com/s3/)
[![S3](https://img.shields.io/badge/AWS_Quicksight-100000?style=flat&logo=QuickLook&logoColor=white&labelColor=494949&color=22A2E3)](https://aws.amazon.com/quicksight/)



## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#projectoverview)
- [Data Source](#datascource)
- [Resources](#resources)
- [Usage](#usage)
- [Conclusion](#conclusion)
- [License & Credits](#license)






## Introduction

This project was created as part of a tutorial by [NextWork](https://www.youtube.com/@itsnextwork). The [tutorial](https://www.youtube.com/live/SnFDQ-4Il2g?si=Is7z0gx6Z_4y1bX1), provided a step-by-step guide on how to use Quicksight for data visualization and analysis. Quicksight is an Amazon Web Services (AWS) tool that allows users to create interactive dashboards and reports using their own data. By following the tutorial, I was able to learn how to use Quicksight to create engaging visualizations and gain valuable insights from my data.
## Project Overview 

The project involves the following steps:

- Download a dataset of over 8000 movies and tv shows on Netflix from Kaggle.
- Store the dataset into an Amazon S3 bucket.
- Connect the S3 bucket with Amazon Quicksight to create a few interesting visualizations.
## Data Source

Dataset used for this project - 
[Netflix Dataset Link](https://storage.googleapis.com/nextwork_course_resources/courses/aws/AWS%20Project%20People%20projects/Project%3A%20Visualise%20Data%20using%20Amazon%20QuickSight/netflix_titles.csv)

### Resources

The following resources were used in the development of this project:

- ![S3](https://img.shields.io/badge/AWS_S3-100000?style=flat&logo=AmazonS3&logoColor=white&labelColor=494949&color=569A31)
- [![S3](https://img.shields.io/badge/AWS_Quicksight-100000?style=flat&logo=QuickLook&logoColor=white&labelColor=494949&color=22A2E3)](https://aws.amazon.com/quicksight/)


## Usage

To get started with this project, please follow the steps listed below:

1. Clone this repository.
2. Download the CSV file named "netflix_titles.csv" and the JSON file named "manifest.json" from the GitHub page.
3. Head over to the AWS Management Console and create an S3 bucket.
4. Upload the CSV file to the S3 bucket.
5. Open the manifest.json file and make the necessary changes to the file as mentioned in the video.
6. Connect the S3 bucket with Amazon Quicksight to create visualizations.

### Step 1: Clone this repository

```
git clone https://github.com/ts5578/AWS-QuickSight-project-netflix.git 
```

### Step 2: Download the CSV file and the JSON file

Download the CSV file named [Amazon-Bestseller-Dataset.csv](netflix_titles.csv) and the JSON file named [manifest.json ](manifest.json) from the GitHub page.

### Step 3: Create an S3 bucket

Head over to the AWS Management Console and create an S3 bucket.

### Step 4: Upload the CSV file to the S3 bucket

Upload the CSV file to the S3 bucket.
![Bucket](./assets/s3-bucket.png)


### Step 5: Make the necessary changes to the manifest.json file

Open the manifest.json file and make the necessary changes to the file as mentioned in the video.

![Modify](./assets/modify-manifest.png)


### Step 6: Connect the S3 bucket with Amazon Quicksight to create visualizations

Connect the S3 bucket with Amazon Quicksight to create visualizations.

## Conclusion

This project provides hands-on experience in using AWS services to create visualizations from large datasets. By following the instructions provided, you can learn how to use Amazon S3 and Amazon Quicksight to create compelling visualizations. Feel free to customize the project to your liking and experiment with different datasets to gain more insights.

![Results](./assets/result2.png)

## License
This project is based on the tutorial [Analyse Netflix Data with Amazon QuickSight](https://www.youtube.com/live/SnFDQ-4Il2g?si=WScLinPe7GCfbSTz) by [NextWork](https://www.youtube.com/@itsnextwork). 

[MIT](https://choosealicense.com/licenses/mit/)





