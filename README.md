# ☁️ AwsPracticeNotes

A personal repository documenting hands-on AWS practices and learnings.  
You can easily see which AWS services I’ve worked with, and explore how I combined them in real system builds.

---

## 🧩 AWS Services Covered

| Service | Status | Notes / Related Projects |
|----------|---------|---------------------------|
| [EC2](./services/EC2/README.md) | ✅ Completed | Used for backend hosting in [Fullstack on EC2](./projects/fullstack-on-ec2/) |
| [RDS (MySQL)](./services/RDS/README.md) | ✅ Completed | Connected to EC2 app; automated backups configured |
| [S3](./services/S3/README.md) | ✅ Completed | Used for static website hosting |
| [Route 53](./services/Route53/README.md) | ✅ Completed | Custom domain and subdomain setup |
| [CloudWatch](./services/CloudWatch/README.md) | ✅ Completed | Log shipping and metrics visualization |
| [IAM](./services/IAM/README.md) | 🔄 In Progress | Working on policy least-privilege setup |
| [VPC]() | ✅ Completed |  |
| [Lambda]() | ✅ Completed |  |
| [ELB]() | ✅ Completed |  |
| [AWS Certificate Manager]() | ✅ Completed |  |
| [Cognito]() | ✅ Completed |  |
| [NatGateWay]() | ✅ Completed |  |
| []() | ✅ Completed |  |
| []() | ✅ Completed |  |
| []() | ✅ Completed |  |

---

## 🏗️ Projects (System Builds)

| Project | Summary | Main Services Used |
|----------|----------|-------------------|
| [Fullstack on EC2](./projects/fullstack-on-ec2/) | React + Spring Boot on EC2 with RDS and ALB | EC2, RDS, ALB, Route53 |
| [Static Website on S3](./projects/static-web-on-s3/) | S3 static hosting + CloudFront + Route53 | S3, CloudFront, Route53 |
| [Monitoring Setup](./projects/monitoring-with-cloudwatch/) | EC2 logs to CloudWatch + custom metrics | CloudWatch, EC2 |

---

## 🧱 Repository Structure

```
AwsPracticeNotes/
├── services/ # Individual AWS service notes
├── projects/ # Hands-on builds combining multiple services
├── diagrams/ # Architecture diagrams
└── docs/ # Templates and references
```

---

