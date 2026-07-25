# AWS S3 Cloud Storage Project

## 📌 Project Overview

This project demonstrates the practical implementation of **Amazon Simple Storage Service (Amazon S3)** for cloud-based object storage.

The project focuses on creating and configuring an S3 bucket, managing objects, and understanding the basic workflow of storing and accessing data using AWS cloud storage services.

This project was developed as a hands-on learning project to build practical knowledge of **AWS Cloud Computing and Cloud Storage**.

---

## ☁️ AWS Service Used

### Amazon S3

**Amazon Simple Storage Service (S3)** is an AWS object storage service that provides scalable and durable storage for data such as documents, images, files, backups, and application data.

In this project, Amazon S3 was used to:

- Create an S3 bucket
- Configure the bucket
- Upload objects/files
- Manage stored objects
- Understand bucket and object structure
- Explore access and permissions
- Work with cloud-based object storage

---

## 🎯 Objectives

The main objectives of this project were:

1. Understand the fundamentals of Amazon S3.
2. Create and configure an S3 bucket.
3. Upload and manage files in S3.
4. Understand the relationship between buckets and objects.
5. Explore S3 permissions and access control.
6. Gain practical experience with the AWS Management Console.
7. Build foundational cloud skills for a Cloud Engineer role.

---

## 🏗️ Project Architecture

The basic workflow of this project is:

```text
                    AWS Cloud
                        │
                        ▼
                ┌───────────────┐
                │   Amazon S3   │
                │     Bucket    │
                └───────┬───────┘
                        │
             ┌──────────┼──────────┐
             ▼          ▼          ▼
          Object 1   Object 2   Object 3
           File       Image      Document
