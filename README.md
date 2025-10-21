# Traditional RAG System on RBI Annual Reports (2020-2025)

## Overview
This project implements a simple **traditional Retrieval-Augmented Generation (RAG)** system trained on **RBI Annual Reports from 2020 to 2025**. The system is designed to analyze the financial assessment and prospects outlined in these reports and generate relevant responses based on the trained data.

## Data
- The training data consists of RBI annual reports for the years 2020–2025.  
- **Data is not included in the repository** for privacy reasons and is ignored via `.gitignore`.  
- Official RBI reports can be accessed here: [RBI Annual Reports](https://rbi.org.in/Scripts/AnnualReportMainDisplay.aspx)

## Notebooks
- `notebooks/pdf_loader.ipynb`: Contains the implementation of data loading, preprocessing, and testing of the RAG system.  
- This notebook demonstrates the results of the trained RAG system and serves as the main point of interaction with the project.

## Features
- Simple, traditional RAG implementation.  
- Trained on domain-specific financial reports.  
- Tested and validated within the provided notebook.

## Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
