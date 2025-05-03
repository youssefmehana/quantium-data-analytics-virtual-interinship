

## 📊 Introduction

Quantium has partnered with a large supermarket chain, providing access to transactional and customer data. As an analyst in the Quantium Analytics team, your role is to deliver high-value data insights to support strategic business decisions.

Supermarkets frequently adjust store layouts, product selections, pricing, and promotions to:

* Meet changing customer needs and preferences
* Stay ahead of competition
* Capitalize on emerging opportunities

Quantium analysts are involved in evaluating the impact of these changes and making data-driven recommendations on their effectiveness.


## 🧠 What You'll Learn

In this program, you'll develop key analytics skills including:

* Data wrangling
* Data visualization
* Programming
* Statistics
* Critical thinking
* Commercial decision-making


## 📁 Task 1: Data Preparation and Customer Analytics

### 🎯 Objective

Conduct an analysis of the client's transaction dataset to uncover customer purchasing behaviors and generate commercial insights, specifically focusing on **chip purchases**.

### 🧾 Background

You are assisting the **Category Manager for Chips**, who wants to understand the types of customers who purchase chips and their purchasing behavior across the region.

### 📌 Key Goals

* Generate actionable insights to support the **strategic plan** for the chips category over the next 6 months.
* Understand current **purchasing trends** and behaviors.
* Segment customers by **LIFESTAGE** and **PREMIUM\_CUSTOMER** type.

### ✅ Tasks

1. Perform high-level data checks:

   * Create data summaries
   * Identify and remove outliers
   * Check and correct data formats

2. Feature engineering:

   * Derive `pack_size` and `brand` from product names
   * Define key metrics such as:

     * Total spend
     * Purchase frequency
     * Customer demographics

3. Identify and describe customer segments

4. Provide commercial recommendations based on insights


## 🧪 Task 2: Experimentation and Uplift Testing

### 🎯 Objective

Evaluate the impact of a **new store layout trial** in select stores to determine whether it should be rolled out chain-wide.

### 🧾 Background

The **Category Manager for Chips** has asked for a data-driven evaluation of trial layouts conducted in stores **77, 86, and 88**.

### 📌 Key Goals

* Select **benchmark (control)** stores using similarity measures
* Measure sales impact during the trial using:

  * Total sales revenue
  * Number of customers
  * Average transactions per customer

### ✅ Tasks

1. Use the `QVI_data` dataset or Task 1 outputs
2. Calculate similarity metrics (e.g. Pearson correlation or magnitude distance) to select control stores
3. Write a **reusable function** for control store selection
4. Analyze trial vs control performance:

   * Is the increase in sales significant?
   * Are changes due to more customers or more purchases?


## 📈 Task 3: Analytics & Commercial Application

### 🎯 Objective

Present a clear, concise report of your findings and strategic recommendations to the **Category Manager**.

### 📌 Focus Areas

* Translate technical insights into **business recommendations**
* Use minimal jargon
* Highlight **commercially actionable** insights

### ✅ Report Guidelines

1. **Structure:**

   * Introduction
   * Methodology
   * Insights (with graphs and taglines)
   * Commercial Recommendations

2. **Visuals:**

   * Use charts to illustrate key trends and comparisons
   * Highlight segment-level behaviors

3. **Recommendations:**

   * Should be data-backed
   * Clear and relevant to strategic planning


## 🧷 Definitions

* **LIFESTAGE**: Identifies whether a customer has a family and what stage they're at (e.g., pre-school, primary, secondary).
* **PREMIUM\_CUSTOMER**: Classifies shoppers based on spending habits and brand preference (e.g., premium vs. budget shoppers).



## 📌 Final Deliverables

* Jupyter Notebook or Python scripts
* Cleaned and prepared datasets
* Control store selection functions
* Strategic presentation/report for Category Manager


