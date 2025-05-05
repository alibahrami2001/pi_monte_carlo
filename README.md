# π Estimation Using Monte Carlo Simulation

![Monte Carlo Pi Simulation](https://github.com/alibahrami2001/pi_monte_carlo/blob/main/image/monte_carlo_pi.png)

*A probabilistic approach to approximating π with random sampling.*

---

## 📖 Overview
This project estimates the value of **π (pi)** using the **Monte Carlo method**, demonstrating how randomness can solve deterministic problems. The simulation visualizes:
- Convergence of π estimates over iterations.
- Scatter plot of random points inside/outside a unit circle.
- Error analysis and distribution of results.

---

## 🧮 Mathematical Foundation
The method leverages the area ratio between a unit square and a quarter-circle:
- **Area of unit square** = 1
- **Area of quarter-circle** = π/4
- **Ratio of points inside the circle** ≈ π/4 ⇒ **π ≈ 4 × (Points Inside / Total Points)**

---

## 🚀 How It Works
1. **Random Sampling**: Generates points uniformly in [0, 1] × [0, 1].
2. **Classification**: Checks if points lie inside the unit circle (`x² + y² ≤ 1`).
3. **Estimation**: Approximates π using the ratio of successful hits.
4. **Visualization**: Plots convergence, point distribution, and error metrics.

---

## 📊 Key Features
| Feature              | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **Convergence Plot** | Shows how the estimate approaches π as iterations increase.                |
| **Scatter Plot**     | Visualizes the first 1,000 points (blue=inside, red=outside).              |
| **Error Analysis**   | Log-scale error convergence over time.                                     |
| **Histogram**        | Distribution of π estimates across all iterations.                         |

---

## 🛠️ Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/alibahrami2001/pi_monte_carlo.git
   cd pi_monte_carlo
