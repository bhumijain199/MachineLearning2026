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

The Olist dataset contains information about customers, orders, products, sellers, payments, reviews, and locations. It is a relational dataset that can be used for data analysis and Machine Learning projects.

## Dataset Exploration

In this lab, all the CSV files were loaded using Pandas. The tables were explored by checking their dimensions, data types, missing values, and duplicate records. The relationships between different tables were also identified using common keys such as `order_id`, `customer_id`, and `product_id`.

## Data Quality

Some tables contained missing values, mainly in the Products and Orders datasets. Very few duplicate records were found, which indicates that the dataset is generally clean. These issues should be handled before building any Machine Learning model.

## Business Insights

The Orders table acts as the main table because it connects most of the other tables. Most orders were successfully delivered, and customer reviews and payment methods provide useful information for analysis.

## Possible Machine Learning Applications

- Predict late deliveries
- Predict customer review scores
- Customer segmentation
- Product recommendation
- Sales forecasting

## Conclusion

This lab helped me understand the structure of the Olist dataset and the relationships between different tables. It also showed the importance of exploring and cleaning data before applying Machine Learning techniques.