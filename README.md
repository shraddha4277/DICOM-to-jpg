# DICOM-to-jpg
This repository contains a Python script for converting DICOM (Digital Imaging and Communications in Medicine) images to PNG or JPG format. This tool is particularly useful for visualizing and processing medical images in a more accessible and widely-used image format.
Features
Convert DICOM to PNG: Easily convert DICOM files to PNG format for easier manipulation and visualization.
Metadata Preservation: Extracts and preserves relevant metadata from DICOM files.
Batch Processing: Supports converting multiple DICOM files at once.
Why DICOM?
DICOM is the international standard for storing and transmitting medical imaging information. It ensures interoperability between different medical devices and systems within a healthcare environment. DICOM files contain not only image data but also important metadata about the patient and imaging study.

Requirements
Python 3.x
pydicom
numpy
Pillow

The required libraries are installed using pip:
--pip install pydicom numpy pillow

Command-line Arguments
--input_dir: Path to the directory containing DICOM files.
--output_dir: Path to the directory where PNG files will be saved.

Example
Here's an example command to convert DICOM files stored in the dicom_files directory to PNG format, saving the results in the png_images directory:
python dicom_to_png.py --input_dir dicom_files --output_dir png_images

Acknowledgements
pydicom - A Python package for parsing DICOM files.
Pillow - The friendly PIL fork for image processing in Python.
