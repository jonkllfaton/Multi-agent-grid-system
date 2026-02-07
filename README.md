
[![Top Language](https://img.shields.io/badge/Top%20Language-Python-blue?style=for-the-badge\&logo=python\&logoColor=white)](https://github.com/jonkllfaton/Agent-based-market-simulator)
[![Stars](https://img.shields.io/badge/Stars-⭐-brightgreen?style=for-the-badge)](https://github.com/jonkllfaton/Agent-based-market-simulator/stargazers)
[![Forks](https://img.shields.io/badge/Forks-🔀-blue?style=for-the-badge)](https://github.com/jonkllfaton/Agent-based-market-simulator/network/members)
[![Issues](https://img.shields.io/badge/Issues-❗-red?style=for-the-badge)](https://github.com/jonkllfaton/Agent-based-market-simulator/issues)
[![Last Commit](https://img.shields.io/badge/Last%20Commit-📅-orange?style=for-the-badge)](https://github.com/jonkllfaton/Agent-based-market-simulator/commits/main)
[![Contributors](https://img.shields.io/badge/Contributors-👥-purple?style=for-the-badge)](https://github.com/jonkllfaton/Agent-based-market-simulator/graphs/contributors)

---

# 🐝 Grid Systems

**Decentralized Resource Allocation Among Autonomous Agents**

[![Python](https://img.shields.io/badge/python-3.8+-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/jonkllfaton/swarmgrid)](https://github.com/jonkllfaton/swarmgrid/stargazers)

Grid Systems is a modular **simulation framework** for decentralized resource allocation in a grid environment. Agents interact, trade, and make independent decisions without a central controller, enabling modeling of cooperation, competition, and emergent behaviors.

---

## 🚀 Features

* **Autonomous Agents** – Agents operate independently using configurable behaviors.
* **Decentralized Resource Exchange** – Peer-to-peer resource management.
* **Multi-Resource Inventory** – Energy, food, compute time, etc.
* **Flexible Scenarios** – Customize agents, distributions, utility models, and interaction rules.
* **Simulation Metrics** – Utility gains, equity, and efficiency tracking.
* **Modular & Extensible** – Add agent types, resources, and communication protocols.
* **Cooperation & Competition** – Model altruistic or selfish strategies.
* **Visualization Tools** – Network flows, heatmaps, and time-series plots.

---

## 🎬 Demo Video

<p align="center">
  <a href="https://youtu.be/urXnRFVPZR8">
    <img width="600" src="https://img.youtube.com/vi/urXnRFVPZR8/maxresdefault.jpg" alt="Grid Systems Demo">
  </a>
</p>

<p align="center">
  <img src="docs/demo_animation.gif" alt="Simulation GIF" width="600"/>
</p>

> Watch the **Grid Systems demo** in action! Click the image above to view the video.

---

## 💻 Installation

```bash
git clone https://github.com/jonkllfaton/swarmgrid.git
cd swarmgrid
pip install -r requirements.txt
```

---

## ⚙️ Usage

Run the default simulation:

```bash
python run_simulation.py
```

Run with a custom configuration file:

```bash
python run_simulation.py --config config.yaml
```

**Customizable in `config.yaml`:**

* Agent types and population size
* Initial resource allocation
* Interaction rules and utility optimization
* Duration, logging, and output formats

---

## 🧩 Agent Types

<p align="center">
  <img src="docs/icons/gatherer.png" width="80" alt="Gatherer"/>
  <img src="docs/icons/allocator.png" width="80" alt="Allocator"/>
  <img src="docs/icons/optimizer.png" width="80" alt="Optimizer"/>
  <img src="docs/icons/balancer.png" width="80" alt="Balancer"/>
  <img src="docs/icons/competitor.png" width="80" alt="Competitor"/>
</p>

| Agent Type     | Behavior Description                            |
| -------------- | ----------------------------------------------- |
| **Gatherer**   | Searches for and collects resources             |
| **Allocator**  | Distributes resources based on utility          |
| **Optimizer**  | Trades resources to maximize efficiency         |
| **Balancer**   | Detects inequalities and redistributes excess   |
| **Competitor** | Prioritizes self-gain and strategic withholding |

---

## 📊 Outputs & Visualization

* **Logs** – Detailed agent transactions and decisions
* **CSV Outputs** – Inventories, resource movement, utility scores
* **Visualizations** –

  * Network graphs
  * Heatmaps
  * Time-series plots

<p align="center">
  <img src="docs/heatmap.png" alt="Resource Heatmap" width="600"/>
</p>

---

## 🤝 Contributing

Contributions are welcome! Submit issues or pull requests following project conventions.

---

## 📝 License & Attribution

© 2025 Jonk L. Faton. All rights reserved.
This project is the intellectual property of Jonk L. Faton. Unauthorized copying, distribution, modification, or use is prohibited.

Contact: **[jonkllfaton@gmail.com](mailto:jonkllfaton@gmail.com)**

---

## ⚡ Technologies

* **Python 3.8+**
* **TypeScript (95%)**
* **JavaScript (4%)**

---
