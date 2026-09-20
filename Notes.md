# AWS Basics
AWS = cloud computing platform

Pay-as-you-use pricing

Scalable and reliable

Used for hosting websites, storage, and databases

# Create AWS Account
Sign up for AWS Free Tier

Add payment details

Verify account

Log in to AWS Management Console

# Services Used
EC2 = Virtual Server

S3 = File Storage

RDS/Aurora = Database

IAM = User Access Management

# EC2 Setup
Search EC2

Click Launch Instance

Enter instance name

Select Amazon Linux

Select t2.micro

Create a Key Pair

Configure Security Group

SSH (22)

HTTP (80)

HTTPS (443)

Launch Instance

# S3 Setup
Search S3

Click Create Bucket

Enter bucket name

Create bucket

Upload website images:

berry.jpg
orange.jpg
chocolate.jpg
caramel.jpg
strawberry.jpg
shop.jpg

## Make Images Public
Disable Block Public Access

Add Bucket Policy

Allow s3:GetObject for public viewing

Get Image URL

Open uploaded image

## Copy Object URL

Use URL in website HTML

IAM Setup

Search IAM

Create User

## Generate:

Access Key ID

Secret Access Key

Save credentials securely

# Aurora / RDS Setup
Search RDS

Click Create Database

Choose Aurora PostgreSQL

Enter:
Database name

Username

Password

Create database cluster

Copy database endpoint

Save:
Host

Username

Password

# Connect to EC2
Open EC2 Instance

Click Connect

Open browser terminal

Connect to server

# Deploy App
Install Git
Clone GitHub repository
Navigate to project directory
Configure S3 environment variables
S3_BUCKET
S3_REGION
S3_ACCESS_KEY
S3_SECRET_KEY
Configure Database environment variables
DB_HOST
DB_USER
DB_PASS
Install Node.js
Verify Node.js installation
Install project dependencies using npm
Start the website using npm start or node index.js
Verify database connection
Verify server is running on port 8080
Test website locally using localhost
Obtain EC2 public IP address
Open website using http://<PUBLIC-IP>:8080
Confirm:
Website loads successfully
Images load from S3
Database data loads correctly
Application is accessible from the browser
