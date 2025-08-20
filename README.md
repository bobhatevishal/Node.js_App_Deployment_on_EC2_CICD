# 🚀 Node.js App Deployment on AWS EC2 with CI/CD Pipeline (Jenkins + GitHub)

This project demonstrates how to deploy a **Node.js application** on **AWS EC2** and automate the deployment process using a **CI/CD pipeline** with Jenkins and GitHub.  

---

## 📌 Project Overview

- Developed and deployed a simple **Node.js application** on AWS EC2.  
- Configured a **Jenkins CI/CD pipeline** integrated with GitHub Webhooks.  
- Automated build, test, and deployment stages to ensure **seamless delivery**.  
- Ensured that every code push to GitHub automatically triggered deployment on EC2.  

---

## 🛠️ Tools & Technologies Used

- **Cloud**: AWS EC2  
- **CI/CD**: Jenkins, GitHub Webhooks  
- **Version Control**: Git, GitHub  
- **OS**: Ubuntu (Linux Administration)  
- **Programming**: Node.js (JavaScript)  
- **Process Manager**: PM2 / systemd  

flowchart LR
A[Developer Pushes Code to GitHub] 
B --> B[GitHub Webhook Triggers Jenkins]
B --> C[Jenkins Pipeline Runs]
C --> D[Build & Test Node.js App]
D --> E[Deploy to AWS EC2]
E --> F[Application Running on EC2]

http\://<EC2-Public-IP>:3000


## ✅ Output

When you hit the EC2 public IP on port 3000, you should see:  

<img width="1901" height="965" alt="console_output" src="https://github.com/user-attachments/assets/9b955c3f-8fa8-4eeb-9baa-a7042ec45216" />


Hello World from Node.js on EC2 with CI/CD!


## 📸 Screenshots
- GitHub Webhook Trigger  
  <img width="1883" height="848" alt="webhook" src="https://github.com/user-attachments/assets/f8d6fe50-c157-4fbd-87ae-2f638015265f" />
  
- Jenkins Pipeline Success  
  <img width="1919" height="986" alt="pipeline_overview" src="https://github.com/user-attachments/assets/79ea404b-6b4f-4933-a05e-fa3cbbd26a42" />

- EC2 Application Running  
  <img width="1545" height="427" alt="webpage" src="https://github.com/user-attachments/assets/6a7322e8-8817-4eb2-9a3a-4efa7e7013fc" />

## 📜 Learnings

- Setting up **end-to-end CI/CD pipelines**.  
- Automating deployments to cloud environments.  
- Managing Node.js applications on Linux servers.  
- Understanding DevOps workflow: **Code → Build → Test → Deploy → Run**.  

## 👤 Author

**Vishal Bobhate**  
- 🌐 [LinkedIn](https://www.linkedin.com/in/vishal-bobhate-61820022b)  
- 💻 [GitHub](https://github.com/bobhatevishal)  
- 📧 bobhatev13@gmail.com  
```

