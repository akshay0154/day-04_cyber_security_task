# 🔐 Task 4: Setup and Use a Firewall on Linux (UFW)

## 🎯 Objective:
Configure and test basic firewall rules to allow or block traffic using UFW (Uncomplicated Firewall) on Linux.

---

## ⚙️ Steps Followed:

### 1. Enabled UFW:
 ufw enable

### 2. block port no. 22
 ufw deny 22

### 3. allow a port no 23
 ufw allow 23
 
### 4. show the status 
 ufw numbered
 
### 5. delete a block port no 22
 ufw delete deny 22


## Summarize

A firewall acts like a security guard between your computer and the internet. It filters network traffic based on rules — allowing or blocking data packets depending on port numbers, IP addresses, or protocols.

For example:

If a rule says "deny port 22", any data trying to use that port is blocked.

If a rule says "allow port 23", data through that port is permitted.

