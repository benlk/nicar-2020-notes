# PDF OCR

Optical character recognition from PDFs

GitHub repo: https://github.com/chadday/nicar_ocr

The bad news: This is all command-line. And it assumes you're on a Mac.

If you can find the notes from the PDF 1 session, on free online tools, go for that:
- https://ireapps.github.io/nicar-2020-schedule#20200305_pdf_1_how_to_extract_text_and_tables_from_pdfs_like_a_boss_1111_all
- 

See also the PDF batch processing guides: 
- https://github.com/dankeemahill/nicar20-batch-pdf-processing
- https://www.ire.org/events-and-training/event/3433/4227/

Tabula is great for pulling tabular data from text-containing PDFs, but if you use the `-table`flag on `pdftotext` it'll be better at extracting tabular data: https://github.com/chadday/nicar_ocr#pdftotext-command-for-tables


Alternately, if the data in the PDF is in the form of images, rather than text, you'll want to use `tesseract`, which is also detailed in the tipsheet: https://github.com/chadday/nicar_ocr#scenario-2-basic-text-extraction-from-image-files
