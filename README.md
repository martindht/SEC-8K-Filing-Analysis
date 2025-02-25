# Financial Data Extraction from Loan Agreements (8-K Filings)

This project extracts details from **unstructured loan contracts** using a combination of **regex-based text extraction** and **OpenAI’s API** for structured data retrieval.

## 🚀 Features
- Identifies **borrower, lenders, and loan amounts** from raw text files.
- Extracts **signature page details** (company name, signing person, title).
- Uses **regex** to locate relevant sections and **OpenAI API** for structured extraction.

## 📂 How It Works
1. **Uploads** raw loan contract `.txt` files.
2. **Finds key phrases** (e.g., "Entry into a Material Definitive Agreement") to extract relevant sections.
3. **Sends extracted text** to OpenAI’s API to format the output.
4. **Displays structured results** for easy review.
