Continuous Integration of GitHub, Jenkins and HashiCrop Terraform on AWS Cloud

Task Description:--

Create the key and security group which allow the port 80,22.
Launch EC2 instance.
In this Ec2 instance use the key and security group which we have created in step 1.
Launch one Volume (EBS) and mount that volume into /var/www/html
Copy the github repo code into /var/www/html
Create S3 bucket, and copy/deploy the images from github repo into the s3 bucket and change the permission to public readable.
Create a Cloudfront using s3 bucket(which contains images) and use the Cloudfront URL to update in code in /var/www/html/
create jenkins CI/CD pipeline
create snapshot of ebs
