# 🧠 Parkinson's Disease Detection using SVM 🎤  

## 🚀 **Overview**  
This project builds a **machine learning model** to detect **Parkinson’s disease** using vocal measurements! 🎙️ The **Support Vector Machine (SVM)** classifier is used to distinguish between **healthy** individuals and those affected by **Parkinson’s disease** based on voice patterns. 🎶  

---

## 📊 **Dataset**  
The dataset, **"Parkinson's disease.csv"**, contains **195 samples** with **24 features**, including:  

✅ **Frequency-based attributes** (Fo, Fhi, Flo)  
✅ **Jitter & Shimmer** (Voice signal variations)  
✅ **HNR & NHR** (Harmonic-to-noise ratio)  
✅ **Nonlinear complexity measures** (RPDE, DFA, PPE)  

🎯 The **status column** (1 = Parkinson’s, 0 = Healthy) is our target variable.  

---

## 🛠️ **Tech Stack**  
🚀 **Python** 🐍  
📊 **Pandas & NumPy** 🔢  
🤖 **scikit-learn** (for ML)  

---

## 📁 **Project Structure**  
📂 **`parkinsons_detection.py`** → Main script 🏆  
📂 **`Parkinson's disease.csv`** → Dataset 📜  

---

## 🏗️ **How It Works**  
1️⃣ **Load Data** → Read the CSV 📊  
2️⃣ **Preprocess** → Remove unwanted columns, standardize values 📏  
3️⃣ **Split Data** → 80% Train, 20% Test 🔪  
4️⃣ **Train Model** → Apply SVM magic 🧙‍♂️  
5️⃣ **Evaluate** → Get accuracy score 📈  

---

## 🎯 **Installation & Setup**  
### **Prerequisites**  
Make sure you have Python installed 🐍, then install dependencies:  
```bash
pip install numpy pandas scikit-learn
```

### **Run the Model**  
1️⃣ Place **Parkinson's disease.csv** in your project folder 📂  
2️⃣ Run the Python script:  
```bash
python parkinsons_detection.py
```
3️⃣ Get the **accuracy score** 🎯  

---

## 🎉 **Expected Output**  
Example output:  
```
Model Accuracy: 89.7% ✅
```
(Your results may vary slightly depending on dataset splits!)  

---

## 🚀 **Future Enhancements**  
✨ Try **Neural Networks** 🧠  
✨ Compare with **Random Forest & XGBoost** 🌲  
✨ Explore more **feature engineering** 🔬  

---
🚀 **Let’s Detect Parkinson’s Disease with AI! 🤖**
