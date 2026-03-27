# Distributed Task Scheduler 🚀

## 📌 Overview
This project is a distributed task scheduling system that simulates a multi-node environment. It efficiently assigns tasks to worker nodes using load balancing and ensures system reliability through fault tolerance and retry mechanisms.

---

## ⚙️ Features

- 🔄 Task Queue System
- ⚖️ Dynamic Load Balancing (Least Loaded Worker)
- 💥 Fault Tolerance (Retry on Failure)
- 🧠 Multi-Worker Simulation
- 📡 REST API Communication

---

## 🏗️ Architecture

Client → Master (Scheduler) → Workers

- **Master Node**: Handles scheduling and task distribution
- **Worker Nodes**: Execute tasks and report load

---

## 🚀 How to Run

### 1. Install dependencies
