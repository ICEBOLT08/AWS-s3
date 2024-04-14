# Hosting a Static Website Using AWS S3

## Table of Contents
1. [Introduction to AWS S3](#introduction-to-aws-s3)
2. [Prerequisites](#prerequisites)
3. [Step-by-Step Guide](#step-by-step-guide)
    - [Creating an S3 Bucket](#creating-an-s3-bucket)
    - [Configuring Bucket for Website Hosting](#configuring-bucket-for-website-hosting)
    - [Uploading Website Files](#uploading-website-files)
    - [Setting Bucket Policy](#setting-bucket-policy)
    - [Accessing the Website](#accessing-the-website)
4. [Theory: What is AWS S3?](#theory-what-is-aws-s3)
5. [Conclusion](#conclusion)

## Introduction to AWS S3

Amazon Simple Storage Service (S3) is an object storage service offered by Amazon Web Services (AWS). It provides scalable, secure, and highly durable storage for various types of data, including websites. With S3, you can host static websites, store and retrieve any amount of data, and integrate with other AWS services.

## Prerequisites

- AWS account
- AWS CLI installed (optional)
- Basic knowledge of HTML/CSS for website creation

## Step-by-Step Guide

### Creating an S3 Bucket

1. **Sign in to AWS Management Console**:
   - Open [AWS Management Console](https://aws.amazon.com/console/) and sign in to your AWS account.

2. **Navigate to S3**:
   - In the AWS Management Console, search for "S3" or find it under "Storage" services.

3. **Create a New Bucket**:
   - Click on the "Create bucket" button.
   - Enter a unique name for your bucket.
   - Choose a region.
   - Click "Next."

![Creating an S3 Bucket](https://github.com/ICEBOLT08/AWS-s3/blob/main/Screenshot%202024-04-15%20005536.png)

### Configuring Bucket for Website Hosting

1. **Select Bucket**:
   - In the S3 dashboard, click on the bucket you just created.

2. **Enable Static Website Hosting**:
   - Go to the "Properties" tab.
   - Click on "Static website hosting."
   - Choose "Use this bucket to host a website."
   - Enter the name of your main HTML file (e.g., `index.html`) and the error document if you have one.
   - Click "Save changes."

![Configure Bucket for Website Hosting](https://github.com/ICEBOLT08/AWS-s3/blob/main/Screenshot%202024-04-15%20005924.png)

### Uploading Website Files

1. **Upload Files**:
   - Go to the "Objects" tab.
   - Click on the "Upload" button.
   - Drag and drop your website files or click "Add files" to select them.
   - Click "Upload."

![Uploading Website Files](https://github.com/ICEBOLT08/AWS-s3/blob/main/Screenshot%202024-04-15%20005650.png)

### Output

![Static Website](https://github.com/ICEBOLT08/AWS-s3/blob/main/Screenshot%202024-04-15%20010416.png)
