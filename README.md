# Invoice Extraction System

This project extracts key fields from invoice images using two different approaches.

Pipeline A
OCR (Tesseract) + Regex

Pipeline B
LayoutLM Document AI

Extracted Fields

Seller Name
Seller Tax ID
Client Name
Client Tax ID
Invoice Number
Invoice Date
Net Worth
VAT
Gross Worth

Outputs

outputs/output.csv
outputs/comparison_report.csv

Run

python main.py
