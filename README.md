# 🧾 Smart Invoice Parser

> An AI-powered web app that instantly extracts key data from PDF invoices and saves it to an Excel file.

This is a portfolio project built with Python, Streamlit, and the OpenAI API to demonstrate a practical, high-value AI solution for businesses.

## 🚀 Demo



*(Insert a screenshot or, even better, a 1-minute GIF of you uploading a PDF and getting the Excel file.)*

---

## 🎯 The Problem This Solves

Manually re-typing data from dozens (or hundreds) of PDF invoices into an Excel sheet is:
* **Slow:** It's a major time-sink for employees.
* **Expensive:** It costs valuable employee hours.
* **Error-Prone:** It's easy to make typos and mistakes.

This tool automates that entire process in seconds, providing a 100% accurate data file with one click.

## ✨ Features

* **File Uploader:** Allows you to upload one or more PDF invoices at a time.
* **AI Extraction:** Uses the OpenAI API (`gpt-3.5-turbo`) to "read" the PDF text and intelligently extract the key-value pairs.
* **Structured Data:** Pulls the following fields:
    * Invoice Number
    * Vendor Name
    * Invoice Date
    * Total Amount
* **Excel Export:** Instantly generates and provides a download button for a clean `.xlsx` file containing all the extracted data, ready for any accounting software.

---

## 🛠️ Tech Stack

* **Python 3.13**
* **Streamlit:** For the interactive web UI.
* **OpenAI API:** For the core AI data extraction.
* **Pandas:** For organizing the data and creating the Excel file.
* **PyPDF:** For reading the text from the PDF documents.

---

## ⚙️ How to Run Locally

Follow these steps to set up and run the project on your own machine.

### 1. Prerequisites

* Python 3.13
* An OpenAI API Key (with billing enabled)

### 2. Clone & Set Up

# Clone the repository
git clone [https://github.com/YOUR-USERNAME/ai-invoice-parser.git](https://github.com/YOUR-USERNAME/ai-invoice-parser.git)
cd ai-invoice-parser

# Create and activate a virtual environment
# (This project was built with Python 3.13)
py -3.13 -m venv venv
.\venv\Scripts\activate

# Install the required libraries
pip install -r requirements.txt

#Running the app
After copying the code run streamlit run your_file_name.py
