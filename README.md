#Hosting Static Website on AWS S3
This project demonstrates how to host a static website on Amazon S3.

Table of Contents
About
Getting Started
Prerequisites
Solution
License
Contact
About
This project serves as a guide for hosting a static website on AWS S3. It provides step-by-step instructions on setting up and deploying a simple static website on the Amazon S3 cloud storage service.

Getting Started
Follow these steps to get a copy of the project up and running on your local machine.

Prerequisites
Before you begin, make sure you have the following prerequisites :

AWS Account
Static website
Solution
Follow these steps to host your static website on AWS S3:

Log into your AWS account.

Create an S3 Bucket:

Create a new S3 bucket through the AWS Management Console.
Upload Your Website:

Upload the files of your website to the newly created S3 bucket.
Configure Static Website Hosting:

In the S3 bucket properties, navigate to the "Static website hosting" option.
Click on "Edit," enable static website hosting, and specify your HTML page's name. Save the changes.
Adjust Bucket Permissions:

In the bucket properties, go to the "Permissions" tab.
Under "Block public access (bucket settings)," disable it.
Configure Object OwnershipInfo:

Scroll down to "Object OwnershipInfo" in the bucket properties.
Click on "Edit" and enable ACLs. Choose "Bucket owner preferred" and save the changes.
Make Objects Public:

In the "Objects" tab, select your files.
Click on "Actions" and choose "Make public using ACL."
Done:

Your static website is now hosted on AWS S3.
Click on index.html and copy the Object URL, paste it into browser !!
Note
Ensure you replace "Your HTML page name" with the actual name of your HTML page.
Review AWS S3 pricing and security considerations based on your usage.
Feel free to customize the steps based on your specific needs. If you have any questions or encounter issues, refer to the AWS documentation for detailed information.
