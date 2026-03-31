# 10 – Denial of Service ⚡

## 📌 Lab Overview

This module focuses on Denial of Service (DoS) and Distributed Denial of Service (DDoS) attacks, which aim to disrupt the availability of systems, networks, or services.

Various tools and techniques were used to simulate resource exhaustion and service disruption in a controlled lab environment.

---

## 🎯 Objectives

- Understand DoS and DDoS attack mechanisms  
- Simulate network and application-level DoS attacks  
- Analyze resource exhaustion techniques  
- Evaluate service disruption impact  
- Understand mitigation strategies  

---

## 🧠 How DoS Attacks Work

- **Overload** – Flooding the target with excessive traffic  
- **Resource Exhaustion** – Consuming CPU, memory, or bandwidth  
- **Service Disruption** – Making services unavailable to legitimate users  

---

## 🌐 How DDoS Attacks Work

- **Compromised Devices** – Multiple infected systems (botnets)  
- **Coordinated Flood** – Simultaneous attack from multiple sources  
- **Resource Depletion** – Exhausting system/network capacity  

---

## 🛠 Tools Used

- Metasploit Framework  
- hping3  
- Raven Storm  
- Slowloris  
- LOIC (Low Orbit Ion Cannon)  
- macof  
- Kali Linux  

---

## 🔍 Methodology

### 💣 DoS/DDoS using Metasploit

Metasploit modules were used to simulate denial-of-service conditions.

Purpose:

- Exploit service vulnerabilities  
- Generate controlled attack traffic  

---

### ⚡ DoS/DDoS using hping3

** hping3 --flood -S -p 80 (IP Address) **

Used to:

- Generate SYN flood attacks  
- Overwhelm target network stack  

---

### 🌪 DoS/DDoS using Raven Storm

Raven Storm was used to simulate high-volume traffic attacks.

Impact:

- Bandwidth saturation  
- Service degradation  

---

### 🐌 DoS Attack using Slowloris

Slowloris targeted web servers by keeping connections open.

Effect:

- Exhaust server connection pool  
- Deny access to legitimate users  

---

### 🔫 DoS/DDoS using LOIC

LOIC was used to generate high traffic requests toward the target.

Impact:

- Server overload  
- Resource exhaustion  

---

### 🔄 MAC Flooding using macof

** macof -i eth0 **

Used to:

- Flood switch CAM table  
- Disrupt network traffic handling  

---

## 📊 Findings

- Successfully simulated service disruption scenarios  
- Observed resource exhaustion effects  
- Identified network instability under high traffic load  
- Demonstrated impact of application-layer attacks (Slowloris)  

---

## ⚠️ Risk Analysis

DoS/DDoS attacks may lead to:

- Service unavailability  
- Business downtime  
- Financial loss  
- Reputation damage  
- Network congestion  

Critical services are highly vulnerable to availability attacks.

---

## 🛡 Mitigation Recommendations

- Implement rate limiting  
- Use firewalls and intrusion prevention systems  
- Deploy DDoS protection services  
- Monitor abnormal traffic patterns  
- Use load balancing and redundancy  
- Harden server configurations  

---

## 📝 Lab Outcome

Developed practical understanding of denial-of-service attack techniques, resource exhaustion methods, and defensive strategies to maintain service availability in networked environments.
