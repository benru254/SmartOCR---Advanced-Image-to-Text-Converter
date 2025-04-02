# SmartOCR - Advanced Image to Text Converter

SmartOCR is a powerful image-to-text extraction tool built with Python and Tkinter. It utilizes Tesseract OCR for accurate text recognition and offers multi-image processing with various export options.

## Features

- Extract text from multiple images at once.
- Preprocessing options to enhance OCR accuracy (grayscale, noise reduction, contrast enhancement).
- Supports exporting extracted text as:
  - Plain text (.txt)
  - Word document (.docx)
  - PDF (.pdf)
- Intuitive GUI with progress tracking.
- Automatic language detection (future update).

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/SmartOCR.git
   ```
2. Navigate to the project directory:
   ```sh
   cd SmartOCR
   ```
3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
   If `requirements.txt` is missing, ensure you have the following Python modules installed:
   ```sh
   pip install tkinter pillow pytesseract langdetect python-docx reportlab
   ```
4. Install Tesseract OCR:
   - **Windows:** Download from [Tesseract OCR](https://github.com/UB-Mannheim/tesseract/wiki) and install it.
   - **Linux/macOS:** Install using package managers (`sudo apt install tesseract-ocr` or `brew install tesseract`).
   - Ensure the Tesseract path is correctly set in `image_to_text_12.py`.

## Usage

1. Run the application:
   ```sh
   python image_to_text_12.py
   ```
2. Click "Select Images" to choose multiple images for text extraction.
3. Select the export format (Text, Word, or PDF).
4. Click "Export Extracted Text" to save the results.
5. Extracted text will be displayed in the GUI for review.

## Requirements

- Python 3.x
- Tkinter (GUI support)
- Tesseract OCR (installed separately)
- Required Python libraries: Pillow, Pytesseract, Langdetect, Python-docx, ReportLab

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request with improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any issues or suggestions, open an issue on GitHub or reach out at [your-email@example.com].

