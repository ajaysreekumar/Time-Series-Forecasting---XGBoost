# Readmission Analysis - Power BI & Databricks Project

This repository contains a Jupyter notebook that supports a Power BI visual analytics project focused on analyzing hospital readmissions over time. It is designed to work with Databricks and demonstrates how to prepare data for dynamic filtering, particularly for calculating metrics over the last 12 months excluding the latest month of data.

---

## 📊 Project Overview

The main objective of this project is to:
- Calculate and visualize hospital readmissions over time.
- Dynamically exclude the latest month from rolling 12-month summaries.
- Support Power BI matrix visuals via backend logic in Databricks SQL and Python.

---

## 📁 Files

- `Project.ipynb`: The main notebook that:
  - Connects to your data source
  - Performs necessary preprocessing
  - Adds derived columns (like `monthsFromLatest`)
  - Prepares the dataset for export to Power BI

---

## 🛠 Key Features

- ✅ Extracts the latest month in a dataset
- ✅ Calculates a `monthsFromLatest` column
- ✅ Supports rolling-window metrics
- ✅ Designed to integrate cleanly with Power BI dashboards

---

## 🚀 Getting Started

1. Clone this repository.
2. Open `Project.ipynb` in a Databricks workspace or local Jupyter environment.
3. Ensure your data source is properly connected (modify as needed).
4. Run all cells to generate the processed output.
5. Export the final dataset to Power BI or a target system.

---

## 🧪 Requirements

- Databricks Runtime or local Python 3.8+
- PySpark (if running locally)
- pandas, numpy
- A dataset with a `monthStartDate` column in `yyyy-MM-dd` format

---

## 📈 Example Output

Final dataset includes:
- `monthStartDate`
- `readmissionCount`
- `monthsFromLatest` column
- Calculated measures for filtering and visualization

---

## 📬 Contact

For questions or collaboration, please reach out via [GitHub Issues](https://github.com/your-repo/issues).

---

## 📄 License

This project is licensed under the MIT License.
