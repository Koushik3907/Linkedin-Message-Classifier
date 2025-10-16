# 📩 LinkedIn Message Classifier — Prioritising Your Connections

## 🧠 Project Summary
The **LinkedIn Message Classifier** is an AI-powered system designed to help users efficiently manage their LinkedIn messages.  
As the number of daily DMs continues to grow, professionals often miss important opportunities hidden among general or promotional messages.  
This project automates the process of extracting, classifying, and prioritizing messages — ensuring that users never overlook key conversations.

---

## 🎯 Problem Statement
- Increasing message volume makes manual management difficult.  
- Important messages from recruiters, collaborators, or friends often go unnoticed.  
- Existing tools provide only basic automation without intelligent categorization.

---

## 💡 Proposed Solution
An intelligent message classification system that:
1. Automatically **extracts messages** from a user’s LinkedIn account via a browser extension.  
2. Uses a **machine learning model** to categorize messages (e.g., Opportunity, General, Thanks, Promotion).  
3. **Color-codes messages** based on their importance and category.  
4. Displays categorized results directly within the LinkedIn interface.

---

## ⚙️ System Architecture
[LinkedIn Browser Extension] → [Django Backend] → [ML Classifier] → [SQLite Database] → [User Interface]

---

## 🧩 Key Features
- 🔐 **Secure Login** via LinkedIn authentication  
- 📨 **Automatic Message Extraction** from LinkedIn  
- 🤖 **AI-Based Message Classification** using NLP  
- 🎨 **Color-Coded Prioritization** for better visibility  
- 💻 **Integrated Browser Extension** for real-time access  

---

## 🧠 Technical Specifications
| Component | Technology |
|------------|-------------|
| Operating System | Windows 10 |
| Backend Framework | Django |
| Frontend | HTML, CSS, JavaScript |
| Database | SQLite3 |
| Programming Language | Python |
| Extension | JavaScript (Browser API) |

---

## 🔬 Machine Learning Overview
- **Algorithm Used:** Text Classification (e.g., Naïve Bayes / Logistic Regression)  
- **Libraries:** scikit-learn, nltk, pandas  
- **Preprocessing:** Tokenization, Stopword Removal, TF-IDF Vectorization  
- **Output:** Message category with priority label  

---

## 🚀 Workflow
1. User installs and enables the browser extension.  
2. Extension securely extracts unseen messages.  
3. Backend API processes text using the ML classifier.  
4. Classified messages are color-coded and displayed on the LinkedIn interface.  
