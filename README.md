# Swiggy Order Data Analysis & Dashboard Project

This repository features a comprehensive data analysis and visualization project based on food delivery data from Swiggy. The analysis covers order trends, geographical distributions, pricing, and restaurant performance across multiple cities.

The core dataset used in this project is based on **Swiggy Raw Data Excel.xlsx**, which contains transactional records of orders, user ratings, and restaurant details.

---

## 📊 Project Overview

The main objective of this project is to clean, analyze, and visualize Swiggy's transactional data to uncover key insights regarding consumer behavior, popular food categories, and operational performance across different quarters.

### Key Insights & Features:
*   **Temporal Trends:** Analysis of order volumes by Quarter, Week, and Days of the week.
*   **Geographical Breakdown:** Performance tracking across various Indian states and major cities.
*   **Menu & Pricing Insights:** In-depth evaluation of food types (Veg vs. Non-Veg), item pricing, and popular dish categories.
*   **Performance Metrics:** Study of restaurant ratings and rating counts to identify top-performing food hubs.

---

## 📁 Dataset Structure

The dataset **Swiggy Raw Data Excel.xlsx** includes the following key worksheets:

1.  **Swiggy Data:** The primary database containing ~197,430 raw order records.
2.  **Analysis:** Pivot tables, aggregations, and core logical calculations.
3.  **Dashboard:** An interactive visual summary of the KPIs and operational metrics.

### Data Dictionary (`Swiggy Data` Sheet):

| Column Name | Description |
| :--- | :--- |
| **State** | The state where the order was placed. |
| **City** | The specific city (e.g., Bengaluru, Mumbai, New Delhi, etc.). |
| **Order Date** | The timestamp/date of the order placement. |
| **week** | Operational week number of the year. |
| **Day** | Day of the week (e.g., Sun, Mon, Tue). |
| **Quarter** | Financial/Calendar quarter (Q1, Q2, etc.). |
| **Restaurant Name** | Name of the restaurant rendering the service. |
| **Location** | Local area/neighborhood within the city. |
| **Category** | Food category or meal section. |
| **Dish Name** | The specific item ordered. |
| **Food Type** | Dietary classification (e.g., Veg, Non-Veg). |
| **Price (INR)** | Price of the item in Indian Rupees. |
| **Rating** | Customer rating given to the dish/restaurant (0.0 - 5.0). |
| **Rating Count** | Total number of ratings received. |

---

## 🛠️ Tech Stack & Tools Used

*   **Data Source / Storage:** Microsoft Excel (`Swiggy Raw Data Excel.xlsx`)
*   **Data Processing:** Excel Formulas, Power Query / Pandas (Python)
*   **Analytics:** Pivot Tables and Data Modeling
*   **Visualization:** Interactive Excel Dashboard / Charts

---

## 🚀 How to Run / Explore This Project

1.  **Clone the Repository:**
```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    ```
2.  **Open the Dataset:**
    *   Navigate to the root directory and locate **Swiggy Raw Data Excel.xlsx**.
    *   Open it using Microsoft Excel or any compatible spreadsheet software.
3.  **Interact with the Dashboard:**
    *   Go to the `Dashboard` sheet to filter data using interactive slicers (by City, Quarter, or Food Type) to view real-time updated metrics.

---

## 📈 Summary Statistics (Quick Snapshot)

*   **Total Records:** 197,430 orders
*   **Geographical Coverage:** 28 Major Cities across India (including Bengaluru, Mumbai, Chennai, Hyderabad, Delhi, etc.)
*   **Timeline Coverage:** Data spanning across multiple quarters of 2025 (Q1 to Q3).

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](link-to-your-issues-here) if you want to contribute to further Python-based automation or PowerBI integration for this dataset.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
