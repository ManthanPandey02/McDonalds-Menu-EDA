# 🍔 McDonald’s Menu Nutritional Analysis  

## 📖 Overview  
This project analyzes the nutritional content of **260 McDonald’s US menu items** to uncover health risks, identify high-calorie categories, and provide actionable recommendations for both **consumers** and **McDonald’s**.  

The work is inspired by growing obesity rates in the US and aims to **educate consumers** on healthier choices while suggesting **strategic improvements** for the company.  

Using **Python (Pandas, Seaborn, Matplotlib, Plotly, Statsmodels)**, the analysis explores:  
- Calorie density by category  
- Portion size vs. calories  
- High-risk nutrient items (sodium, sugar, fats)  
- Correlations among nutrients  

---

## 🎯 Problem Statement & Background  
According to the National Health and Nutrition Examination Survey, over **40% of adults** and almost **20% of children** in the US are obese. Obesity contributes to diabetes, cardiovascular diseases, and cancer, with annual medical costs of **$173B (2019)**.  

Many fast-food consumers unknowingly exceed their daily calorie and nutrient needs. This project demonstrates how data analysis can guide **informed food choices** and reduce the risk of obesity-related diseases.  

---

## 📊 Dataset  
- **Source:** McDonald’s US Menu Nutritional Data  
- **Size:** 260 items × 24 variables  
- **Features:** Category, Item, Serving Size, Calories, Macronutrients (fat, protein, carbs), Micronutrients (sodium, iron, calcium, etc.)  
- **Cleaning:**  
  - Removed zero-nutrient beverages (coffee/tea)  
  - Standardized serving sizes (grams/ml)  
  - Validated calorie counts against macros  

---

## 🔍 Exploratory Data Analysis (EDA)  

### Key Visualizations  
✔ **Calorie Density by Category** – desserts & breakfast items are calorie-heavy.  
✔ **Top 5 High-Nutrient Items** – highlights burgers, shakes, and desserts exceeding daily values.  
✔ **Boxplots of Nutrients** – show outliers and category differences.  
✔ **Serving Size vs. Calories Scatterplot** – strong positive relationship.  
✔ **Correlation Heatmap** – calories strongly linked to fat, protein, and carbs.  

📌 *Takeaway:* Nearly **47% of items exceed daily nutrient limits**, and upsizing in certain categories disproportionately increases calorie intake.  

---

## 📈 Key Findings  
- **High-Risk Items:** 121 menu items exceed 100% of daily nutrient limits (sodium, sugar, fat).  
- **Calorie Density:** Desserts, beef/pork, and breakfast items are the most calorie-dense.  
- **Portion Size Impact:** Upsizing increases calories more than serving size proportionally.  
- **Correlations:** Calories strongly correlated with saturated fat (0.85), protein (0.79), and carbs (0.78).  

---

## 📝 Recommendations  

### ✅ For Consumers  
- Avoid **upsizing** in calorie-heavy categories.  
- Choose lower-calorie-density items (salads, apple slices).  
- Monitor **sodium & sugar** intake using menu data.  

### ✅ For McDonald’s  
- Introduce more **portion-controlled options**.  
- Display **nutrient densities** clearly on menus.  
- Reformulate **high-sugar desserts and beverages**.
