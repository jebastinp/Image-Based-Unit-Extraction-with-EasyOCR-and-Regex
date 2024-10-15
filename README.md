# Image-Based-Unit-Extraction-with-EasyOCR-and-Regex


This repository provides a Python solution to extract numerical values and associated units (e.g., grams, meters, kilograms) from images linked in a CSV file. The project uses EasyOCR for optical character recognition (OCR) and regex for filtering and extracting specific units from the text.

# Features

Extract text from images using EasyOCR.
Identify numerical values and associated units from the extracted text.
Save the formatted results (numbers and units) into a CSV file.
Setup Instructions

# Prerequisites
Ensure you have the following libraries installed:

pandas
requests
Pillow
easyocr
re
sklearn

# Usage

Prepare your input CSV file with a column named image_link that contains URLs of images to be processed.
Run the provided Jupyter notebook OCR_extraction.ipynb to perform the OCR and extraction of numerical values and units.
The notebook follows these key steps:

1.Load the input CSV.
2.Use EasyOCR to extract text from each image.
3.Apply regex to extract numerical values and recognized units.
4.Save the results into a new CSV file.
