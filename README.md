# 🎮 Video Game Sales Forecasting

This project analyzes global video game sales data to identify market trends, evaluate platform and genre performance, and generate insights to guide business decisions. Using exploratory analysis, hypothesis testing, and forecasting logic, the project helps stakeholders understand what drives sales across regions and platforms.

---

## 📌 Project Objectives

- Analyze global and regional sales trends  
- Evaluate performance by platform and genre  
- Identify market opportunities across NA, EU, and JP  
- Conduct statistical hypothesis tests on platform and genre ratings  
- Create business recommendations for publishers entering 2017  
- Build a foundation for forecasting future game sales

---

## 📂 Dataset

The dataset includes:  
- **Game titles**  
- **Platform**  
- **Genre**  
- **Critic and user ratings**  
- **Sales by region (NA, EU, JP, Other)**  
- **Global sales totals**

Source: TripleTen (based on historical VGCharts data)

---

## 📊 Key Findings & Insights

### **1. Most profitable genres differ by region**
- **North America:** Action, Shooter, and Sports dominate  
- **Europe:** Action and Shooter remain strong  
- **Japan:** Role-Playing Games (RPG) significantly outperform other genres  

### **2. Platform performance varies globally**
- **PS4 & Xbox One** lead in Western markets  
- **3DS** performs strongly in Japan  
- Older platforms show sales decline by 2013–2016

### **3. Statistical Hypothesis Tests**
- **Xbox One vs. PC ratings:**  
  - Result: No statistically significant difference  
  - Test: Welch’s t-test (p ≈ 0.1476)  
- **Action vs. Sports ratings:**  
  - Result: Unable to test due to insufficient rating data  

### **4. Best timeframe for forecasting 2017**
- Selected **2013–2016** as training window because:  
  - Represents latest console generation  
  - Older systems (PS2, Wii, DS) already declined  
  - Best reflects trends entering 2017

---

## 🧠 Business Recommendations

### **North America**
- Prioritize: **Action, Shooter, Sports**  
- Focus on **PS4** and **Xbox One** game development  

### **Europe**
- Similar to NA: Emphasize **Action/Shooter** genres  
- Target PS4 and Xbox One markets  

### **Japan**
- Invest heavily in **RPGs**  
- Support **3DS** platform  
- Develop titles with strong critic appeal  

### Overall Strategy
- Reduce investment in older declining platforms  
- Tailor marketing by **region-specific preferences**  
- Build genre-focused strategies for each market  

---

## 🛠️ Tools & Technologies

- **Python**  
- **Pandas & NumPy**  
- **Matplotlib & Seaborn**  
- **SciPy** (Welch’s t-test)  
- **Jupyter Notebook**  
- **EDA + Visualization**  
- **Statistical Hypothesis Testing**


---

## 🙌 Conclusion

This project demonstrates ability to:  
- Clean and analyze real-world data  
- Visualize trends and patterns  
- Apply statistical testing  
- Translate findings into business recommendations  
- Perform region- and genre-specific market analysis  
- Build analytics skills aligned with data analyst & data scientist roles  

---

## 🔗 Repository

GitHub: **https://github.com/ContrerasJJ/Video-Game-Sales-Forecasting**
