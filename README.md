# 📊 Sales Management Intelligent Dashboard (IntelliShift Hackathon)

An AI-powered sales management and analytics system developed for a hackathon. The project transforms raw sales data into meaningful business insights through data analysis, visualization, and intelligent decision support.

## 🚀 Overview

The **Sales Management Intelligent Dashboard** is designed to help businesses understand their sales performance, customers, products, and orders through an interactive dashboard.

The system combines:

* 📈 Sales analytics and visualization
* 👥 Customer analysis
* 📦 Product and category analysis
* 🗺️ Location-based analysis
* 🚚 Shipping and order analysis
* 🤖 AI-powered insights
* 📊 Interactive Streamlit dashboard

The goal is to make sales data easier to understand and turn it into actionable business decisions.

---

## 🎯 Problem Statement

Businesses often have large amounts of sales data distributed across multiple datasets, making it difficult to quickly identify:

* Best-performing products
* Most valuable customers
* Sales trends and patterns
* Underperforming categories
* Geographic performance
* Shipping and order behavior
* Opportunities for improving sales

This project addresses these challenges by providing a centralized intelligent dashboard that processes the available sales data and presents useful insights in an accessible way.

---

## ✨ Key Features

### 📈 Sales Analytics

Analyze overall sales performance using metrics and visualizations such as:

* Total sales
* Order volume
* Customer activity
* Product performance
* Sales trends

### 👥 Customer Analysis

Explore customer behavior and identify:

* High-value customers
* Customer purchasing patterns
* Customer distribution
* Sales contribution by customer

### 📦 Product & Category Analysis

Understand which products and categories contribute most to the business.

The dashboard can be used to identify:

* Top-selling products
* High-performing categories
* Underperforming products
* Category-level sales patterns

### 🗺️ Location Analysis

Analyze sales performance across different locations and identify geographic trends and opportunities.

### 🚚 Shipping Analysis

Analyze shipping methods and order-related information to understand their relationship with sales and customer behavior.

### 🤖 Intelligent Insights

The project incorporates AI capabilities to help transform raw analytical results into more understandable business insights and support decision-making.

---

## 🏗️ Project Structure

```text
Sales-Management-Intelligent-Dashboard/
│
├── data/
│   ├── Categories.csv
│   ├── Customers.csv
│   ├── Data.csv
│   ├── Locations.csv
│   ├── Order_Details.csv
│   ├── Orders.csv
│   ├── Products.csv
│   ├── Ship_Modes.csv
│   ├── Sub_Categories.csv
│   │
│   └── updatedfolders/
│       ├── Customers (1).csv
│       ├── Order_Details (1).csv
│       ├── Orders (1).csv
│       └── Products (1).csv
│
├── Hackathon.ipynb
├── Data.csv
├── ERD.pdf
├── Problem_Statement.pdf
├── O JAMP.pdf
│
└── Streamlit.py
```

> File names may vary depending on the final version of the project.

---

## 🛠️ Technologies Used

| Technology            | Purpose                              |
| --------------------- | ------------------------------------ |
| Python                | Core development and data processing |
| Pandas                | Data manipulation and analysis       |
| NumPy                 | Numerical operations                 |
| Streamlit             | Interactive web dashboard            |
| Matplotlib / Plotly   | Data visualization                   |
| Jupyter Notebook      | Exploratory data analysis            |
| AI / LLM Technologies | Intelligent insights                 |

---

## 📊 Dataset

The project uses multiple related datasets representing different aspects of a sales management system.

### Main datasets

* **Customers** — customer information
* **Orders** — order-level information
* **Order Details** — detailed information about individual orders
* **Products** — product information
* **Categories** — product categories
* **Sub-Categories** — product subcategories
* **Locations** — geographic information
* **Ship Modes** — shipping methods

These datasets can be combined to provide a comprehensive view of the sales ecosystem.

---

## 🧠 Data Architecture

The project uses relational sales data where entities such as customers, orders, products, and locations are connected through relationships.

A simplified representation is:

```text
Customers
    │
    │ Customer ID
    ▼
  Orders
    │
    │ Order ID
    ▼
Order Details
    │
    │ Product ID
    ▼
 Products
    │
    ├── Category
    │
    └── Sub-Category

Orders
    │
    ├── Location
    │
    └── Ship Mode
```

The complete database relationship design can be found in the included **ERD.pdf**.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/bahboorr/Sales-Management-intelligent-Dashboard--problem-statement-.git
```

### 2. Navigate to the project

```bash
cd Sales-Management-intelligent-Dashboard--problem-statement-
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the environment

#### Windows

```powershell
.venv\Scripts\activate
```

#### Linux / macOS

```bash
source .venv/bin/activate
```

### 5. Install dependencies

If a `requirements.txt` file is available:

```bash
pip install -r requirements.txt
```

Otherwise, install the required packages manually:

```bash
pip install pandas numpy streamlit matplotlib plotly
```

---

## ▶️ Running the Dashboard

Start the Streamlit application with:

```bash
streamlit run Streamlit.py
```

Streamlit will provide a local URL, typically:

```text
http://localhost:8501
```

Open the URL in your browser to interact with the dashboard.

---

## 🔍 Exploratory Data Analysis

The `Hackathon.ipynb` notebook contains the exploratory analysis and data-processing work performed during development.

It can be opened using:

```bash
jupyter notebook Hackathon.ipynb
```

or:

```bash
jupyter lab
```

---

## 📌 Example Business Questions

The system can help answer questions such as:

* What are our best-selling products?
* Which categories generate the most revenue?
* Which customers contribute the most to sales?
* Which locations have the highest sales?
* Which products are underperforming?
* What are the major sales trends?
* Which shipping methods are most frequently used?
* Where are the biggest opportunities for improving sales?

---

## 💡 Future Improvements

Potential improvements include:

* 🔮 Sales forecasting
* 🤖 More advanced AI-powered recommendations
* 💬 Natural-language querying of the sales database
* 📊 More advanced interactive visualizations
* 📈 Customer segmentation
* 🧠 Predictive customer behavior analysis
* 🚨 Automated anomaly detection
* 📦 Inventory and demand prediction
* 🔐 User authentication and role-based dashboards
* ☁️ Cloud deployment

---

## 🏆 Hackathon Project

This project was developed as part of a **hackathon challenge focused on sales management and intelligent business analytics**.

The objective was to combine data analysis, visualization, and AI technologies to create a practical solution for improving sales-management decision making.

---

## 👨‍💻 Contributors

**Bahboor**

Developed as a collaborative hackathon project.

---

## 📄 Project Documentation

Additional project materials are included in the repository:

* `Problem_Statement.pdf` — Hackathon problem statement
* `ERD.pdf` — Entity Relationship Diagram
* `O JAMP.pdf` — Supporting project documentation
* `Hackathon.ipynb` — Data analysis and experimentation

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.
