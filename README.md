# India-Election-Result-2024-Analysis-
SQL-based analysis of the 2024 Indian Lok Sabha Election results using constituency, party, and state-wise datasets. Includes seat distribution, alliance performance (NDA, I.N.D.I.A, OTHER), vote patterns, top candidates, and state-level insights using advanced queries for political and data analysis.

# 🇮🇳 India Election Result 2024 – SQL Analysis Project

This project analyzes the 2024 Indian Lok Sabha Election Results using SQL. It covers constituency-level, party-level, and state-level performance, along with alliance mapping, vote comparison, and top-candidate insights.  
:contentReference[oaicite:1]{index=1}

---

## 📌 Project Overview
Using relational datasets (constituency, party, state), this project performs deep analytical queries to answer key election questions such as:

- Total seats and state-wise seat availability  
- Seats won by alliances (NDA, I.N.D.I.A, OTHER)  
- Party-wise and candidate-wise performance  
- Highest EVM votes, margins & vote comparisons  
- State-specific summaries (e.g., Maharashtra analysis)  

The goal is to derive meaningful insights into political outcomes using structured SQL analysis.

---

## 📂 Dataset Structure

The SQL file processes the following datasets:

### **1. constituencywise_results**
- Winning candidate  
- Party  
- Total votes & margin  
- Constituency information  

### **2. constituencywise_details**
- Candidate-level EVM & postal votes  
- Total votes  
- Party  

### **3. partywise_results**
- Total seats won per party  
- Party alliance mapping (NDA, I.N.D.I.A, OTHER)  

### **4. states**
- State ID & state name  

### **5. statewise_results**
- State-to-constituency mapping  
:contentReference[oaicite:2]{index=2}

---

## 🧠 Key SQL Insights

### ✅ **Election-Level Insights**
- Total seats in the election  
- Seats available across states  
- Seats won by each alliance (NDA, INDIA, OTHER)

### ✅ **Alliance & Party Analysis**
- Alliance-based total seats  
- Party-wise seats sorted in descending order  
- Automatic party-to-alliance classification using SQL updates  

### ✅ **Constituency Insights**
- Winning candidate details by constituency & state  
- Top 10 candidates with highest EVM votes  
- Margin analysis  

### ✅ **Vote Pattern Analysis**
- EVM vs Postal vote comparison for any constituency  
- Total votes by state  
- State-wise seat distribution among alliances  

### ✅ **State-Level Summaries**
Example: **Maharashtra**
- Total seats  
- Total candidates  
- Total parties  
- EVM votes, postal votes, total votes  
:contentReference[oaicite:3]{index=3}

---

## 📘 Major Queries Included
- Seat distribution by state  
- Seats won by NDA & INDIA alliances  
- Party-level seat breakdown  
- Top EVM vote performers  
- Winning candidate details by constituency  
- State-wise alliance comparison  
- EVM vs postal votes breakdown  
- Comprehensive Maharashtra summary  

---

## 🛠 Tech Stack
- **SQL (MySQL)**  
- **CSV datasets** (Constituencies, Parties, States, Votes)

---

## 📈 Highlights
- Built entirely with **SQL analytical queries**  
- Clean, structured, reusable analysis  
- Includes **14+ in-depth political analytics queries**  
- Ideal for data analysis & political insights  

---

## 📬 Author
**Piyush Barve**
Data Analyst skilled in SQL, Power BI, Python, ETL, and predictive analytics. Passionate about building dashboards, analyzing data, and solving real-world problems through analytics.
📧 Email: piyushbarve@outlook.com
🔗 GitHub: github.com/piyushpbarve
