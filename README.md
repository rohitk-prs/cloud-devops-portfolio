\# Cloud DevOps Portfolio



A hands-on Cloud and DevOps project built and deployed using Git, GitHub, Docker, AWS EC2, Amazon ECR, GitHub Actions and AWS Systems Manager.



\## 🚀 Project Overview



This project demonstrates an end-to-end DevOps workflow starting from source code version control and progressing to containerization, cloud deployment and automated CI/CD.



\## 🏗 Architecture



Developer

↓

Git

↓

GitHub

↓

GitHub Actions

↓

Docker Image Build

↓

Amazon ECR

↓

AWS Systems Manager

↓

Amazon EC2

↓

Docker Container

↓

Live Website



\## ✅ Phase 1 - Git \& GitHub



\- Created a portfolio website using HTML and CSS

\- Initialized a Git repository

\- Used Git staging and commits

\- Created feature branches

\- Created and merged a Pull Request

\- Connected local Git repository with GitHub

\- Pushed source code to GitHub

\- Hosted the website using GitHub Pages



\## ✅ Phase 2 - Docker \& AWS EC2



\- Created a Dockerfile using Nginx

\- Built a Docker image locally

\- Ran the website inside a Docker container

\- Used port mapping to access the container

\- Launched an Amazon Linux EC2 instance

\- Configured Security Group rules for SSH and HTTP

\- Installed Git and Docker on EC2

\- Cloned the GitHub repository on EC2

\- Built and ran the Docker container on AWS EC2

\- Successfully accessed the website using the EC2 Public IP



\## ✅ Phase 3 - CI/CD Automation



\- Created a private Amazon ECR repository

\- Configured GitHub Actions with AWS using OIDC

\- Created IAM roles using least-privilege permissions

\- Configured AWS Systems Manager for EC2 deployment

\- Created a GitHub Actions workflow

\- Automatically built Docker images after code push

\- Automatically pushed Docker images to Amazon ECR

\- Automatically deployed the latest Docker image to EC2

\- Verified automatic website updates without manually connecting to EC2



\## 🔄 CI/CD Workflow



Code Change

↓

Git Commit

↓

Git Push

↓

GitHub Actions

↓

AWS Authentication using OIDC

↓

Docker Image Build

↓

Push Image to Amazon ECR

↓

AWS Systems Manager Command

↓

EC2 Pulls Latest Docker Image

↓

Old Container Replaced

↓

Updated Website Live



\## 🛠 Technologies Used



\- AWS EC2

\- Amazon ECR

\- AWS IAM

\- AWS Systems Manager

\- Git

\- GitHub

\- GitHub Actions

\- Docker

\- Nginx

\- Linux

\- HTML

\- CSS

\- CI/CD



\## 📁 Project Structure



cloud-devops-portfolio/

├── index.html

├── style.css

├── Dockerfile

├── README.md

└── .github/

&#x20;   └── workflows/

&#x20;       └── deploy.yml



\## 🔐 Security



\- GitHub Actions authenticates with AWS using OIDC

\- No permanent AWS access keys are stored in GitHub

\- IAM roles are used for AWS permissions

\- EC2 deployment commands are sent through AWS Systems Manager



\## 🌐 Live Demo



GitHub Pages:

https://rohitk-prs.github.io/cloud-devops-portfolio/



\## 💻 GitHub Repository



https://github.com/rohitk-prs/cloud-devops-portfolio



\## 🎯 Final Result



A code change pushed to the main branch automatically triggers the CI/CD pipeline, builds a new Docker image, pushes it to Amazon ECR and deploys the updated container to AWS EC2.



This project demonstrates practical experience with version control, containerization, AWS cloud infrastructure and CI/CD automation.

