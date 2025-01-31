# PDF Table Extractor

## Overview

This project provides a Python script to extract tables from a PDF file and save them as separate Excel files. It is designed to handle multiple PDFs with structured tabular data efficiently.

## Features

- Extracts tables from all pages of a PDF.

- Saves each table as a separate Excel file.

- Works with different PDF inputs.

- Optimized for accuracy and performance.

## Installation

Ensure you have the required dependencies installed:

` pip install pdfplumber pandas `

## Usage

- Step 1: Upload the PDF in Google Colab

`from google.colab import files
uploaded = files.upload()`

- Step 2: Run the Extraction Script

Execute the extract_tables_from_pdf.py script to process the uploaded PDF.

- Step 3: Download Extracted Excel Files

The extracted tables will be automatically saved and downloaded.

## Key Considerations

- Handles empty tables gracefully.

- Detects headers and structures data correctly.

- Ensures compatibility with different table formats in PDFs.

## Conclusion

This script provides a reliable and efficient way to extract tabular data from PDFs, making it useful for data processing and automation tasks.
