# AWS Static Website Hosting

## Project Overview

This project demonstrates how to host a static website using Amazon S3. The website is designed as a personal portfolio with multiple pages and is deployed using AWS S3 Static Website Hosting.

The project showcases cloud deployment concepts and static website hosting without using a traditional web server.

---

## Live Website

Website URL:

http://rami-aws-static-website.s3-website.eu-north-1.amazonaws.com

---

## Features

- Responsive Portfolio Website
- Home Page
- About Page
- Projects Page
- Contact Page
- Custom CSS Styling
- JavaScript Interactivity
- Contact Form Integration
- AWS S3 Static Website Hosting
- Cloud-Based Deployment

---

## Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript

### Cloud Platform

- Amazon S3
- AWS Static Website Hosting

### Form Storage

- Google Sheets
- Google Apps Script

---

## Project Structure

aws-static-website-hosting/

├── index.html

├── about.html

├── projects.html

├── contact.html

├── css/

│ └── style.css

├── js/

│ ├── script.js

│ └── contact.js

├── images/

│ ├── profile.jpg

│ ├── project1.jpg

│ ├── project2.jpg

│ └── project3.jpg

└── README.md

---

## AWS Services Used

### Amazon S3

Amazon S3 is used to:

- Store website files
- Host static web pages
- Provide public website access

---

## Deployment Steps

### Step 1

Create an AWS Account.

### Step 2

Open Amazon S3 Service.

### Step 3

Create a new bucket.

Example:

rami-aws-static-website

### Step 4

Disable Block Public Access.

### Step 5

Enable Static Website Hosting.

### Step 6

Upload all website files.

### Step 7

Configure Bucket Policy.

### Step 8

Access the website through the generated endpoint URL.

---

## Bucket Policy Used

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicRead",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::rami-aws-static-website/*"
    }
  ]
}# aws-stacic-website-hosting
