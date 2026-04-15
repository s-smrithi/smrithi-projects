# ☁️ AWS Disaster Recovery and Failover Architecture

## 📌 Project Overview
This project focuses on designing and implementing a **Disaster Recovery (DR) solution on AWS** to ensure high availability and business continuity.  
The system is built to automatically failover to a secondary region during failures.

---

## 🎯 Objectives
- Ensure high availability of applications  
- Minimize downtime during failures  
- Implement automated backup and recovery  
- Enable DNS failover using Route 53  

---

## 🛠️ AWS Services Used
- EC2 (Elastic Compute Cloud)  
- S3 (Simple Storage Service)  
- AWS Backup  
- Route 53  
- CloudWatch  

---

## 🏗️ Architecture Design
- Primary Region (Main Application Server)  
- Secondary Region (Backup Server)  
- Data stored in S3 with backup enabled  
- Route 53 used for DNS routing and failover  
- Health checks configured to monitor application status  

---

## 🔁 Disaster Recovery Strategy
- Regular backups using AWS Backup  
- Data replication to secondary region  
- Standby EC2 instance in secondary region  
- Automatic failover using Route 53 health checks  

---

## ⚙️ Implementation Steps
1. Launch EC2 instances in primary and secondary regions  
2. Configure application in primary instance  
3. Store data in S3 and enable backup  
4. Configure AWS Backup plans and policies  
5. Set up Route 53 hosted zone  
6. Configure health checks for primary server  
7. Enable DNS failover to secondary server  
8. Monitor using CloudWatch  

---

## 🧪 Testing & Validation
- Simulated failure of primary server  
- Verified automatic failover to secondary region  
- Tested DNS routing and application accessibility  

---

## 📊 Results
- Achieved high availability  
- Reduced downtime during failures  
- Ensured reliable backup and recovery  

---

## 📁 Files Included
- Architecture diagram  
- Configuration screenshots  
- Deployment steps  

---

## 🚀 Conclusion
This project demonstrates how AWS services can be used to build a **robust disaster recovery system** with automatic failover and minimal downtime.

---

## 📫 Contact
- Email: smrithi06.s@gmail.com  
- GitHub:https://github.com/s-smrithi  

---

⭐ *This project showcases practical implementation of cloud reliability and disaster recovery on AWS*
