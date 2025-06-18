
# 📊 D3.js Retail Sales Dashboard

This project is a **polished, interactive sales dashboard** built using **D3.js**. It visualizes retail sales performance across various stores and compares metrics such as **Daily Sales**, **Industry Average**, and **Global Average** using multiple datasets.

---

## 📁 Project Structure

```
d3js_retail_dashboard/
│
├── DASHBOARD/
│   ├── Store_Sales_Dataset_2.csv
│   ├── Store_Sales_Dataset_3.csv
│   ├── Store_Sales_Q1_2025.csv
│   └── index.html               # Main dashboard with interactive charts
│
├── Task/
│   ├── Store_Sales_Dataset_1.csv
│   ├── Store_Sales_Dataset_2.csv
│   ├── Store_Sales_Jan_to_June_2025.csv
│   └── sales.html               # Task-specific version of dashboard
│
├── README.md                    # This file
```

---

## 🧩 Features

- 📈 Multiple D3.js chart types: line, bar, pie/donut, scatter, and stacked bar.
- 🏪 Dataset filter to compare store performance.
- 🌍 Benchmarks included:
  - Store Sales vs Industry Average
  - Industry Average vs Global Average
- 🎨 Smooth animations, tooltips, and modern UI.
- 🌙 Dark mode support for better readability.
- 📂 Accepts any CSV file with the correct structure.

---

## 📄 CSV File Format

The dashboard supports CSV files with the following columns:

```csv
Date,Store,Daily Sales,Industry Average,Global Average
```

Make sure your CSV follows this structure to ensure proper visualization.

---

## 🚀 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/whyvirinchy/d3js_retail_dashboard.git
   ```

2. **Open the dashboard**:
   - For full dashboard: open `DASHBOARD/index.html` in a browser
   - For task version: open `Task/sales.html` in a browser

3. No backend/server required. Runs entirely in the browser.

---

## 📦 Datasets Included

- `Store_Sales_Dataset_1.csv`
- `Store_Sales_Dataset_2.csv`
- `Store_Sales_Dataset_3.csv`
- `Store_Sales_Q1_2025.csv`
- `Store_Sales_Jan_to_June_2025.csv`

These datasets contain sales metrics for various stores and date ranges to demonstrate different dashboard views.

---

## 🛠 Technologies Used

- **D3.js v7**
- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6)**

---

## 🙋‍♂️ Author

Created by [@whyvirinchy](https://github.com/whyvirinchy)

Feel free to fork, improve, or raise issues!
