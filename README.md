# OCR PDF Extractor

A simple web application that extracts text from scanned PDF files using OCR. The application allows users to upload a PDF, processes the pages, and returns the extracted text.

## Features

* Upload scanned PDF files
* Extract text from PDF pages using OCR
* Supports image-based/scanned documents
* Simple browser-based interface
* Download or copy extracted text
* Deployed online using Vercel

## Tech Stack

* **Python**
* **Flask** – Backend API
* **Tesseract OCR** – Text recognition
* **PyMuPDF** – PDF processing
* **Pillow** – Image processing
* **Vercel** – Deployment

## How It Works

```text
Upload PDF
    ↓
Flask Backend
    ↓
PyMuPDF extracts PDF pages
    ↓
Pillow processes page images
    ↓
Tesseract OCR reads the text
    ↓
Extracted Text
```

## Project Structure

```text
OCR-PDF-Extractor/
│
├── app.py
├── requirements.txt
├── templates/
│   └── index.html
├── static/
│   └── ...
└── README.md
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/princeraushan/OCR-PDF-Extractor.git
cd OCR-PDF-Extractor
```

### 2. Install Python dependencies

```bash
pip install -r requirements.txt
```

### 3. Install Tesseract OCR

Install Tesseract OCR on your system and make sure it is available in your system PATH.

### 4. Run the application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## Usage

1. Open the application.
2. Upload a scanned PDF.
3. Start the extraction process.
4. The application processes each page using OCR.
5. View or copy the extracted text.


[Source Code](https://github.com/princeraushan/OCR-PDF-Extractor)

## Future Improvements

* Support multiple languages
* Improve OCR accuracy
* Add support for larger PDF files
* Add text formatting
* Add downloadable `.txt` or `.docx` output

## Author

**Raushan Kumar Prince**
