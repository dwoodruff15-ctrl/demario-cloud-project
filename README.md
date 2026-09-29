# AWS Cloud Portfolio Website

A hands-on cloud project where I built and deployed a static professional portfolio website using Amazon Web Services.

🌐 **Live Website:** https://wutechdesigns.com

## Project Overview

The goal of this project was to gain hands-on experience deploying and securing a public website using AWS cloud services.

The website was developed locally using HTML and CSS, version-controlled with Git, stored on GitHub, and deployed using AWS.

## Architecture

GitHub → Amazon S3 → Amazon CloudFront → AWS WAF → Route 53 → Custom Domain

Additional security and configuration are provided through AWS Certificate Manager (ACM) and HTTPS.

## AWS Services Used

- **Amazon S3** — Stores and hosts the website files
- **Amazon CloudFront** — Content Delivery Network (CDN) used to securely deliver the website
- **AWS WAF** — Adds web application firewall protection
- **Amazon Route 53** — DNS management for the custom domain
- **AWS Certificate Manager (ACM)** — Provides the SSL/TLS certificate for HTTPS

## Other Technologies

- HTML
- CSS
- Git
- GitHub
- PowerShell

## What I Built

- Created a responsive professional portfolio website
- Created and configured an Amazon S3 bucket for website files
- Deployed the website through Amazon CloudFront
- Configured AWS WAF protection
- Registered and configured the `wutechdesigns.com` custom domain
- Configured DNS records using Route 53
- Requested and validated an SSL/TLS certificate using ACM
- Enabled HTTPS for secure website access
- Used Git and GitHub for source control
- Updated production files and invalidated the CloudFront cache after changes

## What I Learned

This project gave me practical experience connecting multiple AWS services to deploy a working cloud-hosted website. I gained hands-on experience with cloud storage, DNS, CDN configuration, web security, SSL/TLS certificates, Git version control, and troubleshooting a live deployment.

## Live Project

Visit the deployed website:

https://wutechdesigns.com
