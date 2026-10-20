---
title: Przemysław Kozłowski
pdf_url: /cv.pdf
github_url: https://github.com/przemyslaw-koz
linkedin_url: https://linkedin.com/in/przemyslaw-kozlowski-devops
---

## DevOps Engineer | Senior Backend Developer
- [linkedin.com/in/przemyslaw-kozlowski-devops](https://linkedin.com/in/przemyslaw-kozlowski-devops)
- [github.com/przemyslaw-koz](https://github.com/przemyslaw-koz)
- tel: 510-385-789
- email: przemyslaw.koz@gmail.com

## Summary
DevOps Engineer with 12 years of experience in software engineering, cloud infrastructure and operations. Spent most of my career building backend systems in .NET and Node.js, including several years in senior backend roles, before gradually moving towards DevOps over the last three years. Currently working mainly with AWS, Terraform, CI/CD, infrastructure automation, production operations and cloud cost optimization. My development background helps me troubleshoot systems across both application and infrastructure layers.

## Experience

- DevOps Engineer at PGS Software / Xebia (11.2025 – now)
  - Building and maintaining Docker based workloads on EC2.
  - Working with Azure DevOps pipelines, including troubleshooting existing pipelines, creating new ones and migrating Classic pipelines to YAML.
  - Managing AWS infrastructure with Terraform.
  - Set up and maintained SonarQube on AWS EC2 for production use.
  - Migrated a legacy PHP/Apache application to a new Windows Server environment, including runtime setup, SQL Server connectivity and external integrations.
  - Analyzing EC2, ECS/Fargate, RDS/Aurora and Auto Scaling workloads using Cost Explorer, CloudWatch, Performance Insights and workload metrics to find rightsizing, scheduling and autoscaling opportunities.
  - Reviewing and optimizing S3 lifecycle policies, RDS backup retention, AMI/EBS snapshots, CloudWatch logs, CloudTrail and AWS Config configurations.
  - Identified AWS cost savings worth thousands of USD per month across compute, storage, backups and logging.

- Senior Node.js Developer at PGS Software / Xebia (04.2022 – 10.2025)
  Started mainly as a backend role and gradually shifted towards AWS, infrastructure, CI/CD and DevOps work.

  - Developed backend APIs in Node.js, TypeScript and NestJS, with unit tests in Jest; later introduced Traefik in place of a custom API gateway component.
  - Built AWS infrastructure in Terraform, including Lambda functions, Cognito configuration, IAM roles and supporting resources.
  - Implemented a Cognito-based authentication and user management setup for a training platform, with Lambda functions handling temporary passwords, account access and password resets, and SES used for email notifications.
  - Built and maintained a separate training environment mirroring the production setup, including deployments, releases and troubleshooting when the environment or dependent services failed.
  - Reworked the nightly test environment pipeline so tests started as soon as an EC2-based environment became ready instead of waiting for fixed time slots. Tests were chained automatically and the instances were terminated after the final run, cutting execution time from roughly 10 hours to 3–4 hours and reducing idle EC2 time.
  - Upgraded a heavily outdated Grafana setup to a current version, which required updating dashboards and queries, changing data sources and adjusting Docker images used by dependent services.
  - Worked extensively with Azure DevOps pipelines, mainly maintaining and troubleshooting existing pipelines

- Node.js Developer at Future-Processing (11.2019 – 03.2022)
  - Developed backend services and REST APIs in Node.js using Hapi.js, with extensive unit testing in Mocha and Sinon.
  - Refactored a large AWS Lambda responsible for subscription-specific newsletter logic, replacing a long switch-based implementation with a strategy-style design to make the code smaller and easier to maintain.
  - Migrated the newsletter logic incrementally, one subscription flow at a time, using a strangler-style approach instead of a big-bang rewrite.
  - Worked as part of the team building and maintaining an Elasticsearch-based search module, including indexing and application-side search logic.
  - Built and maintained serverless components using AWS Lambda, SQS, DynamoDB, SES and PostgreSQL, with CloudWatch Logs used heavily for debugging and production troubleshooting.
  - Investigated messages landing in SQS dead-letter queues, traced processing failures and supported recovery/reprocessing of failed messages.
  - Worked with Serverless Framework, some Terraform and GitLab CI to manage deployment and infrastructure-related parts of the applications.

- Software Developer at NGK Ceramics (03.2018 - 11.2019)
  - Developed and maintained internal manufacturing applications using C#, ASP.NET MVC and Oracle, supporting production and quality-control processes on the factory floor.
  - Built applications integrating production systems with factory-floor equipment, including barcode readers and devices used directly on production lines.
  - Developed a production-line application automatically displaying product-specific packing plans and work instructions based on the currently manufactured product.

- Software Developer at Rescop (05.2014 - 02.2018)
  - Developed and maintained web applications using C#, ASP.NET Web Forms and SQL Server, including systems generating business documents from user-submitted forms.
  - Worked extensively with SQL queries and application-side data processing.
  - Supported manual application deployments and configuration on IIS.

## New Skills
### Cloud & Infrastructure
AWS: EC2, ECS/Fargate, RDS/Aurora, Lambda, S3, SQS, SNS, SES, Cognito, IAM, CloudWatch, CloudTrail, Auto Scaling
Docker, Linux

### Infrastructure as Code & Automation
Terraform, Ansible, Bash

### CI/CD
Azure DevOps pipelines, GitLab CI, GitHub Actions

### Observability
CloudWatch, Grafana, ELK / Elasticsearch

### Development
Node.js, TypeScript, C#, .NET, REST APIs

### Databases
PostgreSQL, DynamoDB, SQL Server, Oracle

### Additional
Kubernetes / k3s

## Personal hobby projects
- Running self-hosted infrastructure using k3s, running multiple containerized services using Kubernetes and Docker Compose.
- Automating host preparation and service configuration using Ansible with CI validation for Ansible playbooks and Kubernetes manifests.
- Using Cloudflare Tunnel to securely expose self-hosted services to the internet without opening inbound ports.

## Education
- Silesian University of Technology – Mechanical Engineering (MSc)
- Silesian University of Technology – Biomedical Engineering (BSc)
