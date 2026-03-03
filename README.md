# 🏋️‍♂️ Calorie Calculator & Fitness Insights Dashboard (Excel)

This project is a fully dynamic **Excel-based calorie calculator and fitness analytics dashboard**.  
It calculates calories, analyzes workout efficiency, and provides personalized insights based on user inputs such as age, gender, height, weight, activity level, and target goals.

The dashboard also includes analytics on **calories burned per workout type**, **calories burned per minute**, and **personalized comparisons** using a “People Like You” engine.

---

## ❤️ Motivation

One day, my father asked me a simple question:

> “How many calories do I burn, and how much should I eat if I want to lose weight?”

As a fitness enthusiast, I wanted to help him — but I also realized that most online calculators are generic and don’t consider real‑world workout data or personalized comparisons.

So I built this project from scratch.

This dashboard is the result of:
- My passion for fitness  
- My curiosity about data  
- And my desire to help people (starting with my dad) understand their bodies better  

---

## ⭐ Features

### 🔢 **Dynamic Calorie Calculator**
Automatically calculates:
- BMI  
- Target BMI  
- BMR (Mifflin‑St Jeor formula)  
- Activity factor  
- Maintenance calories  
- Calorie intake after deficit  
- Protein intake  

All values update instantly when the user changes:
- Age  
- Gender  
- Height  
- Weight  
- Activity level  
- Deficit size  

---

### 🧠 **“People Like You” Engine**
A custom filtering system that identifies people in the dataset who match the user’s:
- Age range (±5 years)  
- Height range (±5 cm)  
- Weight range (±5 kg)  
- Gender  

This enables personalized insights based on real workout data.

---

### 🔥 **Workout Analytics**
PivotTables and charts reveal:
- Average calories burned per workout type  
- Average session duration  
- Calories burned per minute (efficiency metric)  
- Comparison across Cardio, HIIT, Strength, and Yoga  
- Insights based on similar people only  

---

### ⏱️ **Calories Burned Per Minute**
A custom metric added to the dataset:

=[@Calories_Burned] / ([@Session_Duration] * 60)


This highlights which workouts burn calories fastest.

---

### 📊 **Interactive Dashboard**
Includes:
- Calorie calculator panel  
- Workout comparison charts  
- Burn‑per‑minute analysis  
- Personalized insights  
- Clean, user‑friendly layout  


![Calorie Calculator Dem](./Image/cal-calc.gif)

---

## 🛠️ Tools & Techniques Used

### **Excel Features**
- PivotTables  
- PivotCharts  
- Slicers  
- Data validation  
- Named ranges  
- Structured tables  
- GETPIVOTDATA  
- Conditional logic (IF, AND)  

### **Data Modeling**
- Helper columns for matching logic  
- Dynamic filtering  
- Custom metrics  
- Dashboard layout design  

---


---

## 🚀 How to Use

1. Open the Excel dashboard file  
2. Enter your personal details in the input panel  
3. The dashboard updates automatically  
4. Explore:
   - Calories burned  
   - Workout efficiency  
   - Personalized insights  
   - Burn per minute  

This makes it easy to understand your calorie needs and compare workout effectiveness.

---

## 🔮 Future Enhancements

- Weekly weight‑loss forecast  
- Workout recommendation engine  
- Heart rate vs calorie burn analysis  
- Macro intake comparison  
- Exportable PDF report  

---

## 🙌 Acknowledgements

This project was inspired by my father’s fitness journey and my own passion for health and data.  
It reflects my interest in building tools that combine **fitness**, **analytics**, and **Excel mastery**.
The dataset is from Kaggle.
---


