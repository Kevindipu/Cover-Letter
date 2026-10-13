# Kevin Thomas Dipu

kevindipu17@gmail.com | Germany | [LinkedIn](URL) | [GitHub](URL) | Student residence permit (§ 16b)
Available immediately

## Summary

Data Analytics Master's student at Universität Hildesheim with 2 years of experience at Qualcomm building Python automation and Splunk dashboards. Hands-on with AWS, Terraform and Docker through personal projects. Seeking a DevOps/Cloud Werkstudent role (up to 20 hours per week).

## Education

**Master of Science in Data Analytics**, *University of Hildesheim* — 04/2026 – Present, Hildesheim

**B.E in Computer Science and Engineering**, *JSS Science and Technology University* — 12/2020 – 06/2024, Mysuru, India
- GPA: 1.7

## Professional Experience

### IT Engineer, Qualcomm — 07/2024 – 03/2026, Bengaluru, India
- Saved **8+ hours of manual work per week** by building a Python pipeline that cleans data from an internal tool, stores metrics in MongoDB and shows validation results on Splunk dashboards for the chip design intellectual property (IP) management system.
- Cut developer setup time **from 60 to 15 minutes** by building QPI, a Python CLI tool with **30+ commands** to automate Git, Perforce and Swarm workspace setup, earning the QSparkler Award as 1 of 5 engineers selected from a 120-person team.
- Improved server data accuracy by **15%** across **500+ servers** by writing a Python script that finds mismatches between records, shows them on a Splunk dashboard and emails machine owners to fix them.

### Interim Engineering Intern, Qualcomm — 01/2024 – 07/2024, Bengaluru, India
- Freed up **20% of software license capacity** across **4 environments** by building an automated Python usage-tracking system for **50+ users**.
- Cut weekly manual reporting effort by **40%** by building a MongoDB-backed metrics dashboard and Python reporting pipeline for **100+ chip IP records**, replacing manual portal searches for the project manager's director-level reports.

## Projects

### URL Shortener on AWS | [GitHub](URL)
*Tech Stack: Python, FastAPI, Docker, Terraform, GitHub Actions, AWS*
- Automated deployment with GitHub Actions, so a single git push goes live in **about 90 seconds**. The pipeline builds the Docker image, pushes it to ECR and deploys to 2 EC2 instances with a health check after each.
- Made the AWS setup repeatable with Terraform. The full stack (VPC, ALB, 2 EC2, RDS, ECR, IAM, CloudWatch) comes up from one terraform apply in **about 4 minutes**.
- Removed the single point of failure by running the FastAPI app on 2 EC2 instances behind a load balancer with a shared PostgreSQL (RDS) database. Added **4 CloudWatch alarms** that send email alerts through SNS.

### Multimodal Deepfake Content Detection | [GitHub](URL)
*Tech Stack: Deep learning, CV, Image processing, NLP, Audio & signal processing*
- Built an end-to-end **multimodal deepfake detection** framework for text, image and audio using TensorFlow and PyTorch, integrating all models into a unified Flask REST API backend.
- Reached **93.7% test accuracy** on image deepfake classification by combining **VGG19** feature extraction with NewNet.
- Achieved **95.1% accuracy** on audio deepfake classification by extracting MFCC features and training a VGGish model.
- Classified LLM-generated text with **84.3% accuracy** by fine-tuning BERT and building lexical pipelines (MAAS, Yule's K).

## Skills

- **DevOps & Cloud:** AWS, Docker, Kubernetes, Terraform, GitHub Actions, CI/CD, Linux, Git
- **Programming & Databases:** Python, Bash, SQL, PostgreSQL, MongoDB
- **Monitoring & Data:** Splunk, ETL pipelines, REST APIs (FastAPI, Flask)
- **Machine Learning:** PyTorch, TensorFlow, BERT, Computer Vision

## Languages

- **English:** C1
- **German:** A2
