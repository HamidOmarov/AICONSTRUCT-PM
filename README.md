---
title: AICONSTRUCT-PM
emoji: 🏗️
colorFrom: blue
colorTo: green
sdk: gradio
python_version: 3.11
---

# AICONSTRUCT-PM: AI-Powered Construction Project Assistant 🏗️

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/downloads/release/python-3110/)
[![Gradio](https://img.shields.io/badge/%F0%9F%A4%97%20Gradio-Gradio-orange)](https://www.gradio.app/)
[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-yellow)](https://huggingface.co/spaces)

**Live Demo:** **[🚀 AICONSTRUCT-PM on Hugging Face Spaces](https://huggingface.co/spaces/HamidOmarov/AICONSTRUCT-PM)**
*(Note: The live demo is currently running in an offline simulation mode due to an external network issue with the Inference API, but it fully demonstrates the application's functionality.)*

---

## Overview

AICONSTRUCT-PM is a web application designed to automate the tedious process of analyzing daily construction reports. This tool leverages a Large Language Model (LLM) to read unstructured text documents (`.txt` files) and extract key, actionable data, presenting it in a clean, structured JSON format. It's built for project managers, site engineers, and cost controllers who need to quickly process information without spending hours on manual data entry.

This project serves as a "proof-of-concept" to solve a real-world business problem I witnessed firsthand in the construction industry: the bottleneck caused by manual document processing.

## How It Works: Before & After

The application transforms a standard, hard-to-parse daily report into a structured, easy-to-use data object.

### **BEFORE:** Unstructured Daily Report

A typical daily report is a simple text file, rich with information but difficult to process automatically.

![Before - Unstructured Report](https://github.com/HamidOmarov/AICONSTRUCT-PM/blob/main/before_image.png?raw=true)

### **AFTER:** AI-Extracted Structured Data

The application extracts the vital information and organizes it into a clean JSON format, ready for use in other systems like databases or dashboards.

![After - Structured JSON Output](https://github.com/HamidOmarov/AICONSTRUCT-PM/blob/main/after_image.png?raw=true)

## Key Features

- **File Upload:** Simple and intuitive interface to upload `.txt` construction reports.
- **AI-Powered Extraction:** Uses a Large Language Model to intelligently parse the document and identify key data points.
- **Structured Output:** Presents the extracted data in a clean, developer-friendly JSON format.
- **Web-Based & Accessible:** Deployed on Hugging Face Spaces, making it accessible from anywhere without any local installation.

## Technology Stack

- **Backend:** Python
- **AI/ML:** Hugging Face Inference API (simulated)
- **Web Framework/UI:** Gradio
- **Deployment:** Hugging Face Spaces
- **Version Control:** Git & GitHub

## Running Locally

To run this project on your own machine:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/HamidOmarov/AICONSTRUCT-PM.git](https://github.com/HamidOmarov/AICONSTRUCT-PM.git)
    cd AICONSTRUCT-PM
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    # For Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```
    ```bash
    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the application:**
    ```bash
    python app.py
    ```
    The application will be available at `http://127.0.0.1:7860`.
