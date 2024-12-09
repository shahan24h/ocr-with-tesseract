# OCR Processing with Tesseract and Magick in R

This project demonstrates the use of Tesseract and Magick libraries in R for Optical Character Recognition (OCR) and image preprocessing tasks. It supports text extraction from images and PDFs, language updates, and custom OCR configurations.

## About

This project leverages the `tesseract` and `magick` R libraries to:
- Perform OCR on images and PDFs.
- Preprocess images for better OCR accuracy.
- Support multilingual text extraction.
- Customize OCR with specific parameters.

## Features

- ✅ OCR support for multiple languages.
- ✅ Image preprocessing with Magick.
- ✅ OCR from PDF files.
- ✅ Custom OCR settings (e.g., character whitelists).

## Prerequisites

Ensure the following are installed on your system:
- R (version >= 4.0)
- Tesseract OCR (installed and configured)
- Required R libraries: `tesseract`, `magick`, `pdftools`

## Installation

1. Install the required R packages:
   ```R
   install.packages("tesseract")
   install.packages("magick")
   install.packages("pdftools")
