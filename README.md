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
<img width="1919" height="960" alt="website-homepage " src="https://github.com/user-attachments/assets/0f56ded2-06e2-41b0-9b4f-f40653a9f751" />


---

### GitHub Actions Success

<img width="1919" height="809" alt="github-actions-success" src="https://github.com/user-attachments/assets/16123cb3-e8b6-4fa4-90f4-25c8807a466d" />


### EC2 Instance

<img width="1919" height="975" alt="ec2-instance" src="https://github.com/user-attachments/assets/f5207be5-49f5-4d53-9f4e-3326a68c7bf5" />

## 🚀 Deployment

Deployment is fully automated using GitHub Actions.

Every push to the **main** branch triggers the deployment workflow automatically.


---

## 👩‍💻 Author

**Snehal Awasare**

Aspiring AWS & DevOps Engineer

GitHub:
https://github.com/awasaresnehal
