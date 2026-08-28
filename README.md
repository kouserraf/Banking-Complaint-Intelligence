# Banking Complaint Intelligence

## Banking Customer Complaint Information Extraction and Category Identification Using Rule-Based NLP

### 📌 Project Overview

Banking Complaint Intelligence is a Natural Language Processing (NLP) project designed to analyze unstructured banking customer complaints.

The system uses rule-based NLP techniques such as keyword matching, regular expressions, and predefined patterns to extract important information from customer queries and identify the relevant complaint category.

The extracted information is converted into a structured format that can make banking complaint analysis easier and more efficient.

---

## 🎯 Problem Statement

Banking customers describe their problems using natural language. When a large number of customer complaints are received, manually identifying important information from each complaint can be time-consuming.

This project addresses this problem by automatically extracting relevant information from banking customer complaints and organizing it into structured fields.

---

## 💡 What Does This Project Solve?

The system helps analyze unstructured banking complaints by automatically identifying information such as:

- Transaction amount
- Payment or transaction type
- Transaction status
- Card information
- Banking service
- Complaint issue
- Complaint category

For example:

**Customer Query:**

> I paid Rs 2500 using my card but the payment was declined.

**Structured Output:**

| Information | Extracted Value |
|---|---|
| Amount | Rs 2500 |
| Payment/Transaction Type | Card Payment |
| Transaction Status | Declined |
| Card Information | Card Payment |
| Banking Service | Card |
| Issue | Payment Declined |
| Complaint Category | declined_card_payment |

---

## 🎯 Objectives

- To preprocess banking-related customer complaint text.
- To extract useful information from unstructured customer queries.
- To identify transaction amounts using regular expressions.
- To identify payment and transaction types using keyword-based rules.
- To identify transaction status and complaint issues.
- To identify relevant banking services.
- To identify complaint categories using predefined rules.
- To evaluate the performance of the information extraction system.
- To provide an interactive complaint analysis system.

---

## 📊 Dataset

The project uses a banking customer complaint dataset containing:

- **3,080 customer queries**
- **77 complaint categories**
- **40 queries per category**

The dataset contains labelled banking-related customer queries covering different types of banking problems.

---

## 🔄 Methodology

The project follows the pipeline below:

```text
Customer Complaint
        ↓
Text Preprocessing
        ↓
Rule-Based Information Extraction
        ↓
Complaint Category Identification
        ↓
Structured Output
        ↓
Performance Evaluation
        ↓
Visualization
        ↓
Interactive Analysis

````
---

## 🧠 NLP Techniques Used

### 1. Regular Expressions

Regular expressions are used to identify numerical amounts and currency information from customer queries.

### 2. Keyword Matching

Predefined keywords are used to identify:

- Payment types
- Transaction status
- Banking services
- Card information
- Complaint issues

### 3. Pattern Matching

Predefined linguistic patterns are used to recognize different ways customers describe similar banking problems.

### 4. Rule-Based Category Identification

Customer queries are matched against predefined complaint-category rules to identify the most relevant category.

---

## ⚙️ Features

- Text preprocessing
- Amount extraction
- Payment/transaction type identification
- Transaction status identification
- Card information extraction
- Banking service identification
- Complaint issue identification
- Complaint category identification
- Field-level performance evaluation
- Data visualization
- Interactive complaint analyzer

---

## 📈 Evaluation

The system is evaluated using manually prepared banking customer queries.

Field-level accuracy is calculated for:

- Amount
- Payment/Transaction Type
- Transaction Status
- Card Information
- Banking Service
- Issue

The project also includes visualizations for complaint-category distribution and information extraction performance.

---

## 🖥️ Interactive Analyzer

The project includes an interactive analyzer that allows a user to enter a new banking complaint.

Example:

```text
Enter your banking complaint:

I tried to transfer money but the transaction is still pending.
````

The system analyzes the query and produces structured information including the transaction type, status, banking service, issue, and complaint category.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Regular Expressions
* Natural Language Processing
* Matplotlib
* Jupyter Notebook

---

## 📁 Project Structure

```
Banking-Complaint-Intelligence/
│
├── Banking_Complaint_Intelligence.ipynb
├── README.md
└── requirements.txt
```

---

## ⚠️ Limitations

The current system uses a rule-based approach and therefore depends on predefined keywords and patterns.

Queries containing unfamiliar wording may not always be correctly identified. The system also has limited contextual understanding compared with machine learning or deep learning approaches.

---

## 🚀 Future Scope

The system can be further improved by incorporating:

* Machine Learning classification
* Deep Learning
* Named Entity Recognition
* Semantic analysis
* Fuzzy matching
* Multilingual NLP
* Automatic learning of complaint categories
* Integration with customer-support chatbots

---

## 👩‍💻 Author

**Rafiya Kouser**

---

## 📌 Project Type

**Natural Language Processing / Information Extraction**

**Approach:** Rule-Based NLP
