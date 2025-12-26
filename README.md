# Hybrid NSGA-III and PPO for Energy-Efficient and Adaptive Controller Placement in SDN

## 📖 Project Description
This project develops a hybrid optimization framework for Software-Defined Networking (SDN) controller placement. It combines:
- **NSGA-III** for offline multi-objective optimization, and
- **PPO (Proximal Policy Optimization)** for real-time dynamic adaptation.

The optimization focuses on minimizing:
- Control latency
- Total energy consumption
- Controller load variance

## 🚀 Technologies Used
- Python 3.10+
- NetworkX
- Pymoo
- Stable-Baselines3
- Folium
- Matplotlib, Seaborn

## 🛠️ Key Features
- Offline NSGA-III optimization to generate Pareto-optimal controller placements.
- Online PPO reinforcement learning to adapt controller placement dynamically.
- Interactive Folium maps for network visualization.
- Modern graphs for performance comparison (latency, energy, load variance).

## 📦 Project Structure
```bash
📦 project-name/
├── dataset/            # Topology files
├── src/                # Source code (NSGA-III, PPO, visualization)
├── outputs/            # Generated maps and graphs
├── README.md           # Project documentation
├── requirements.txt    # Python dependencies
└── LICENSE             # (Optional) Project license
```
## ⚡ How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/sdn-controller-placement.git
cd sdn-controller-placement
```
