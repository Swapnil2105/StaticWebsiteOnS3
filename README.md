# Hosting Static Website on AWS S3

This project demonstrates how to host a static [website](https://mytestbucketpatik.s3.ap-south-1.amazonaws.com/index.html) on Amazon S3.

## Table of Contents
- [About](#about)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Solution](#solution)
- [License](#license)
- [Contact](#contact)

## About

This project serves as a guide for hosting a static website on AWS S3. It provides step-by-step instructions on setting up and deploying a simple static website on the Amazon S3 cloud storage service.

## Getting Started

Follow these steps to get a copy of the project up and running on your local machine.

### Prerequisites

Before you begin, make sure you have the following prerequisites :

- [AWS Account](https://aws.amazon.com/)
- [Static website](https://github.com/PratikPatil131/PratikPatil131.github.io.git)

### Solution

Follow these steps to host your static website on AWS S3:

1. **Log into your AWS account.**

2. **Create an S3 Bucket:**
   - Create a new S3 bucket through the AWS Management Console.

3. **Upload Your Website:**
   - Upload the files of your website to the newly created S3 bucket.

4. **Configure Static Website Hosting:**
   - In the S3 bucket properties, navigate to the "Static website hosting" option.
   - Click on "Edit," enable static website hosting, and specify your HTML page's name. Save the changes.

5. **Adjust Bucket Permissions:**
   - In the bucket properties, go to the "Permissions" tab.
   - Under "Block public access (bucket settings)," disable it.

6. **Configure Object OwnershipInfo:**
   - Scroll down to "Object OwnershipInfo" in the bucket properties.
   - Click on "Edit" and enable ACLs. Choose "Bucket owner preferred" and save the changes.

7. **Make Objects Public:**
   - In the "Objects" tab, select your files.
   - Click on "Actions" and choose "Make public using ACL."

8. **Done:**
   - Your static website is now hosted on AWS S3.
   - Click on index.html and copy the Object URL, paste it into browser !!

## Note
- Ensure you replace "Your HTML page name" with the actual name of your HTML page.
- Review AWS S3 pricing and security considerations based on your usage.


Feel free to customize the steps based on your specific needs. If you have any questions or encounter issues, refer to the [AWS documentation](https://docs.aws.amazon.com/s3/index.html) for detailed information.
