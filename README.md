# 🏦 Dynamic OOP Simulations: Financial Ledgers & Inventory Engines

A comprehensive Python repository implementing **Object-Oriented Programming (OOP)** paradigms to solve foundational real-world tracking problems. This repository hosts two distinct, production-grade command-line simulation engines: a **Secure Banking Ledger System** and an **Automated Bicycle Inventory Management Engine**. Both systems demonstrate programmatic encapsulation, state mutations, and temporal data tracking.

---

## 📂 Repository Structure & Assets

* 💻 **[View Core Code Notebook](./Bank_account_project.ipynb)** – Interactive Jupyter Notebook containing the full object class blueprints, strict validation parameters, execution loops, and real-time outputs.
* 📋 **Project Source:** Developed as an advanced architectural capstone featuring modular programmatic architectures.

---

## 🛠️ Tech Stack & OOP Design Principles

* **Programming Language:** Python 🐍
* **Design Pattern:** Object-Oriented Programming (OOP) enforcing:
  * **Encapsulation:** Binding data properties (such as account balances and bike sales metrics) safely inside class instances to prevent outside mutation corruption.
  * **State Validation:** Utilizing conditional boundary gates to enforce business rules (e.g., stopping withdrawals beyond existing balance limits, or locking price updates on already-sold assets).
* **Time Management:** Native integration of Python's `datetime` module for granular financial audit stamping.

---

## 🚀 Component Projects Overview

### 1. Object-Oriented Banking System (`bank` class)
An isolated financial ledger environment capable of simulating everyday retail banking behaviors with automated multi-format outputs:
* **Initial State Protection:** Boots every new user instance with a rigid baseline equity of `0`.
* **Guarded Deposit Routine:** Validates inputs to ensure positive float entries before incrementing account matrices.
* **Insufficient Funds Shield:** Calculates withdrawal queries against active balances to intercept deficit creations:
  $$\text{Condition Check: } \text{Amount} \le \text{Current Balance}$$
* **Chronological Audit Logs:** Leverages custom string formatting (`%A`, `%B`, `%p`) to render transaction outputs complete with day names and diurnal time frames (AM/PM).

### 2. Bicycle Retail & Inventory Engine (`Bike` class)
An asset management pipeline tracing product lifecycles from acquisition through condition grading, price tuning, and final purchase fulfillment:
* **Asset Profiling:** Encapsulates physical parameters including technical description tags, acquisition cost, recommended sales pricing, and overall mechanical condition coefficients.
* **Price Locking Guard:** Enforces transactional integrity; once an asset's state transitions to `sold = True`, the algorithm permanently freezes the entry and blocks any post-sale value manipulation attempts.

---

## 👤 Developed by:
* **Nada Alaklook**
* 🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/nada%20alakluk-725049252)
