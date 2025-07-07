# 🍃 Google BigQuery Analysis – Avocado & Citi Bike Data

This repository contains queries written and tested in **Google BigQuery** for analyzing:
- 🥑 Avocado sales data
- 🚲 NYC Citi Bike trip data

The goal is to explore data transformation, calculate percentages, verify aggregation logic, and identify trends across years.

---

## 📁 Included File

- `sql.txt` – A collection of queries for:
  - `coastal-cider-465210-c8.avocado_data.avocado_prices`
  - `bigquery-public-data.new_york_citibike.citibike_trips`

---

## 🧠 Query Highlights

### 🥑 Avocado Price Dataset

**Source:** `coastal-cider-465210-c8.avocado_data.avocado_prices`

#### 🔹 Total Bag Verification
Calculates total bags by summing Small, Large, and XLarge bag columns.

#### 🔹 Small Bag Percentage
Finds the percentage of small bags compared to total bags where total bags are not zero.

#### 🔹 All Bag Types – Percent Breakdown
Returns percent share of small, large, and extra-large bags relative to total bags.

#### 🔹 View All Records
Displays the full dataset without filtering.

---

### 🚲 NYC Citi Bike Trip Dataset

**Source:** `bigquery-public-data.new_york_citibike.citibike_trips`

#### 🔹 Yearly Trip Volume
Extracts the year from ride start times and counts trips per year to track growth trends.

---

## 🧰 Tools Used

- Google BigQuery (Standard SQL)
- GCP Console Interface
- Public Datasets

---

## 🎯 Purpose

- 🧪 Practice percentage calculations
- 🔁 Verify bag aggregation logic
- 📊 Identify trends using date-based grouping
- 🧹 Filter and explore public datasets interactively

---

## 🙋‍♂️ Author

**Zain Ul Abideen Alvi**  
📧 zainalvi552@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/zain-ul-abideen-alvi-32b3b6275/)  
🏷️ *Data Engineer | AI Developer*

---

## ⭐ Contributions

Suggestions or collaborations are welcome! Feel free to fork this repo, raise an issue, or submit a PR for new queries, datasets, or enhancements.
