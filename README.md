# 🚗⚡ Cost Analysis: Electric Cars vs Gasoline Cars (Python)

This project analyzes and compares the **Total Cost of Ownership (TCO)** of **electric cars** and **gasoline cars**, using **Python** for data processing and visualization.

The goal is to understand **which option is more cost-effective** in the medium to long term, considering not only the purchase price, but also energy/fuel costs, maintenance, and government incentives.

---

## 📌 Project Goals

* Compare **initial costs** (purchase price + incentives)
* Analyze **annual operating costs**
* Estimate **total cost over multiple years**
* Visualize differences using **charts**
* Provide a flexible data model for future simulations

---

## 📊 Dataset & Assumptions

The main variables used in the analysis are:

* Average price of electric cars
* Average price of gasoline cars
* Electricity cost (€/kWh)
* Fuel cost (€/liter)
* Average consumption (kWh/100km – km/l)
* Annual mileage
* Maintenance costs
* Government incentives

> ⚠️ All values are **estimated** and can be easily modified in the code.

---

## 🧮 Methodology

1. Definition of economic parameters
2. Calculation of annual operating costs
3. Cumulative cost calculation over *n* years
4. Final comparison using a DataFrame
5. Data visualization

---

## 🐍 Technologies Used

* **Python 3**
* **Pandas** – data manipulation
* **Matplotlib** – data visualization
* **NumPy** – numerical computations

---

## 🧑‍💻 Code Example (snippet)

```python
import pandas as pd

costs = {
    "Car Type": ["Electric", "Gasoline"],
    "Annual Cost": [450, 1200]
}

df = pd.DataFrame(costs)
print(df)
```

---

## 📂 Project Structure

```
📦 auto-cost-analysis
 ┣ 📂 images
 ┃ ┣ 📊 costo_totale_10_anni.png
 ┃ ┗ 📊 costo_annuale.png
 ┣ 📜 analysis.py
 ┣ 📜 requirements.txt
 ┗ 📜 README.md
```

---

## ✅ Key Findings

* Electric cars generally have a **higher initial cost**
* **Operating costs** are significantly lower for electric cars
* The **break-even point** is reached after several years of usage

---

## 🔮 Future Improvements

* Add multiple car models
* Simulate fuel and electricity price variations
* Build an interactive dashboard (Streamlit)
* Integrate real-world data from external sources

---

## 👤 Author

**Gabriele Rumi**
Computer Science Student | Data Engineering

---

📬 *Feedback and suggestions are welcome!*
