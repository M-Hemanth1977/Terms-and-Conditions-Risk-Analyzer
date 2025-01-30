# Terms and Conditions Risk Analyzer

## Overview
The **Terms and Conditions Risk Analyzer** is a web-based tool designed to help businesses and individuals analyze Terms and Conditions (T&Cs) to identify potential risks. The tool leverages **Natural Language Processing (NLP)** and **keyword matching** to scan legal contracts for critical clauses that may introduce **legal, financial, or operational risks** for the user.

Additionally, it provides a **summarization feature** to generate a concise summary of the T&Cs, highlighting key aspects without requiring users to read the full contract.

## Features

### 🔹 Multiple Input Formats:
- **📄 PDF Upload**: Upload a PDF version of the terms and conditions.
- **🔗 URL Input**: Provide a URL link to a webpage containing the terms and conditions.
- **📋 Text Input**: Directly paste the text of the terms and conditions.

### 🔹 Risk Categorization:
The tool identifies and categorizes risks into the following categories:

- ✅ **Data Privacy Risk**
- ✅ **Liability Risk**
- ✅ **Termination Risk**
- ✅ **Intellectual Property Risk**
- ✅ **Payment or Financial Risk**
- ✅ **Service Level Agreement (SLA) Risk**
- ✅ **Governing Law and Jurisdiction Risk**
- ✅ **Force Majeure Risk**
- ✅ **Confidentiality Risk**
- ✅ **Warranty Risk**
- ✅ **Third-Party Obligations Risk**
- ✅ **Compliance Risk**
- ✅ **Indemnity Risk**
- ✅ **Modification of Terms Risk**
- ✅ **Auto-Renewal Risk**
- ✅ **Usage Restrictions Risk**
- ✅ **License Scope Risk**
- ✅ **Age Restrictions Risk**
- ✅ **Prohibited Users Risk**
- ✅ **Geographic Restrictions Risk**

### 🔹 Interactive UI:
- **Sidebar** for input options: Upload PDF, enter URL, or paste text.
- **Expandable sections** explain detected risk categories and causes.
- **Highlighted matched text** for better risk visualization.

### 🔹 Keyword Matching with NLP:
- Uses **spaCy's PhraseMatcher** to detect risk-related keywords and phrases.
- Provides **explanations** for identified risks and highlights the **exact phrases** that triggered the detection.

### 🔹 Summarization Feature:
- Uses **TextRank** (via spaCy or Sumy) to generate a **concise summary** of the Terms and Conditions.
- Extracts key points without requiring users to read the entire document.

### 🔹 Performance Optimization:
- **Fast text extraction** from PDFs and web pages using **pypdf** and **BeautifulSoup**.
- **Streamlit-powered UI** for a **user-friendly** experience.

---

## 🚀 How to Use

1. **Choose an input method**:
   - 📄 **Upload a PDF** containing the Terms and Conditions.
   - 🔗 **Enter a URL** of a webpage with the Terms and Conditions.
   - 📋 **Paste the Terms and Conditions** in the provided text area.

2. **Click "Analyze T&C"** to start the analysis.

3. The tool will:
   - 🔍 **Identify risk categories** and causes.
   - 📌 **Highlight matched text** for each risk.
   - ✍️ **Provide a summary** of the Terms and Conditions.

---

# SaaS Terms and Conditions Risk Analyzer

## Overview
The SaaS Terms and Conditions Risk Analyzer is a web-based tool that helps businesses and individuals analyze SaaS vendors' Terms and Conditions (T&Cs) to identify potential risks. The tool uses natural language processing (NLP) and keyword matching to scan legal contracts for critical clauses that may introduce legal, financial, or operational risks for the buyer. These risks are categorized into various sections such as data privacy, intellectual property, liability, termination, and more.

This tool aims to help users quickly identify and assess risks hidden within lengthy contracts, enabling them to make informed decisions before accepting T&Cs from SaaS providers.

## Features

### Multiple Input Formats:
- **PDF Upload**: Upload a PDF version of the terms and conditions to be analyzed.
- **URL Input**: Provide a URL link to a webpage containing the terms and conditions.
- **Text Input**: Directly paste the text of the terms and conditions for analysis.

### Risk Categories: 
The tool identifies and categorizes risks into the following categories:
- Data Privacy Risk
- Liability Risk
- Termination Risk
- Intellectual Property Risk
- Payment or Financial Risk
- Service Level Agreement (SLA) Risk
- Governing Law and Jurisdiction Risk
- Force Majeure Risk
- Confidentiality Risk
- Warranty Risk
- Third-Party Obligations Risk
- Compliance Risk
- Indemnity Risk
- Modification of Terms Risk
- Auto-Renewal Risk
- Usage Restrictions Risk
- License Scope Risk
- Age Restrictions Risk
- Prohibited Users Risk
- Geographic Restrictions Risk

### Interactive UI:
- Use the sidebar to upload a PDF, enter a URL, or paste text.
- Risks are displayed with expandable sections explaining the risk category and the causes behind the risk.
- Highlighted matched text that triggered the risk detection.

### Keyword Matching with NLP:
- Utilizes spaCy's PhraseMatcher to detect predefined risk-related keywords and phrases.
- Provides explanations for the identified risks and matches the exact phrases that triggered the risk.

### Performance Optimization:
- Fast and efficient text extraction from PDFs and web pages using pypdf and BeautifulSoup respectively.
- Displays results with a user-friendly interface powered by Streamlit.



## Example Usage
1. Choose an option from the sidebar:
   - **PDF**: Upload a PDF containing the SaaS Terms and Conditions.
   - **URL**: Enter the URL of a webpage with the SaaS Terms and Conditions.
   - **Text**: Paste the Terms and Conditions in the provided text area.
2. Click on the "Analyze T&C" button to start the analysis.
3. The tool will display the identified risk categories and causes along with the matched text for each risk.
