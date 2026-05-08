# Hosted-a-Website-on-Amazon-S3-bucket
<img width="856" height="316" alt="image" src="https://github.com/user-attachments/assets/fa90c918-1782-407d-9784-c51686b11f7b" />

This project demonstrates how to host a static website using Amazon S3
.
The website files, including HTML and image assets, are uploaded to an S3 bucket and configured for public access through static website hosting.

🚀 Project Overview

In this hands-on beginner cloud project, I:

Created and configured an S3 bucket
Enabled Static Website Hosting
Uploaded website content (HTML & images)
Configured public access permissions using ACLs
Hosted a live static website on AWS

This project helped me understand the fundamentals of:
Cloud storage
Static website hosting
AWS S3 bucket configuration
Access Control Lists (ACLs)
Public access management in AWS

🛠️ Technologies Used
Amazon Web Services (AWS)
Amazon S3
HTML
Static Website Hosting

📚 Key Learning Outcomes
Understanding how S3 works as object storage
Hosting static websites in the cloud
Managing permissions and bucket policies
Working with AWS Management Console
Learning the basics of cloud infrastructure

🌐 Features
Publicly accessible static website
Hosted directly from an S3 bucket
Image assets and HTML content management
Beginner-friendly AWS project

*****STEP-BY-STEP GUIDE*****
STEP 1 :- Create a bucket in Amazon S3
Log in to the AWS console.
In the AWS Management Console, search for S3
<img width="3072" height="1694" alt="image" src="https://github.com/user-attachments/assets/452eef3d-712a-473b-8d72-fcaccc7827c4" />
Select the AWS Region closest to you. You can find this at the top right corner of your AWS Management console, right next to your name.
<img width="3668" height="1318" alt="image" src="https://github.com/user-attachments/assets/5dc02122-7108-4a61-8cb1-0b45cc32b0ac" />
Choose Create bucket.
For Bucket name, enter
```bash
nextwork-website-project-
```
Make sure to replace enter your name with your name.
For Object Ownership, choose ACLs enabled.
<img width="1782" height="1275" alt="image" src="https://github.com/user-attachments/assets/2955600d-48d2-41a8-8b38-0286e3976ea8" />
Choose Bucket owner preferred.
For Block Public Access settings for this bucket, clear the check box for Block all public access.
Check the box that says “I acknowledge that the current settings might result in this bucket and the objects within becoming public.”
<img width="2020" height="1554" alt="image" src="https://github.com/user-attachments/assets/3d774de4-7d1a-4dda-b4dc-34c4660a7301" />
For Bucket Versioning, choose Enable.
Choose Create bucket.
<img width="1890" height="835" alt="image" src="https://github.com/user-attachments/assets/8d3b38bc-2bba-40ab-b2b9-897c2236202e" />

STEP 2 :-Upload website content to your bucket

In the Buckets section, choose the name of your new bucket.
Download these files to your computer so we can add them into your bucket (right click on each link, and select Save link as...):

index.html
NextWork - Everyone...love_files.zip

Open the Downloads folder in your local computer.
Unzip the .zip file you've downloaded.
Return to the Amazon S3 console with your bucket page open. Choose the Objects tab Objects.
Choose Upload.
Choose Add files.
Choose index.html.
Choose Add folder.
Choose the unzipped folder - NOT the zip file itself!
You might get a popup that tells you that all files in that folder will be uploaded ("Do you want to upload 44 files?"). Select Upload if you need to!
Choose Upload in your AWS console.
<img width="1936" height="1549" alt="image" src="https://github.com/user-attachments/assets/3da9e410-bbe8-4b4f-98ba-0accfa76a7e7" />
S3 will get to work right away!
While we wait for your files to upload...
<img width="1889" height="1549" alt="image" src="https://github.com/user-attachments/assets/d211f53d-4093-4315-8402-b418ba4fa129" />
Choose Close underneath the green Upload succeeded banner.
<img width="1722" height="982" alt="image" src="https://github.com/user-attachments/assets/d3304eb1-b453-4d9f-b5f8-c3784ed96fab" />
<img width="2022" height="1076" alt="image" src="https://github.com/user-attachments/assets/9d84bf12-0895-424b-9f82-9189256fca24" />

STEP 3 :-Configure a static website on Amazon S3

Next up, let's make your website available on the internet by setting up static website hosting!
Make sure you're back in your bucket's page. If you're not sure, choose General purpose bucckets on the left hand side navigation bar, and then choose the bucket you created for this project.
Choose the Properties tab.
Scroll allllllllll the way down to the Static website hosting panel.
Choose Edit.
<img width="2025" height="813" alt="image" src="https://github.com/user-attachments/assets/ea58fc72-1ede-4014-835d-58cd326ab67c" />
Configure the following settings:
Static web hosting: Choose Enable.
Hosting type: Choose Host a static website.
Index document: Enter index.html
<img width="2034" height="1415" alt="image" src="https://github.com/user-attachments/assets/19b07056-419e-466a-8c60-70f3eac0d227" />
Choose Save changes.
In the Static website hosting panel, click on the URL under Bucket website endpoint.
<img width="2034" height="1074" alt="image" src="https://github.com/user-attachments/assets/1188ee39-b8bb-44da-9a55-79a7831be8bd" />

An error!
<img width="2080" height="673" alt="image" src="https://github.com/user-attachments/assets/167bf8db-bd82-4410-9ea3-736cdee2d583" />


STEP 4 :-Make objects in your S3 bucket public

The only missing ingredient is to make your website files publicly accessible, so everyone has permission to view your website.
Keep the error message tab open and switch back to the Amazon S3 console tab.
Do you still remember how to view your S3 bucket's objects? Try finding your bucket's Objects page and making your objects public using ACLs. 
You'll know it's working when you see an awesome website like the one below.
<img width="2988" height="1868" alt="image" src="https://github.com/user-attachments/assets/a66ddab4-9902-4875-a2b0-39c134a97d9b" />

STEP 5 :- Delete all the resources

GUIDE VIDEO LINK:-https://www.youtube.com/watch?v=MxemozHPwp0






