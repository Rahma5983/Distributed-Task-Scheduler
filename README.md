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
pip install fastapi uvicorn requests

### 2. Start Workers
uvicorn worker:app --port 8001 uvicorn worker:app --port 8002

### 3. Start Master
uvicorn master:app --port 8000

### 4. Run Client
python client.py

---

## 📊 Example Output

- Tasks are queued
- Assigned to least loaded worker
- Retries happen if worker fails

---

## 🧠 Concepts Used

- Distributed Systems
- Load Balancing Algorithms
- Fault Tolerance
- System Design
- REST APIs

---

## 📌 Future Improvements

- Docker-based deployment
- Real-time monitoring dashboard
- Priority-based scheduling

---

## 🔬 Learning Outcome
This project helped in understanding:
- Distributed system design
- Load balancing strategies
- Fault tolerance mechanisms

---

## 👩‍💻 Author

Rahma Naqui
