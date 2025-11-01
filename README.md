# 🎢 Roller Coaster Data - Exploratory Data Analysis

This project performs **Exploratory Data Analysis (EDA)** on a dataset of roller coasters from around the world.  
The goal is to clean, prepare, and visualize the data to uncover insights about coaster features such as speed, height, year introduced, and manufacturer.

---

## 📊 Project Overview

This notebook walks through the following steps:

### **Step 0: Imports and Data Loading**
- Load the dataset `coaster_db.csv` using pandas.
- Display shape, data types, and a statistical summary of the data.

### **Step 1: Data Understanding**
- Explore dataset structure using `.shape`, `.head()`, `.describe()`, `.dtypes`.
- Identify columns to retain for analysis.

### **Step 2: Data Preparation**
- Drop irrelevant and duplicate columns.
- Rename columns for clarity.
- Handle missing and duplicate rows.
- Convert date columns to datetime format.

### **Step 3: Feature Understanding (Univariate Analysis)**
- Visualize individual features using:
  - Histograms
  - KDE Plots
  - Boxplots
- Identify trends such as:
  - Distribution of coaster speeds
  - Most active years of coaster introductions
  - Types of coasters (steel, wooden, hybrid, etc.)

### **Step 4: Feature Relationships (Bivariate Analysis)**
- Explore relationships between multiple variables:
  - Scatter plots (Speed vs Height)
  - Pairplots
  - Correlation Heatmaps
  - Grouped statistics by coaster location

### **Step 5: Insights / Question**
> **Question:** Which locations have the fastest roller coasters (minimum 10 coasters per location)?  
Visualized using a horizontal bar chart showing the average coaster speed by location.

---

## 📈 Sample Visualizations

| Visualization | Description |
|----------------|-------------|
| 📊 **Speed Distribution** | Histogram and KDE of coaster speeds |
| 🔗 **Speed vs Height** | Scatterplot showing relationship between coaster speed and height |
| 🌍 **Average Speed by Location** | Bar chart comparing average coaster speeds across countries |
| 🔥 **Correlation Heatmap** | Relationship strength between numerical features |

---

## 🧰 Technologies Used

| Tool | Purpose |
|------|----------|
| **Python 3** | Core programming language |
| **Pandas** | Data manipulation and cleaning |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Advanced statistical plots |
| **Jupyter Notebook** | Interactive analysis |

---

## 🗂️ Project Structure

