# Audibly

Audibly is a Python-based application that converts text from PDF files into speech using the `pyttsx3` text-to-speech library. It allows users to listen to the content of their PDF files.

## Features

- Select a PDF file using a file dialog.
- Extract text from all pages of the PDF.
- Convert the extracted text into speech.

## Requirements

- Python 3.x
- `pyttsx3` library
- `PyPDF2` library
- `tkinter` (comes pre-installed with Python)

## Installation

1. Clone this repository or download the `main.py` file.
2. Install the required Python libraries:
   ```sh
   pip install pyttsx3 PyPDF2
   ```

## Usage

1. Run the `main.py` script:
   ```sh
   python main.py
   ```
2. A file dialog will appear. Select the PDF file you want to convert to speech.
3. The application will read the text from the PDF and play it as speech.

## Notes

- Ensure the PDF file contains selectable text. Scanned PDFs without OCR will not work.
- The application reads the entire PDF file page by page.

## Next Steps
- Build a basic UI and deploy it on Stream Lit
