# Python-Mini_Project
ML Project using Pandas and Python

use this link to download the CSV file: https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants?

Zomato Restaurant Analysis & Preprocessing

An end-to-end data science project focused on exploring, cleaning, and preprocessing the Zomato Bangalore restaurants dataset to uncover insights into the food industry landscape.

---

## 📌 Project Overview
This project processes real-world scraped data from Zomato (Bangalore) containing information on over 50,000 restaurants. The notebook focuses on key data science stages:
* Data ingestion and inspection.
* Handling missing or malformed values (e.g., non-standard rating formats like `4.1/5`).
* Feature engineering and data transformations for exploratory analysis and predictive modeling.

---

## 📊 Dataset Features
The dataset (`zomato.csv`) includes the following information:

| Column Name | Description |
| :--- | :--- |
| `url` | Zomato URL for the restaurant |
| `address` | Complete location details |
| `name` | Name of the restaurant |
| `online_order` | Availability of online ordering (Yes/No) |
| `book_table` | Table booking facility (Yes/No) |
| `rate` | Restaurant rating out of 5 |
| `votes` | Total number of customer ratings |
| `location` | Specific neighborhood in Bangalore |
| `rest_type` | Type of restaurant (e.g., Casual Dining, Cafe, Quick Bites) |
| `cuisines` | Food styles offered |
| `approx_cost(for two people)` | Estimated dining expense for two |
| `listed_in(type)` | Type of meal service (e.g., Buffet, Delivery) |

---

## 🛠️ Requirements & Environment Setup

### Tech Stack
* **Language:** Python 3
* **Environment:** Google Colab / Jupyter Notebook

Required Libraries
To run the notebook locally, you need the following Python scientific stack:
import pandas
import numpy
import matplotlib.pyplot
import seaborn


Data Preprocessing:

Stripping off string suffixes from numerical values (e.g., cleaning the rate and approx_cost columns).

Handling null data fields and filtering noise.

Exploratory Data Analysis (EDA): Visualizing patterns across restaurant pricing, customer engagement (votes), and popularity distribution across different cities and service types.

🎯 Sample Insights from Preview
Pricing & Class Multiplicity: The dataset shows a varied landscape ranging from affordable local spots (approx_cost ~ 300 INR) to higher-tier experiences (~ 800+ INR).

Delivery-First Footprint: A significant presence of modern customer-facing features like online ordering and automated table booking across several standard locations.
