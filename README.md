# Cloud Security Hardening (AWS S3 & IAM)

## 📌 Overview
This project demonstrates how to identify and fix cloud security misconfigurations in AWS. The goal is to show the risks of insecure S3 buckets and IAM roles, then harden them using best practices.

## 🛠 Tools Used
- AWS Free Tier
- AWS CLI

## 🔍 Steps
1. Create an S3 bucket with default permissions.
2. Simulate a misconfiguration (public access enabled).
3. Verify that sensitive data can be accessed publicly.
4. Apply best practices:
   - Enable bucket encryption (AES-256).
   - Restrict public access.
   - Configure IAM least privilege roles.
   - Enable CloudTrail logging.
5. Re-test security posture.

## 📊 Findings
- Initial state: Data was publicly accessible.
- After hardening: Public access blocked, logs enabled.

## 📑 Report
- Documented a **Before vs After Security Posture**.
- Added screenshots of IAM policy changes.

## 🎯 Skills Learned
- AWS security basics
- Cloud misconfiguration risks
- IAM role management
