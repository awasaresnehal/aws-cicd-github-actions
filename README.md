# 🚀 CI/CD Pipeline using GitHub Actions and AWS EC2

## 📌 Project Overview

This project demonstrates an automated CI/CD pipeline that deploys a static website from GitHub to an AWS EC2 Ubuntu server using GitHub Actions.

Whenever code is pushed to the **main** branch, GitHub Actions automatically:

- Copies website files to EC2
- Deploys them to Apache Web Server
- Restarts Apache
- Makes the latest version available instantly

## 🛠 Technologies Used

- AWS EC2 (Ubuntu 24.04)
- Git
- GitHub
- GitHub Actions
- Apache2
- HTML5
- CSS3
- SSH

## ⚙️ CI/CD Workflow

1. Developer updates code in VS Code
2. Code pushed to GitHub
3. GitHub Actions starts automatically
4. Files copied securely to EC2 using SSH
5. Apache serves the updated website

## 📂 Project Structure

```
aws-cicd-github-actions/
│
├── .github/
│   └── workflows/
│       └── deploy.yml
├── screenshots/
├── index.html
├── style.css
└── README.md
```
## 📸 Project Screenshots

### Website

![Website](screenshots/website-homepage.png)

---

### GitHub Actions Success

![GitHub Actions](screenshots/github-actions-success.png)

---

### EC2 Instance

![EC2](screenshots/ec2-instance.png)

---

## 🚀 Deployment

Deployment is fully automated using GitHub Actions.

Every push to the **main** branch triggers the deployment workflow automatically.

---

## 👩‍💻 Author

**Snehal Awasare**

Aspiring AWS & DevOps Engineer

GitHub:
https://github.com/awasaresnehal
