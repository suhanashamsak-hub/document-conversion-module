Document Conversion Module

This project implements a parser module capable of processing PDF and DOCX inputs.

Features
- Extracts text from PDF files using PyMuPDF
- Extracts text from DOCX files using python-docx
- Exports extracted content into .txt or .md formats
- Batch processes files from input directory

Project Structure
- input/ : Contains source documents
- output/ : Stores converted files
- converter.py : Main processing script

How to Run

pip install pymupdf python-docx
python converter.py
