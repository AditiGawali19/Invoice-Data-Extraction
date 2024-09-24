# Invoice-Data-Extraction and Table Highlighting


Overview

This project focuses on detecting tables within invoice documents and extracting their coordinates, along with the number of rows and columns. The detected tables are visually represented by drawing borders around them in the original image files.


Objectives

The objective of this project is to work with files similar to invoice documents containing itemized tables of services and prices, alongside other content such as addresses and invoice information. The task includes:

1.Detecting tables within these files.
2.Extracting the coordinates of each detected table (bounding box or other appropriate representation) as well as the number of rows and columns in each table.
3.Drawing a border around each detected table in the original file to visually represent the table areas.


Required libraries: opencv-python, numpy, Pytesseract, json
Tesseract OCR installed on your machine
IDE: Jupyter Notebook



Procedure
1. Input Files Preparation:
   Convert the pdf into image format i.e .PNG and Store the invoice images (PNG or JPG) in the 
   "Input Images" folder.

2.Data Extraction:
  Use Pytesseract to extract Text from the images, and Save the Extracted data in aJSON format 
  in "extracted_invoices".

3.Table Detection:
  Use Python code to detect tables in the invoice images.
  1. Identify tables and extract their coordinates.
  2. Count the number of rows and columns in each detected table.
  3. Save the extracted data in a JSON format in "table_coordinates"

4. Table Highlight:
   Using python code will also draw borders around each detected table in the original images, 
   highlighting their positions.
   The output images will be saved in the "Highlighted" folder.


5. Output:
There are two types of outputs:

   1.JSON File: Contains the coordinates and structural information for each detected table.
   2.Highlighted Images: Image files with borders drawn around each detected table.   





Conclusion

This project effectively demonstrates the ability to detect and visualize tables in invoice documents, providing structured data for further processing or analysis.
  
