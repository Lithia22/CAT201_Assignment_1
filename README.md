# PDF Converter Web Application

This project is a simple web-based application designed to convert PDF files to TXT files and vice versa. The web application is built using HTML, CSS, JavaScript, PHP, and Java. The app uses the Apache PDFBox library, a free tool for handling PDF documents.


## Prerequisites

- Docker installed on your system. [Watch a YouTube tutorial on installing Docker](https://youtu.be/TDLKQWsrSyk?si=bcv0J37m7tACiZW_)

## Features

- **PDF to TXT Conversion**
- **TXT to PDF Conversion**
- **File Validation**: Checks file type, size, and integrity.
- **Multiple File Upload**: Allows uploading one or more files at a time.

## How To Use

1. **Pull the Docker images:**
   
   ```bash
   docker pull httpd
   docker pull php:apache
   ```

2. **Download the repository:**
   
   ```bash
   git clone https://github.com/Lithia22/CAT201_pdf_converter.git
   ```
   
3. **Enter the project folder::**
   
   ```bash 
   cd pdf_converter
   ```
   
4. **Launch the Docker container:**
   
   ```bash
   docker run -d -p 8000:80 --name PDF_converter -v "$(pwd)":/var/www/html php:apache
   ```
   
5. **Verify the container is running:**
   
   ```bash
   docker ps
   ```
   
6. Access the application at localhost:8000 to start converting PDFs and TXT files.

## Video Tutorial

https://github.com/user-attachments/assets/d53a4f7c-5dfd-4bd1-8779-a6fc579ad9ad




