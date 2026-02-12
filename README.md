
# AWS S3 Static Website with Terraform

## 📌 Overview

This repository contains a Terraform configuration to provision and host a static website on **Amazon S3**.  
It demonstrates cloud infrastructure automation using Infrastructure as Code (IaC) to deploy a static HTML website.

---

## 🚀 Architecture & Tools

This project uses:

- **AWS S3** for hosting a static website  
- **Terraform** to define and provision AWS infrastructure  
- **HTML** files (index & error pages)

---

## 🛠️ What It Does

1. Creates an S3 bucket configured for static website hosting  
2. Sets public access and correct bucket policy  
3. Uploads `index.html` and `error.html`  
4. Optionally allows you to link a custom domain

You can deploy this configuration to any AWS account.

---

## 📁 Repo Structure

├── index.html # Main website page
├── error.html # Error page
├── provider.tf # AWS provider configuration
├── main.tf # S3 bucket and website configuration
├── output.tf # Terraform outputs
├── variables.tf # Input variables


---

## ⚙️ How to Deploy

1. Install Terraform  
2. Configure AWS credentials  
export AWS_ACCESS_KEY_ID="YOUR_KEY"
export AWS_SECRET_ACCESS_KEY="YOUR_SECRET"

3. Initialize Terraform  


terraform init

4. Apply the configuration  


terraform apply


After deployment, Terraform will output the S3 website URL.

---

## 🎯 Key Skills Demonstrated

✔ Cloud infrastructure automation using Terraform  
✔ AWS S3 static website hosting  
✔ Infrastructure as Code (IaC) best practices

---

## 🧪 Future Improvements

- Add CloudFront for HTTPS support  
- Enable automated deploy (GitHub Actions / CI/CD)  
- Add custom domain support

---

## 👩‍💻 Author

Jyotishree Dash
