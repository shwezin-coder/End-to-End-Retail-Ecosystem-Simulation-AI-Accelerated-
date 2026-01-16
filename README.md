
# End-to-End Retail Ecosystem Simulation (AI-Accelerated)

### 🚀 Project High-Level Overview

This project features a high-fidelity synthetic data engine designed to simulate the complex, end-to-end operations of a major Australian retail ecosystem. Moving beyond simple randomization, I engineered a production-grade simulation that mirrors real-world supply chain dependencies, consumer behavior, and geographical constraints.

By leveraging a hybrid workflow of **Python (NumPy/Pandas)** and **Gemini Pro**, I optimized the generation logic to handle massive datasets with high performance and logical integrity.


<img width="6341" height="4868" alt="Dataset Simulation-2026-01-16-034349" src="https://github.com/user-attachments/assets/d3a4e32d-63fb-4baf-bed0-c7ac2c27cc11" />

---

### 🛠️ Technical Stack & Architecture

* **Engine:** Python (NumPy, Pandas, Datetime)
* **Orchestration:** Gemini Pro (AI-Assisted Code Refactoring & QA)
* **Data Model:** Relational Star Schema (10+ Datasets)
* **Documentation:** Mermaid.js (Architecture-as-Code)
<img width="1181" height="1234" alt="image" src="https://github.com/user-attachments/assets/5cf912ad-f1eb-49eb-aa3b-4661f29dd7e1" />


---

### ✨ Key Features & Business Logic

* **Omnichannel Simulation:** Enforced strict 15% Online vs. 85% Offline transaction ratios.
* **Seasonality Curves:** Modeled holiday sales spikes (e.g., December peaks) using weight-based statistical trends.
* **Supply Chain Constraints:** Relational mapping between 130+ Suppliers, 150+ Stores, and 1M+ Order Items.
* **Last-Mile Logistics:** Integrated delivery plan logic, courier distribution, and status tracking (Pending/Delivered/Failed).
* **Marketing Intelligence:** Simulated campaign-driven web sessions, bounce rates, and customer reviews.

---

### ⚡ Performance Optimization (The 94% Speedup)

A core highlight of this project is the transition from iterative processing to vectorized execution.

* **The Problem:** Initial loops took **2+ hours** to generate 400,000 orders.
* **The Solution:** Refactored logic using **Dictionary Hashing (O(1) lookups)** and **NumPy Vectorization**.
* **The Result:** Reduced execution time to just **7 minutes**, a 94% performance improvement.
<img width="830" height="631" alt="image" src="https://github.com/user-attachments/assets/13f9958f-665e-4fb9-9872-53c683eb8cea" />

---

### ✅ Data Integrity & Validation

To ensure production-grade quality, the engine includes a rigorous validation framework:

* **Chronological Logic:** Guaranteed that `Delivery Date` never precedes `Order Date`.
* **Stock Consistency:** Order volumes are strictly capped by monthly store inventory levels.
* **Geo-Accuracy:** Store and customer distributions are mapped to valid Australian postcodes and states.
<img width="1151" height="1404" alt="image" src="https://github.com/user-attachments/assets/be84e816-5549-46f2-aaad-0118e81db762" />

---

### 📊 Sample Insights (Generated Data)

*Note: Due to the commercial nature of this simulation engine, raw datasets are not public. Below are aggregated insights proving data validity.*

---

### 📝 Personal Note

I am dedicated to providing the highest quality resources for my students and readers. This project was born from a need for "messy," realistic data to teach advanced concepts like industry-specific outlier detection and complex data preparation. If you find a way isn't working, don't give up—find a better way.
