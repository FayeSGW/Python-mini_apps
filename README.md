# PDF_translator

A short script to extract text from a pdf, translate to English, and then save the translated text to a new pdf.
It's a little clunky, and the layout of the translated pdf tends to be a little messy, but it works.

Takes two command line arguments - argument 1 is the name of the pdf to be translated, and argument 2 is the name to save the new pdf under.
Your command line should look like this:

python.exe PDF_translator.py input.pdf output.pdf

Required modules:
re
sys
pdfminer.six
googletrans
fpdf
