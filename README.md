# 🏫 Binus Campus Network Simulation

This project simulates a comprehensive **computer network infrastructure** for multiple floors in a building at **Binus University**. It is built using **Cisco Packet Tracer** and implements essential networking concepts like **IP Addressing**, **Subnetting with VLSM**, **Static Routing**, **DHCP Server**, and **Web Server** configuration.

---

## 📌 Project Overview

### 🏢 Building Structure (Simulated Floors)
The network is divided into **three major subnet zones**, each representing a floor in the campus:

- **Level 1 (Yellow)**: 192.168.1.0/24  
- **Level 6 (Green)**: 192.168.6.0/24  
- **Level 3 (Blue)**: 192.168.3.0/24  

Each floor is connected via a router using **static routing**, and further divided using **VLSM (Variable Length Subnet Masking)** to optimize IP address allocation.

---

## 🧠 Key Technologies & Concepts

### ✅ IP Addressing & Subnetting
- Implemented **Class C addressing**
- Used **VLSM** to allocate subnets efficiently across different departments/floors

### 🔁 Static Routing
- Routers configured manually with static routes to communicate between subnets

### 🌐 DHCP Server
- Central DHCP Server to dynamically assign IP addresses to selected hosts

### 💻 Web Server
- Configured web server accessible by devices across all subnets

---

## 🖥️ Devices Used

- **Routers** (Layer 3)
- **Switches** (Layer 2)
- **PCs** (for various departments)
- **DHCP Server**
- **Web Server**

---

## 📡 Network Topology

- The diagram shows hierarchical connectivity between floors
- Each switch connects multiple department PCs
- Routers ensure inter-floor communication
- Color-coded areas:
  - 🟨 Yellow – Level 1
  - 🟩 Green – Level 6
  - 🟦 Blue – Level 3

