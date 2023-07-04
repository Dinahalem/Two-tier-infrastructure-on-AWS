# Two-tier-infrastructure-on-AWS

**I improved my knowledge of cloud architecture by using Terraform to create a Two-tier infrastructure on AWS.

Here's a list of AWS services I utilized
🔹 🌐 Route 53 (DNS service)
🔹 🌍 CloudFront (CDN)
🔹 💻 EC2 (Server)
🔹 ⚖️ Auto Scaling group (Scale on demand)
🔹 🌐 VPC (Virtual private cloud: Private Network)
🔹 🗄️ RDS (Relational database services: Database)
🔹 🚀 DynamoDB (State-locking for tfstate file)
🔹 ☁️ Amazon S3 (Storing backend and achieving versioning)



cd book_shop_app
terraform init 

Note: we need public key and private key for our server so follow below procedure.
cd modules/key/
ssh-keygen.exe   #this command ask for key name then give client_key it will create pair of keys one public and one private.
