# Olist 360°: End-to-End E-Commerce Data Analytics Project

## Project Overview
This project presents an end-to-end data analytics solution designed to evaluate and optimize the marketplace ecosystem of Olist, the largest department store in Brazilian marketplaces. By analyzing historical transaction data spanning 2016 to 2018, this project provides a comprehensive 360-degree view of the platform across three core business pillars: **Business & Sales**, **Logistics & Delivery**, and **Customer Experience**.

The target objective is to uncover operational bottlenecks, assess merchant governance, identify seasonal purchasing trends, and translate raw data into actionable corporate strategies.

---

## Repository Structure & Deliverables
The repository is organized around the following key deliverables:

*   **[`Olist 360°.ipynb`](./Olist%20360%C2%B0.ipynb)**: The technical pipeline containing data cleansing, structural preprocessing, text analytics (NLP), and statistical formatting executed in Python.
*   **[`Olist 360°-.pbix`](./Olist%20360%C2%B0-.pbix)**: The interactive Power BI dashboard featuring three dedicated reporting layers built with custom DAX measures, dynamic filter interfaces, and advanced geospatial mapping.
*   **[`Recommendation.pdf`](./Recommendation.pdf)**: A formal business report outlining data-driven strategic actions and expected commercial outcomes for executive leadership.
*   **[`images-.pdf`](./images-.pdf)**: Visual documentation and screenshots of the finished dashboards for rapid review.

---

## Technical Workflow & Methodology

### 1. Data Source & Extraction
The underlying raw dataset was sourced from the **Kaggle Olist Dataset**, which contains real, anonymized marketplace records across multiple relational tables (customers, orders, items, payments, reviews, and products).

### 2. Data Cleansing & Preparation (Python)
Using [`Olist 360°.ipynb`](./Olist%20360%C2%B0.ipynb), a systematic preprocessing pipeline was engineered to ensure data integrity:
*   **Handling Inconsistencies & Redundancies**: Evaluated missing values, standardized data types, and parsed timestamp records.
*   **Feature Engineering**: Computed critical custom metrics such as delivery duration variances, installment preferences, and freight-to-price ratios.
*   **Text Analytics (NLP)**: Processed raw customer review text by isolating Portuguese feedback, filtering out systemic stop-words, and generating a frequency-based word cloud to extract thematic root causes behind negative scores.

### 3. Business Intelligence & Visualization (Power BI)
The processed data was modeled into an active snowflake schema inside [`Olist 360°-.pbix`](./Olist%20360%C2%B0-.pbix), separating analytics into three distinct reporting lenses:
*   **Business & Sales Dashboard**: Tracks total Gross Merchandise Volume (GMV), Total Orders, Average Order Value (AOV), payment method distributions, and temporal trends.
*   **Logistics & Delivery Dashboard**: Maps out SLA breach rates across geographical clusters, evaluates delivery times, and isolates freight cost correlations relative to product dimensions.
*   **Customer Experience Dashboard**: Analyzes the relationship between transit delays and customer ratings, evaluates seller performance distribution, and visualizes qualitative review text.

---

## Key Strategic Insights & Strategic Report
The analytical findings have been consolidated into a professional executive document. You can read the detailed insights, statistical evidence, and commercial outcomes directly here:

 **[View the Strategic Recommendations Report (Recommendation.pdf)](./Recommendation.pdf)**

### Brief Summary of Core Insights:
*   **Sales Trends**: A definitive sales peak was identified in November 2017, aligning directly with seasonal Black Friday demand and proving a baseline for proactive pre-season inventory allocation.
*   **Logistical Costs**: Freight value accounts for an average of 16.66% of the product price, showing a strong linear correlation with product weight, justifying a need for tiered third-party logistics restructuring.
*   **Customer Experience**: Natural Language Processing (NLP) of text reviews revealed that fulfillment anxieties and shipping delays are the primary drivers of negative (1-3 star) feedback, establishing a clear link between transit times and platform reputation.

---

## Visual Dashboard Preview
For a quick graphical overview of the developed dashboard interfaces without opening Power BI, you can explore the complete compiled visual export here:

 **[View Dashboard Screenshots (images-.pdf)](./images-.pdf)**

---

## Professional Growth Statement
Developing this project provided a structured opportunity to apply end-to-end data engineering and analytics practices to a complex, real-world e-commerce architecture. Managing the workflow—from raw relational database joins and programmatic data cleansing in Python to relational modeling, advanced DAX calculations, and interactive interface design in Power BI—deepened my technical execution. 

Crucially, it reinforced the value of data governance, the importance of avoiding speculative assumptions without statistical evidence, and the ability to translate technical data models into clear, actionable business strategies for executive decision-makers.
