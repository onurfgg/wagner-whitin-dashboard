# 📦 Industrial Engineering Dashboard: Wagner-Whitin & EOQ Optimizer

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Operations Research](https://img.shields.io/badge/Operations%20Research-Optimization-success)

A modern, interactive web-based Decision Support System (DSS) designed to solve complex dynamic inventory problems. This dashboard applies the **Wagner-Whitin Dynamic Programming Algorithm** to find the absolute optimal order plan for varying demands, while comparing it seamlessly with classical **EOQ (Economic Order Quantity)** calculations.

[🚀 **Click Here for Live Demo**](https://onurfgg.github.io/wagner-whitin-dashboard/) 

## ✨ Key Features

* **Real-Time Dynamic Programming:** Instantly generates the optimal cost matrix and backtracks the exact periods to place orders.
* **EOQ vs. WW Analysis:** Automatically calculates the theoretical EOQ based on average demand and contrasts it with the dynamic WW approach to highlight cost inefficiencies of static models.
* **Interactive Demand Visualization:** Dynamic bar charts that adapt instantly as users input or modify periodic demands.
* **Glassmorphism UI/UX:** A highly polished, dark-themed, and responsive interface inspired by modern FinTech and analytics dashboards.
* **Mathematical Rendering:** Integrates KaTeX to elegantly render operations research formulas natively in the browser.

## 🧮 Mathematical Background

The Wagner-Whitin algorithm balances setup costs ($S$) and holding costs ($h$) over a planning horizon of $N$ periods to minimize the total cost ($Z$). The dynamic programming recursion is defined as:

$$Z_t = \min_{1 \le j \le t} \left[ Z_{j-1} + S + \sum_{k=j}^{t} h \cdot D_k \cdot (k-j) \right]$$

Where:
* $Z_t$: Minimum total cost for periods 1 through $t$
* $S$: Setup / Ordering Cost
* $h$: Holding Cost per unit per period
* $D_k$: Demand in period $k$

While **EOQ** assumes constant demand, this dashboard proves how dynamic programming flawlessly handles volatile demand environments without heuristic approximations.

## 🛠️ Installation & Usage

This project is 100% frontend-based. No Node.js backend, no complex build tools, and no dependencies to install.

1. Clone the repository:
   ```bash
   git clone [https://github.com/onurfgg/ie-inventory-optimizer.git](https://github.com/onurfgg/ie-inventory-optimizer.git)


Onur Furkan Gök

[Linkedin](https://www.linkedin.com/in/onurfurkan/) 
[GitHub](https://github.com/onurfgg) 

