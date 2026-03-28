# English to Hindi PDF Translator

## Overview
The **English to Hindi PDF Translator** is a Streamlit-based application that allows users to enter text in English, translate it into Hindi using Google Translator, and generate a downloadable PDF file with the translated content.

## Features
- **Text Translation**: Translates English text into Hindi using the `deep_translator` library.
- **PDF Generation**: Creates a Hindi-language PDF using the `fpdf` library.
- **Download Option**: Provides an option to download the translated Hindi text as a PDF file.
- **Text Wrapping**: Ensures proper text formatting and line wrapping in the generated PDF.

## Prerequisites
Ensure you have the following dependencies installed before running the application:

```bash
pip install streamlit deep-translator fpdf
```

## Installation & Usage
1. Clone the repository:

   ```bash
   git clone https://github.com/your-repository/english-hindi-pdf-translator.git
   cd english-hindi-pdf-translator
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:

   ```bash
   streamlit run main.py
   ```

## File Structure
- `main.py` - Main script containing Streamlit UI and translation logic.
- `MANGAL.TTF` - Hindi Unicode font required for PDF generation (ensure it is in the project directory).

## How It Works
1. The user enters English text into the input field.
2. The application translates the text into Hindi using Google Translator.
3. The translated text is displayed in the app.
4. A PDF is generated with the translated Hindi text.
5. The user can download the PDF file.

## Error Handling
- If the `MANGAL.TTF` font is missing, the application will raise a `FileNotFoundError`.
- If an API request fails, an error message is displayed.

## Notes
- Ensure that `MANGAL.TTF` is placed in the project directory to support Devanagari script in the PDF.
- The translation API may have rate limits based on usage.

## License
This project is licensed under the MIT License.

## Author
[https://github.com/Sisira121]  
Email: sisiras325@gmail.com


