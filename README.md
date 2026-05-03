# IT3040 – ITPM Assignment 1  
## Transliteration Accuracy Testing  

**Student ID:** IT23682764  
**Degree:** BSc (Hons) in Information Technology – Year 3  
**Semester:** Semester 1  
**Assignment:** Assignment 1 – Option 1 (Sinhala Transliteration)

---

## 📌 Objective
This project evaluates the accuracy of the Chat Sinhala transliteration function available at:

👉 https://www.pixelssuite.com/chat-translator  

The goal is to:
- Identify 50 incorrect transliteration test cases  
- Automate testing using Playwright  
- Record results in an Excel file  

---

## ⚙️ Prerequisites
Make sure you have installed:

- Python 3.11 or 3.12  
- Google Chrome (recommended)  
- Git  

---

## 🚀 Installation & Setup

### 🔹 Step 1: Clone the repository

## Step 1: Clone the repository

git clone https://github.com/isiwari2004/ITPM_Assigment1.git
cd ITPM_Assigment1

## Step 2: Navigate to the test_automation folder
cd test_automation

## Step 3: Install required dependencies (one-time only)

- pip install -U pip
- pip install playwright openpyxl
- python -m playwright install

### ▶️ How to Run the Tests

## Step 1: Go back to the root folder
cd ..

## Step 2: Run the Playwright script
python test_automation/test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Step 3: Check the results
After the script finishes, open Assignment 1 - Test cases.xlsx. The Actual output and Status columns will be filled automatically.

