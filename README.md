# 📊 Cost Model Intelligence (CMI)

## 📌 Project Overview
Cost Model Intelligence (CMI) is a smart system designed to automate the validation of vendor cost models against contract terms.

The project focuses on reducing manual effort in procurement processes by extracting, analyzing, and comparing contract data with vendor-submitted cost data. This system ensures accuracy, consistency, and compliance in cost evaluation using data processing and intelligent validation techniques.

---

## 🎯 Objectives
- Automate contract and cost model validation  
- Reduce manual errors in procurement analysis  
- Improve accuracy in vendor cost comparison  
- Ensure compliance with contract terms  
- Generate structured validation reports  

---

## 🏗️ System Architecture
The system follows a modular pipeline:

- Contract Upload & Processing  
- Cost Model Input Handling  
- Data Preparation & Alignment  
- Validation Engine  
- Report Generation  

---

## 🧩 Modules Description

### 1️⃣ Contract Processing Module
- Accepts contract documents (PDF/Docs)  
- Extracts important details such as:
  - Pricing terms  
  - Conditions  
  - Vendor agreements  

---

### 2️⃣ Cost Model Processing Module
- Takes vendor cost data as input  
- Identifies:
  - Bill of Materials (BOM)  
  - Pricing breakdown  
  - Cost structures  

---

### 3️⃣ Data Preparation for Validation
Before validation, the system aligns and prepares data:

- Map cost model data with contract terms  
- Align BOM and vendor data  
- Filter relevant validation records  
- Ensure data consistency and completeness  
- Normalize formats:
  - Units  
  - Currency  
  - Naming conventions  

---

### 4️⃣ Validation Engine
- Compares contract data with cost models  
- Detects:
  - Price mismatches  
  - Missing components  
  - Contract violations  
- Uses rule-based validation logic  

---

### 5️⃣ Report Generation Module
- Generates validation reports with:
  - ✅ Matching entries  
  - ❌ Errors and mismatches  
  - ⚠️ Warnings and alerts  
- Helps in decision-making for procurement teams  

---

## 🛠️ Technologies Used

- **Frontend:** React.js, CSS  
- **Backend:** FastAPI (Python)  
- **Database:** PostgreSQL  
- **AI & LLM Services:** Azure OpenAI (GPT), LangGraph  
- **Document Processing:** Azure AI Document Intelligence  
- **File Storage:** Azure Blob Storage  

---

## 🔄 Data Flow
Contract → Data Extraction → Data Preparation → Validation → Report
Cost Model → Data Alignment → Validation → Output


---

## 📚 Conclusion
The Cost Model Intelligence system simplifies the complex process of validating vendor cost models against contracts. By automating key steps, it enhances efficiency, accuracy, and reliability in procurement workflows.
