# Edge Computing System Simulation

This project models and simulates a multi-layer IoT edge computing architecture using queueing theory and stochastic processes.

The system consists of:

- Edge Servers (finite queue M/M/1/K model)
- Collecting Servers
- Main Server

The goal is to analyze system performance and optimize processing rate (μ).

---

## 📌 Project Objectives

- Model edge server as M/M/1/K queue
- Simulate job arrivals (Poisson process)
- Simulate service time (Exponential distribution)
- Compute:
  - Average queue length
  - Job loss probability
  - Throughput
  - Return rate (p)
- Compare theoretical modeling vs simulation
- Optimize μ to minimize total system cost

---

## ⚙️ System Architecture

IoT Sensors → Edge Servers → Collecting Servers → Main Server

- Jobs arrive at rate λ
- Processed at rate μ
- Return probability p
- Queue capacity k

---

## 📊 Optimization Problem

We minimize total system cost:

Total Cost = (A × Lost Jobs) + (B × Returned Jobs)

The optimal μ is found under different cost conditions:
- A > B
- B > A
- A = B



## 📁 Repository Structure

