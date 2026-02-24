<h1 align="center">AWS Network Connectivity Project</h1>

<p align="center">
  <strong>Hands-on lab exploring how resources communicate across AWS networks</strong><br>
  VPCs • Subnets • Routing • Connectivity • Traffic Flow
</p>

---

## 🚀 Overview

This project focuses on **AWS network connectivity** — how resources in different parts of a cloud environment communicate with each other.  
It builds on core AWS networking concepts and explores how routing, subnets, and connectivity options affect traffic flow.

The goal of this lab is to understand:

- How traffic moves between subnets and VPCs  
- How routing decisions are made  
- How connectivity impacts availability and security  

This project is part of my **Cloud / DevOps / DevSecOps learning journey**.

---

## 🧠 Key Concepts

In this project, I worked with:

- **VPCs and Subnets** – Isolated networks and IP ranges  
- **Route Tables** – How AWS decides where to send traffic  
- **Connectivity Paths** – How resources reach each other across networks  
- **Security Layers** – How Security Groups and NACLs affect connectivity  

---

## 🛠️ What I Built

### 1. VPC and Subnet Layout

- Created one VPCs with defined CIDR blocks  
- Configured public and/or private subnets  
- Ensured non-overlapping IP ranges for clean routing  

### 2. Route Tables and Routes

- Created and associated route tables with subnets  
- Added routes to direct traffic between networks  
- Verified that traffic followed the expected paths  

### 3. Connectivity Testing

- Deployed test resources (e.g., EC2 instances) in different subnets  
- Used ping, curl, or similar tools to test connectivity  
- Observed how routing and security rules impacted communication  

### 4. Security Controls

- Reviewed Security Group rules  
- Reviewed Network ACL rules  
- Confirmed how they allowed or blocked traffic between resources  

---

## 🌍 Traffic Flow & Connectivity

This project helped me understand:

- How AWS decides where to send packets  
- Why some resources can talk to each other and others cannot  
- How misconfigured routes or security rules can break connectivity  

I practiced reading and reasoning about:

- Route tables  
- Subnet associations  
- Allowed/denied traffic paths  

---

## 🧩 What I Learned

- Connectivity is not just “up or down”—it’s the result of **routing + security**  
- Even if routing is correct, Security Groups or NACLs can still block traffic  
- Good network design requires planning IP ranges, routes, and security together  

---


## 📸 Screenshots

Screenshots are stored in the `screenshots/` folder.

Suggested files:

- `screenshots/vpc-layout.png` – VPC and subnet layout  
- `screenshots/route-tables.png` – Route table configuration  
- `screenshots/connectivity-test.png` – Successful connectivity test  
- `screenshots/security-rules.png` – Security Group / NACL rules  

You can embed one like this:


'[Route Tables](screenshots/route-tables.png)'
