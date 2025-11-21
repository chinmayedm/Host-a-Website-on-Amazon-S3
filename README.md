# Host a Website on Amazon S3
# 30 Second Summary

You can use Amazon S3 to store and retrieve any amount of data at any time from anywhere on the web.
In this project, you’ll create an S3 bucket to store pictures and files needed for your website and host a static site directly from S3.

![architect]

# Project Overview

You will host a website using Amazon S3 by uploading your site’s HTML file and image assets into an S3 bucket and making them publicly accessible.
By the end, you’ll have a fully hosted static website running from your own S3 bucket.

# AWS Beginners Challenge

This is Project ONE of the AWS Beginners Challenge—hands-on, beginner-friendly, and perfect for building your cloud portfolio.

# Step 1 — Create a Bucket in Amazon S3

In this step:

Open Amazon S3

Create a storage space for your website files
# Steps:

1. Log in to AWS Console

2. Search for S3

3. Choose your closest AWS Region

4. Select Create bucket

5. Bucket name: nextwork-website-project-yourname

6. Enable ACLs

7. Set Object Ownership to Bucket owner preferred

8. Disable Block all public access and acknowledge the warning

9. Enable Bucket Versioning

10. Create bucket

# What is an ACL? Did you enable or disable ACLs?

An ACL is an Access Control List that controls who can access or modify objects inside the bucket. I enabled ACLs because I need to make individual files public for website hosting.

# Step 2 — Upload Website Content to Your Bucket

In this step:

Download the project’s HTML file

Download and unzip the images folder

Upload both into S3

You will upload:

index.html

The unzipped folder of images

# Step 3 — Configure Static Website Hosting

In this step:

Enable static website hosting in S3

Access your website URL

Steps:

1. Go to your bucket’s Properties

2. Scroll to Static website hosting

3. Choose Edit

4. Enable static hosting

5. Hosting type: Host a static website

6. Index document: index.html

7. Save changes

8. Open the bucket website endpoint URL

# Step 4 — Make Your S3 Objects Public

In this step:

Make your website files publicly accessible

View your live website

Use ACLs to make all objects public, then reload your website URL.