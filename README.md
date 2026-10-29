# AWS S3 Security Audit

## Project Overview

This project demonstrates a basic security audit of an Amazon S3 bucket using AWS security best practices.

## 1 Security Checks

* S3 Block Public Access
* Bucket encryption (SSE-S3)
* Bucket policy review
* Object access permissions
* IAM least-privilege principles

## 2 Lab Environment

* Cloud Provider: Amazon Web Services (AWS)
* Service: Amazon S3
* Encryption: SSE-S3
* Public Access Block: Enabled

## 3 Findings

* Block Public Access is enabled.
* An object named `security-test.txt` was uploaded for testing.
* SSE-S3 encryption was selected.
* Bucket policy was reviewed.

## 4 Security Recommendations

* Keep Block Public Access enabled unless public access is specifically required.
* Use least-privilege IAM permissions.
* Review bucket policies regularly.
* Never publish AWS access keys, secret keys, or passwords.

## 5 Disclaimer

This is a learning lab using my own test resources. It is not a professional audit of a production environment.

AWS S3 security audit project covering public access, encryption, bucket policies, and security best practices.
## 6. Data Protection

* [x] S3 Bucket Versioning is enabled.
* [x] Object Ownership is set to Bucket owner enforced.
* [x] ACLs are disabled.
