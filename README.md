# Agentic AI Framework for Dynamic EV Charging Tariff Optimization

## Overview

Developed an Agentic AI framework for EV charging tariff optimization using large-scale charging network data.

The framework consists of:

1. Demand Prediction Agent
2. Congestion Prediction Agent
3. Dynamic Tariff Pricing Agent
4. Monitoring & Learning Agent

The system forecasts charging demand, predicts congestion, recommends adaptive tariffs, and evaluates business performance through continuous monitoring.

---

## Dataset

### UrbanEV Dataset

- 2.12 Million charging observations
- 247 charging zones
- Occupancy data
- Charging volume
- Charging duration
- Dynamic electricity pricing

### Station Information

- Latitude
- Longitude
- Fast chargers
- Slow chargers
- Charger counts

---

## Agents

### Demand Prediction Agent

Predicts:

- Charger Utilization Rate
- Charging Demand (Volume)

Results:

| Target | Metric | Score |
|----------|----------|----------|
| Utilization Rate | R² | 0.943 |
| Charging Volume | R² | 0.994 |

---

### Congestion Prediction Agent

Predicts:

- Congested Stations
- Non-Congested Stations

Results:

| Metric | Value |
|----------|----------|
| Accuracy | 0.995 |
| Precision | 0.996 |
| Recall | 0.995 |
| F1 Score | 0.996 |
| AUC | 0.9999 |

---

### Tariff Pricing Agent

Generates:

- Surge Pricing
- Discount Pricing
- Revenue Optimization

---

### Monitoring & Learning Agent

Tracks:

- Revenue Gain
- Customer Response Rate
- Wait Time Reduction
- Pricing Efficiency

Results:

| Metric | Value |
|----------|----------|
| Revenue Gain | 3.14% |
| Wait Time Reduction | 16.56% |

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- Random Forest
- Matplotlib

---

## Project Structure

data/

outputs/

images/

notebook.ipynb

README.md

---

## Business Impact

The framework demonstrates how AI-driven dynamic pricing can improve charging infrastructure efficiency, reduce congestion, and increase operational revenue.
