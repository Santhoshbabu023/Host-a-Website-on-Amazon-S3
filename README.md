# Host-a-Website-on-Amazon-S3
This project demonstrates how to host a static website using Amazon S3. By creating an S3 bucket, uploading files like `index.html` and images, and enabling static website hosting, the site becomes publicly accessible via a generated URL. It provides a simple, scalable, and cost-effective solution for hosting static websites.

## Project Overview

In this project, we will:
- Set up an S3 bucket.
- Upload website files such as `index.html` and image assets.
- Enable static website hosting on S3.
- Make the website publicly accessible via a generated URL.

## Prerequisites

Before getting started, ensure you have the following:
- An AWS account.
- Basic knowledge of how to use AWS S3.

## Steps to Set Up

1. **Create an S3 Bucket**:
   - Sign in to the AWS Management Console.
   - Navigate to S3 and create a new bucket.
   - Ensure the bucket name is globally unique.

2. **Upload Website Files**:
   - Upload the necessary files such as `index.html` and any image files (e.g., in a zip folder).

3. **Enable Static Website Hosting**:
   - In your S3 bucket settings, enable static website hosting.
   - Set the index document (e.g., `index.html`).

4. **Set Permissions**:
   - Ensure the files are publicly accessible by setting the correct Access Control List (ACL).
   - Make sure your image files and HTML files are publicly readable.

5. **Access the Website**:
   - After setting everything up, S3 will generate a bucket endpoint URL.
   - You can use this URL to access your website from any browser.

## Conclusion

By following these steps, you'll have a static website hosted on Amazon S3, offering a simple, scalable, and cost-effective solution for publishing content on the web.
