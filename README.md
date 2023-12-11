<h1>PDF Page Splitter</h1>
<h3>Overview</h3>
</h6>This Python script allows you to split a PDF file into individual pages. Each page is saved as a separate PDF file. The script utilizes the PyPDF2 library.</h6>

<h3>Prerequisites</h3>
Python 3.x
PyPDF2 library (install using pip install PyPDF2)

<h3>Usage</h3>
1. Clone or download the repository to your local machine.
<code>#git clone https://github.com/your-username/pdf-page-splitter.git</code>
<b>cd pdf-page-splitter</b>

2. Place the PDF file you want to split into the same directory as the script.

3. Open a terminal or command prompt and run the following command:

<code>python split.py</code>
Replace <b>split.py</b> with the actual filename if you've renamed the script.

The script will split each page of the PDF file and save them as individual PDFs in the same directory.

<h3>Configuration</h3>
Modify the input_pdf_path variable in the script to specify the path to your input PDF file.

input_pdf_path = "input.pdf"

<h3>Example</h3>
If your input PDF is named example.pdf, the script will create files like example_page_1.pdf, example_page_2.pdf, etc., for each page in the same directory as the original PDF.

<h3>License</h3>
This project is licensed under the GNU License - see the LICENSE file for details.
