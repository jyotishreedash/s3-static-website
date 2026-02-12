
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
