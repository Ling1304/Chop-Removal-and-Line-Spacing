# Scanned Document Enhancement: Chop Removal and Line Spacing Adjustment

This repository contains a Python project that uses OpenCV and several supporting libraries to process scanned documents, specifically targeting the enhancement of physical receipts, invoices, and other scanned texts that suffer from poor readability due to tight sentence spacing and visual distortions.

## Key Features of the Code:

- **Deskewing**:  
  Automatically detects and corrects skew in scanned documents, aligning the text properly for improved clarity and readability.

- **Chop Removal**:  
  Removes unwanted artifacts such as cut-off edges, reducing noise and enhancing text recognition.

- **Upscaling**:  
  Enhances the resolution of scanned documents to improve image quality for easier text extraction and better visual appeal.

- **Sentence Detection**:  
  Uses contour detection techniques to accurately detect individual sentences or blocks of text for precise processing.

- **Line Spacing Adjustment**:  
  Allows users to specify the amount of spacing between sentences, improving legibility for tightly spaced text in receipts and invoices.

## Purpose:

The goal of this project is to make scanned physical documents more readable and accessible by addressing common issues such as misalignment, artifacts, and poor spacing. Whether you're working with receipts, handwritten notes, or any document requiring adjustments to its layout and quality, this tool provides an easy solution to enhance the visual presentation and text extraction for further processing or printing.

## Use Cases:

This code is particularly useful for preprocessing scanned receipts and invoices for:

- Machine learning models requiring clean, structured input.
- Document processing systems that need readable, high-quality data.
- Improved visual appeal and text clarity for printing and further usage.

---

Feel free to contribute to this project or suggest improvements by submitting a pull request.
