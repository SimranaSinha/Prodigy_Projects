# Prodigy_Projects

This repository contains a collection of data science and supply chain analytics projects developed as part of coursework and experimentation using Python and Google Colab.

The focus of these projects is on decision-making, simulation, and the application of Generative AI in real-world scenarios.

---

## 📂 Repository Structure

```
Prodigy_Projects/
│
├── DS_Task_3.ipynb      # Data Science Task 3 (Colab Notebook)
├── DS_Task_4.ipynb      # Data Science Task 4 (Colab Notebook)
├── README.md            # Project documentation
```

---

## 📊 Project Highlights

### 1. Beer Game: Manual vs GenAI-Assisted Planning

This project compares traditional manual decision-making with GenAI-assisted order planning in a supply chain simulation.

#### Key Objectives

* Evaluate stability of ordering decisions
* Analyze inventory fluctuations and backorders
* Compare cost performance between methods

#### Key Findings

* GenAI reduces variability in order quantities and inventory levels
* Manual decisions show higher fluctuation and overcorrection
* GenAI works best as a decision-support tool, not full automation
* Cost is not always lower, but more stable across runs 

---

### 2. Prompt Engineering in Supply Chain Decisions

This project explores how different prompt strategies impact GenAI decision-making in the Beer Game simulation.

#### Prompt Strategies Tested

* Baseline (Flexible GenAI)
* Cost-Aware Conservative
* Risk-Constrained Data-Driven

#### Evaluation Metrics

* Total cost
* Average cost
* Standard deviation

#### Key Insights

* Flexible prompts performed best in cost and stability
* Over-constraining GenAI increased costs significantly
* Prompt design directly impacts decision quality
* Variability is as important as average cost in evaluation 

---

## ⚙️ Technologies Used

* Python
* Google Colab
* Data Analysis (Pandas, NumPy)
* Simulation Modeling
* Generative AI (Prompt-based decision systems)

---

## 🚀 Key Concepts Covered

* Supply Chain Simulation (Beer Game)
* Decision-Making Under Uncertainty
* Generative AI for Decision Support
* Prompt Engineering
* Cost vs Variability Trade-offs


