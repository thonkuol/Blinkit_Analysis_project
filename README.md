# Blinkit Sales Analysis Project

This project is a **Python-based data analysis** of Blinkit sales. It covers the **full data analysis workflow**:  
- Importing and inspecting the dataset  
- Cleaning and preprocessing  
- Calculating key KPIs  
- Creating visualizations for business insights  
- Drawing final conclusions  

---

## Business Objectives
1. Analyze sales performance across outlets and items  
2. Understand customer preferences by item type and fat content  
3. Compare outlet sizes, locations, and establishment years  
4. Identify key factors that drive higher sales  

---

## Technologies Used
- **Python**  
- **Pandas** → data cleaning & manipulation  
- **NumPy** → numerical computations  
- **Matplotlib** & **Seaborn** → visualization
---



## Data Preparation

### Data Inspection
- Shape: **8,523 rows × 12 columns**  
- Missing values checked  
- Dtypes verified  

### Data Cleaning
- Standardized `Item Fat Content`:
  - Replaced `LF` and `low fat` with **Low Fat**  
  - Replaced `reg` with **Regular**  
- Final categories: **Regular, Low Fat**  

---

## Key Performance Indicators (KPIs)
Calculated from the dataset:  
- **Total Sales:** 💰 $1,201,681.5  
- **Average Sales per Item:** 💵 $141.0  
- **Number of Items Sold:** 📦 8,523  
- **Average Rating:** ⭐ 4.0  

---

## Visualizations & Insights

### 1. Total Sales by Fat Content
- Regular items dominate overall sales.  
<img width="1024" height="448" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/387c68b6-8214-456d-93a0-9ef63793b299" />

### 2. Total Sales by Item Type
- Fruits, Vegetables, and Snacks generate the highest sales.  
<img width="1221" height="545" alt="Screenshot (102)" src="https://github.com/user-attachments/assets/68e1f7b1-046f-4c12-b70d-e617bd16c6a0" />


### 3. Total Sales by Outlet Establishment Year
- Older outlets contribute more to total sales.  
<img width="1175" height="546" alt="Screenshot (104)" src="https://github.com/user-attachments/assets/42e50637-e7c5-4531-9379-970b7e9f2f1c" />


### 4. Total Sales by Outlet Size
- Medium-sized outlets dominate sales share.
- <img width="1094" height="461" alt="Screenshot (107)" src="https://github.com/user-attachments/assets/12eebc8f-0045-44f5-ba16-032d961f0e79" />
 


### 5. Total Sales by Outlet Location
- Urban outlets (Tier 1) generate the highest sales.  
<img width="1168" height="556" alt="Screenshot (106)" src="https://github.com/user-attachments/assets/d9a79bd8-b43f-4b1a-9ea3-f0c594c733f7" />

---

## Final Insights
✅ **Urban & medium-sized outlets** drive most sales.  
✅ **Older outlets** have stronger performance.  
✅ **Regular fat items** dominate sales across locations.  
✅ **Fruits, vegetables, and snacks** are the top-selling categories.  



