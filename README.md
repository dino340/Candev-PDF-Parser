# Candev-PDF-Parser
An information extraction algorithm that would scan financial statements in PDFs format and convert the information into a database format. For the 2022 Candev Challenge

# Operation
This was written using Google Colab to prevent any platform issues, so the code is best run there with a google drive mounted to export the finished JSON files and OCR'ed PDFs if desired.

OCRmyPDF will convert PDFs which can be saved on a Colab connected Google Drive, Camelot will access the converted PDFs and extract tables from them.

# Packages used
Uses OCRmyPDF to convert scanned PDFs to a text PDF that can be scanned with Camelot

Uses Camelot to extract tables from the PDFs and export each table as a JSON file

# Future work
A filter for table data is required, generates a lot of extra tables where text formatting confuses Camelot.
