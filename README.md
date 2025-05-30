# cv_parser
extracting and structuring data from CVs

This project uses Tesseract-OCR, an open-source Optical Character Recognition (OCR) engine developed by Google.
It allows the script to extract text from image-based CVs (e.g., JPG, PNG, scanned PDFs). Without it, the tool cannot read text from images accurately.

To Install Tesseract:

On Windows:
Download the installer from https://github.com/tesseract-ocr/tesseract/wiki
After installing, make sure to add the installation path (e.g., C:\Program Files\Tesseract-OCR) to your system PATH environment variable.
to add Tesseract to system PATH:
- search for Environment Variables (in windows search)
- choose 'Edit system environment variables'
- click 'environment variables'
- under system variables, find and select Path, then click Edit.
- click 'New', then add your PATH.

On macOS: 
brew install tesseract

Once installed, the pytesseract Python library will be able to communicate with the engine to extract text from image files.
