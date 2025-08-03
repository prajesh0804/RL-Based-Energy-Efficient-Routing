# RL-Based Energy-Efficient Routing for Wireless Sensor Networks

Routing algorithms play a crucial role in determining efficient paths for data transmission in **Wireless Sensor Networks (WSNs)**, which are commonly deployed in energy-constrained environments. With the expansion of **IoT**, **smart cities**, and **environmental monitoring** applications, energy conservation has become critical to ensure long-term and reliable network operations.

## ❗ Problem Statement

Designing effective routing protocols for WSNs is challenging due to the need to:
- Minimize energy consumption.
- Maintain performance in terms of **latency**, **throughput**, and **reliability**.
- Adapt to dynamic network conditions.

Traditional routing approaches like **LEACH**, **PEGASIS**, and **DEAR** focus on energy efficiency using clustering, chain-based transmission, or distance-aware strategies. However, they often suffer from:
- Uneven energy depletion.
- Static role assignment.
- Limited adaptability.

These limitations can cause premature node failures and reduce overall network lifetime.

## 🚀 Proposed Solution

This project proposes a **Reinforcement Learning (Q-Learning)** based routing protocol that dynamically adapts to network conditions to improve energy efficiency and sustainability.

### 🔑 Key Features
- **Energy-aware decision-making** using node residual energy and distance to the sink.
- **Adaptive routing** to handle topology changes and balance energy consumption.
- **Cluster-based communication** for load distribution.
- **Performance benchmarking** against standard protocols: `LEACH`, `PEGASIS`, `DEAR`, `RLBR`, and `DADF`.

## 🎯 Objectives
1. Develop an energy-aware routing protocol that **minimizes total energy consumption**.
2. Improve **network sustainability** through **adaptive and balanced routing decisions**.

## 📈 Results
- Achieved **24.6% longer network lifetime** and up to **19.8% lower peak energy usage** compared to DEAR and RLBR.
- Maintained stable performance for **5600+ simulation rounds**, outperforming RLBR which collapsed before 4500 rounds.

## 🛠️ Tech Stack
- **Language**: Python
- **Libraries**: TensorFlow, NumPy, Matplotlib

## 📁 Project Structure
