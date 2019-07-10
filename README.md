# AutoPDF TSA (Automated PDF Text Search and Analyzer)

Prepared by Hiro Yokoi, July 10, 2019<br><br>

This is the temporary PDF analyzer to ease **text search** for **Portfolio Review and Analysis (PRA)** for managing urban spatial growth.

**Limitations of this Script**
- This PDF analyzer can only analyze ONE PDF file at a time at this moment. In the future, all the PDF files in a folder will be analyzed all at once.
- If the file is OCR-read PDF, this PDF analyzer does not accurately read the text (particularly multiple phrases).

**What you have to do**
- All you have to do is to change `your_folder_path` and `your_pdf_file_name`. Then, the system will automatically anlyze the texts in the PDF.
- If you want to change the search text, you can change the String part like `String = ['aaa', 'bbb', 'ccc', 'ddd']`. Be sure to type the **lower case** character. Text search is case sensitive.
