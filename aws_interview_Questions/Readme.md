
# AWS Interview Questions and Answers

A sequential collection of AWS interview questions, answers,
practical examples, and troubleshooting scenarios.

## Table of Contents

1. [AWS Fundamentals](#1-aws-fundamentals)
2. [IAM](#2-iam)
3. [EC2](#3-ec2)
4. [S3](#4-s3)
5. [VPC and Networking](#5-vpc-and-networking)
6. [ELB and Auto Scaling](#6-elb-and-auto-scaling)
7. [RDS](#7-rds)
8. [CloudWatch and Monitoring](#8-cloudwatch-and-monitoring)
9. [Lambda](#9-lambda)
10. [EKS and Kubernetes](#10-eks-and-kubernetes)
11. [Security and Troubleshooting](#11-security-and-troubleshooting)

---

## 1. AWS Fundamentals

### Q001. What is AWS?

**Answer:**

AWS (Amazon Web Services) is a cloud computing platform
that provides services such as compute, storage, networking,
databases, security, and monitoring on demand.

**Real-world example:**

An application can run on EC2, store files in S3, and use
RDS for its relational database.

**Follow-up questions:**
- What is cloud computing?
- What is the difference between a Region and an Availability Zone?

---

### Q002. What is the difference between an AWS Region and an Availability Zone?

**Answer:**

A Region is a separate geographic area where AWS operates.
An Availability Zone is an isolated location within a Region
consisting of one or more data centers.

**Real-world example:**

Deploying an application across multiple Availability Zones
can improve availability if one zone experiences a failure.

---

## 2. IAM

### Q003. What is AWS IAM?

**Answer:**

AWS Identity and Access Management (IAM) controls who can
access AWS resources and what actions they can perform.

**Key concepts:**
- Users
- Groups
- Roles
- Policies
- Least-privilege access

**Real-world example:**

An EC2 application can assume an IAM role to access an S3
bucket without storing long-lived access keys on the server.

---

## Progress Tracker

| Topic | Questions | Status |
|---|---|---|
| AWS Fundamentals | Q001–Q002 | In progress |
| IAM | Q003 onward | In progress |
| EC2 | Not started | Pending |
| S3 | Not started | Pending |
| VPC and Networking | Not started | Pending |
