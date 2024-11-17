# Scanned Document Enhancement: Chop Removal and Line Spacing Adjustment
This repository contains a Python project that uses OpenCV and several supporting libraries to process scanned documents, specifically targeting the enhancement of physical receipts, invoices, and other scanned texts that suffer from poor readability due to tight sentence spacing and visual distortions.

## Key features of the code include:
Deskewing: Automatically detects and corrects any skew in the scanned document, aligning the text properly to improve clarity and readability.
Chop Removal: Removes unwanted "chops" or artifacts typically found on scanned documents, such as cut-off edges, reducing noise and improving text recognition.
Upscaling: Enhances the resolution of scanned documents, improving image quality for easier text extraction and better visual appeal.
Sentence Detection: Utilizes contour detection techniques to accurately detect individual sentences or blocks of text, ensuring that each sentence is processed distinctly for spacing adjustments.
Line Spacing Adjustment: Allows users to specify the amount of line spacing between sentences, improving the legibility of tightly spaced text, especially on receipts and invoices.
The goal of this project is to make scanned physical documents more readable and accessible by addressing common issues such as misalignment, artifacts, and poor spacing. Whether you're working with receipts, handwritten notes, or any document requiring adjustments to its layout and quality, this tool provides an easy solution to enhance the visual presentation and text extraction for further processing or printing.

This code is particularly useful for preprocessing scanned receipts and invoices for machine learning models or other document processing systems that require clean, readable data.
