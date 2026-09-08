---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.19.4
  kernelspec:
    display_name: Python 3 (ipykernel)
    language: python
    name: python3
---

```python
# Understanding the Olist E-Commerce Dataset

## Introduction

The Olist Brazilian E-Commerce Dataset is a multi-table relational dataset containing information about customers, orders, products, sellers, payments, reviews, and geographical locations. It provides a realistic representation of an e-commerce platform and serves as an excellent dataset for learning Machine Learning and Data Engineering concepts.

## Dataset Exploration

During this laboratory, the dataset was successfully loaded into Python using Pandas. Each table was inspected for its structure, dimensions, data types, missing values, and duplicate records. Relationships between tables were also identified using common keys such as `order_id`, `customer_id`, `product_id`, and `seller_id`.

## Data Quality

Several tables contained missing values, especially the Products and Orders tables. Duplicate record analysis showed very few duplicate rows, indicating good overall data quality. Understanding these issues is important before applying Machine Learning algorithms.

## Business Insights

The Orders table acts as the central table, connecting customers, payments, reviews, and products. Initial exploratory analysis showed that delivered orders constitute the majority of transactions, while review scores and payment methods provide useful business insights.

## Potential Machine Learning Applications

This dataset can be used for:
- Late delivery prediction
- Customer review score prediction
- Customer segmentation
- Product recommendation
- Sales forecasting
- Fraud detection

## Conclusion

This laboratory provided a strong foundation in understanding relational datasets, performing exploratory data analysis, and preparing data for future Machine Learning tasks. Proper data understanding is an essential first step before feature engineering and model development.
```
